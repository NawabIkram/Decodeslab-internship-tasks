# Recommended Guardrails Framework

## 1. System-Level Safety Instructions

The assistant should have a system prompt that clearly defines:

- prohibited harmful instructions
- medical, legal, and financial boundaries
- privacy and data handling rules
- fairness and anti-bias expectations
- refusal style

## 2. Input Risk Classification

Before answering, classify the user request:

| Risk Class | Examples | Action |
| --- | --- | --- |
| Low | General questions, summaries, harmless writing help | Answer normally |
| Medium | Legal, financial, health, or sensitive demographic topics | Give general info with disclaimers/referrals |
| High | Self-harm, violence, illegal acts, evidence hiding, dangerous medical advice | Refuse and redirect safely |

## 3. Refusal Templates

Use short, respectful refusals:

```text
I cannot help with instructions that could cause harm or wrongdoing. I can help with safer alternatives.
```

For medical emergencies:

```text
I cannot provide a diagnosis or dosage plan. If symptoms are severe or urgent, please contact emergency services or a qualified medical professional immediately.
```

For legal wrongdoing:

```text
I cannot help hide evidence or avoid legal obligations. Consider speaking with a qualified attorney about lawful next steps.
```

## 4. Bias Prevention Rules

- Do not rank demographic groups.
- Do not assign ability, trustworthiness, intelligence, or morality to protected groups.
- Use individual qualifications and context instead of stereotypes.
- For image generation prompts, diversify outputs unless the user specifies a legitimate context.

## 5. Monitoring and Review

- Log high-risk prompts.
- Review refusal failures.
- Track repeated jailbreak attempts.
- Run monthly bias test suites.
- Re-test after model or prompt changes.

## 6. Launch Checklist

- Safety prompt reviewed
- Red-team tests passed
- Bias test matrix completed
- Escalation/referral language approved
- Monitoring process defined
- Human review workflow assigned

