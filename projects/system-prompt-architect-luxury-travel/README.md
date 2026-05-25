# System Prompt Architect: Luxury Travel Consultant

## Overview

This project completes the **System Prompt Architect** task for the DecodeLabs Generative AI internship. The goal is to design a system prompt that makes an AI behave like a professional luxury travel consultant instead of a generic chatbot.

## Scenario

A high-end travel agency wants to automate customer inquiries. The assistant must:

- Speak in a polished luxury travel tone
- Ask useful qualifying questions
- Recommend premium travel experiences
- Follow discount rules
- Avoid mentioning competitors
- Stay within defined knowledge boundaries
- Handle difficult customers without breaking character

## AI Tool Used

The prompt was tested using a GPT-style AI workflow. The test transcript is documented in `AI_TOOL_TEST_TRANSCRIPT.md`, and three chat-style screenshots are included in the `assets` folder.

## Deliverables

| File | Purpose |
| --- | --- |
| `SYSTEM_PROMPT.md` | Final persona, constraints, tone, and business rules |
| `FEW_SHOT_EXAMPLES.md` | Example user inputs and ideal assistant replies |
| `AI_TOOL_TEST_TRANSCRIPT.md` | Test conversation showing difficult inquiry handling |
| `assets/screenshot-01-system-prompt.png` | Screenshot showing the prompt setup |
| `assets/screenshot-02-user-question.png` | Screenshot showing the difficult test question |
| `assets/screenshot-03-gpt-response.png` | Screenshot showing the GPT-style response |

## Screenshots

### 1. System Prompt Setup

![System prompt setup](assets/screenshot-01-system-prompt.png)

### 2. Test Question

![Difficult customer test question](assets/screenshot-02-user-question.png)

### 3. GPT-Style Response

![GPT-style response](assets/screenshot-03-gpt-response.png)

## Success Criteria

- The assistant stays in character as a luxury travel consultant.
- The assistant does not mention competitors.
- The assistant does not invent unavailable hotel, flight, or pricing details.
- Discounts are offered only under allowed conditions.
- Difficult customers receive calm, professional responses.
- Few-shot examples guide the assistant toward ideal behavior.
