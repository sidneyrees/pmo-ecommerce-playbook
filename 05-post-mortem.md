# 5. Post-Mortem Template

Run this 1-2 weeks after go-live, once the dust has settled but while memory is still fresh. Goal: extract process improvements for the *next* project, not to assign blame for this one. Blameless framing gets you honest input; blame framing gets you defensiveness and silence.

```markdown
# Post-Mortem — [Project Name]
Date: [date] · Facilitator: [name] · Attendees: [names]

## Summary
[2-3 sentences: what was the project, what was the outcome]

## Timeline
| Date | Event |
|---|---|
| | Project kickoff |
| | Feature freeze |
| | Go-live |
| | [Any major incident] |

## What Went Well
- [Specific, not generic — "risk matrix caught the SKU mismatch before it hit production" not "good planning"]
-
-

## What Didn't Go Well
- [Specific and blameless — describe the process gap, not the person]
-
-

## Root Cause Analysis (for anything that broke in production)
| Issue | Root Cause | Contributing Factors | Detected By | Time to Resolve |
|---|---|---|---|---|
| | | | | |

## Metrics: Planned vs Actual
| Metric | Planned | Actual | Variance |
|---|---|---|---|
| Launch date | | | |
| Budget | | | |
| Post-launch conversion rate | | | |
| Post-launch page load time | | | |
| Critical bugs in first 2 weeks | | | |

## Action Items for Next Project
| Action | Owner | Add to which template? |
|---|---|---|
| | | e.g. "Add to Risk Matrix §2.2" |
| | | |
| | | |

## Would We Do This Again the Same Way?
[Yes/No + why — this is the single most useful question in the whole document]
```

## 5.1 Facilitation Notes

- Send the metrics table as pre-work so the meeting isn't spent hunting for numbers.
- Ask "what surprised us?" — surprises reveal gaps in the risk matrix or charter more reliably than asking "what went wrong?"
- Every action item should update one of the other four templates in this playbook. A post-mortem that doesn't change the charter, risk matrix, checklist, or reporting cadence for next time was just a venting session.

---
[⬅ Back to playbook index](../README.md)
