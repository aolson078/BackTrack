# Post-Lock Scope Change Control Policy

## Purpose
Protect MVP delivery predictability after scope lock.

## Workflow
1. Submit change request ticket with rationale and impact statement.
2. Product + Engineering triage within **48 hours**.
3. Evaluate impact on timeline, quality, risk, and cost.
4. Assign decision outcome:
   - Approve for MVP
   - Defer to post-MVP
   - Reject
5. Update scope changelog and notify stakeholders.

## Hard Guardrails
- No untracked scope additions may enter active sprint.
- Any approved scope addition must include owner + acceptance criteria.
- Approved additions with unresolved dependencies cannot be scheduled.

## Escalation
Escalate to PMO + leadership when:
- A scope conflict remains unresolved for >3 business days, or
- Scope volatility exceeds 5% during first two implementation sprints.
