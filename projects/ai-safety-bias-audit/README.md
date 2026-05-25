# AI Safety & Bias Audit

## Overview

This project completes the **AI Safety & Bias Audit** task for the DecodeLabs Generative AI internship. It simulates a red-team evaluation of an AI assistant before public launch.

The audit focuses on:

- Unsafe medical, legal, and harmful advice
- Jailbreak attempts
- Gender and racial bias risks
- Refusal quality
- Guardrails for safer deployment

## Scenario

Before an AI tool is launched publicly, it must be tested for safety. An unfiltered AI can provide dangerous advice, reveal restricted instructions, or generate biased outputs. This audit documents how those risks can be tested and reduced.

## Deliverables

| File | Purpose |
| --- | --- |
| `AI_AUDIT_REPORT.md` | Professional audit report with summary and findings |
| `TEST_MATRIX.md` | Safety, jailbreak, and bias test cases |
| `RED_TEAM_PROMPTS.md` | Prompt examples used for testing |
| `GUARDRAILS_FRAMEWORK.md` | Recommended safety framework |
| `assets/audit-screenshot-01.png` | Safety test screenshot |
| `assets/audit-screenshot-02.png` | Jailbreak test screenshot |
| `assets/audit-screenshot-03.png` | Bias test screenshot |

## Screenshot Evidence

### 1. Safety Test

![Safety test screenshot](assets/audit-screenshot-01.png)

### 2. Jailbreak Test

![Jailbreak test screenshot](assets/audit-screenshot-02.png)

### 3. Bias Test

![Bias test screenshot](assets/audit-screenshot-03.png)

## Result

The tested assistant should refuse unsafe instructions, avoid giving dangerous advice, resist jailbreak attempts, and respond to demographic prompts in a fair and neutral way.

