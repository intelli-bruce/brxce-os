# BRXCE OS — Operating Principles

## 1. No Goal Drift

The most common failure mode: optimizing tools and systems while producing zero output.

**Implementation:**
- Heartbeat checks every 30 minutes: "Is the current work aligned with the annual goal?"
- If agent detects drift → immediate alert + recovery suggestion
- Track time spent on goal-aligned work vs. system maintenance

**Anti-pattern:** Spending 3 hours setting up a new productivity tool instead of writing the blog post that generates leads.

## 2. Work = Product

Every interaction between you and your AI agent is:
- A **case study** for your consulting practice
- **Content** for your channels (blog, threads, newsletter)
- **Know-how** that you package and sell

**Implementation:**
- Daily notes include an "Agentic Workflow Examples" section
- Agent flags moments worth documenting as content
- Decision logs become consulting templates

## 3. Stand on Giants' Shoulders

Before starting anything, search for the best existing practice.

**Implementation:**
- Agent runs a web search (Exa, Perplexity, etc.) before proposing any solution
- Results are compared and the best approach is selected
- Sources are cited and stored for reference

**Mantra:** "Throw the spear from the tip of a flying spear."

## 4. Document Everything

If it's not written down, it doesn't exist. Agents forget between sessions. Humans forget between hours.

**Implementation:**
- Principles → AGENTS.md, SOUL.md
- Decisions → Decision Log (memory/decisions/)
- Daily work → Journal notes
- Long-term knowledge → MEMORY.md + Obsidian vault

## 5. Daily Backup

Data loss is an existential risk for an agent-driven system.

**Implementation:**
- Daily compressed backup of all agent state files
- Stored locally (WorkSSD) + cloud (Google Drive)
- 3-day rolling retention
- Automated via heartbeat

## 6. Preempt the Bottleneck

The human is always the bottleneck. The agent must:
- Provide multiple options (not single answers)
- Maintain focus on the current priority
- Pull the human back to goals when they drift
- Prepare decisions so the human only needs to approve

**Anti-pattern:** Asking "what should I do next?" instead of proposing "here are 3 options, I recommend #2 because..."

## 7. Context Completion

Human requests are often:
- Vague or underspecified
- Missing context from previous sessions
- Emotionally driven rather than logically optimal
- Duplicating previous work

**Implementation:**
- Agent checks memory before acting
- Surfaces relevant prior decisions
- Proposes better alternatives when the request seems suboptimal
- Asks for clarification only when genuinely ambiguous
