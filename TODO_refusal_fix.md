# Refusal Choices Fix Plan (Approved)

## Issue
After state10 ("W-Wait… please! You don't understand—there's no one else!"), showRefusalChoices() called but choices don't appear/work due to handleChoice parsing failure on non-numeric data-choice="r1".

## Steps
1. ✅ Create this TODO
2. Fix handleChoice: properly handle refusal choice ids → advance states (r3→accept state9, else→state11)
3. Ensure choices-container shows correctly (add class/timing)
4. Fix state11 desperate choices (d1→final state12, d2→accept)
5. Update images for refusal states (neutral)
6. Test all paths
7. Update main TODO.md
8. attempt_completion

**User confirmed: Use same choice UI styling/flow as newChoices()**

