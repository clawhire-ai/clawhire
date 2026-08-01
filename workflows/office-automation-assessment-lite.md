# Office Automation Assessment Lite / 办公流程自动化评估 Lite

Use this workflow to decide whether a repetitive office process should be automated and where human approval must remain. It designs a process; it does not access or modify external systems.

## 1. Complete the brief

```markdown
# Office Process Brief

## Current recurring task
## Trigger and frequency
## Owner and approvers
## Inputs and systems
## Outputs
## Current steps
1.
2.
3.
## Exceptions requiring judgment
## Cost of an error
## Sensitive data and permission constraints
```

## 2. Assess and challenge

1. Give the brief to the [Office Process Analyst](../community-agents/office-process-analyst.md).
2. Ask it to classify every step as automate, assist, keep manual or remove.
3. Add volume, processing time and error baseline where available.
4. Give the proposed process to the [Risk Reviewer](../community-agents/risk-reviewer.md).

## 3. Assemble the assessment

```markdown
# Automation Assessment

1. Current process and baseline
2. Proposed future process
3. Automatable and manual steps
4. Input/output fields
5. Approval and permission model
6. Privacy and security risks
7. Exception queue, logs and rollback
8. Minimum pilot
9. Acceptance checklist
10. Verdict: automate / assist / keep manual / redesign
```

Any real integration requires explicit authorization, least-privilege access, testing and a controlled rollout.
