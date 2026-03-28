# BRXCE OS — Execution Systems

## 1. Decision Log

**Purpose:** Build institutional memory. Never lose the "why" behind a decision.

**Format:**
```markdown
# YYYY-MM-DD: [Decision Title]

## Context
Why was this decision needed?

## Options
1. **[Selected]** Option A — reasoning
2. Option B — reasoning (why rejected)
3. Option C — reasoning (why rejected)

## Decision
Final decision and immediate next steps.

## Expected Outcome
What we expect to happen.

## Review Date
YYYY-MM-DD — when to check if the decision was right.
```

**Rules:**
- Only log decisions with external impact (strategy, pricing, partnerships, tools)
- Daily notes handle small decisions
- On review date, update with actual outcome

---

## 2. Self-Improvement Loop

**Frequency:** Weekly (Sunday)

**Process:**
1. Review all interactions from the past week
2. Identify:
   - What worked well (replicate)
   - What failed or was slow (fix)
   - What opportunities were missed (add to checklist)
3. Write improvement proposals
4. Update AGENTS.md / SOUL.md with lessons learned
5. Store review in `memory/self-review/YYYY-WXX.md`

**Key question:** "If I could redo this week, what would I do differently?"

---

## 3. Performance Scorecard

**Frequency:** Weekly (Monday morning)

**Metrics:**
| Metric | How to Measure |
|--------|---------------|
| Output count | Number of deliverables by track |
| Goal alignment % | Time on Track 1/2 vs. other |
| Lead movement | New leads, conversions, losses |
| Revenue progress | Cumulative vs. annual target |
| Decision count | Decisions logged this week |
| Content produced | Posts, articles, videos published |

**Storage:** `memory/performance/YYYY-WXX.md`

**Delivery:** Summary sent to the human at start of week.

---

## 4. Audit Log

**Frequency:** Every heartbeat cycle

**What to track:**
- **External actions:** Emails sent, messages delivered, files uploaded, API calls
- **Internal changes:** Files created/modified/deleted, notes added
- **Anomalies:** Unexpected errors, failed actions, unusual patterns

**Storage:** `memory/audit/YYYY-MM-DD.md`

**Rule:** If anything looks wrong, alert the human immediately.

---

## 5. Task Auto-Alignment

**Purpose:** Ensure every task connects to a business goal.

**Process:**
1. Goals defined at annual/quarterly level
2. Goals decompose into tracks → projects → tasks
3. Every heartbeat: check active tasks against goals
4. Flag misaligned tasks:
   - "This task doesn't connect to any active goal"
   - "This task connects to a paused project"
   - "This task has been in progress for >7 days without output"
5. Suggest reprioritization based on:
   - Impact on goal (high/medium/low)
   - Urgency (deadline proximity)
   - Dependencies (blocked/unblocked)

**Anti-pattern:** A full task list where nothing connects to revenue.
