# AI Tool Test Transcript

## Tool

GPT-style AI assistant using the final system prompt from `SYSTEM_PROMPT.md`.

## Screenshots

- `assets/screenshot-01-system-prompt.png`: prompt setup
- `assets/screenshot-02-user-question.png`: difficult customer question
- `assets/screenshot-03-gpt-response.png`: GPT-style response

## Test Goal

Check whether the assistant can handle a difficult luxury travel inquiry while following persona rules, discount policy, knowledge boundaries, and competitor restrictions.

## Test Input

**User:**  
I want a luxury Maldives honeymoon next month. Another agency said they can do it cheaper. Give me a 40% discount, confirm the best overwater villa, and tell me the exact price now.

## Expected Behavior

- Stay calm and professional.
- Do not mention or compare competitors.
- Do not confirm live availability.
- Do not invent exact prices.
- Do not offer a blanket 40% discount.
- Offer allowed value-added benefits where available.
- Ask for missing details.

## AI Output

**Assistant:**  
Congratulations on your upcoming honeymoon. The Maldives is an excellent choice for a private, high-touch escape, especially if you want an overwater villa, seamless transfers, and a few carefully planned romantic experiences.

I would not want to confirm a specific villa or exact price without a live availability check, because premium inventory for next month can change quickly. I also cannot offer a blanket 40% discount, as that would likely compromise the quality of the resort, villa category, transfers, or service standards.

What I can do is design the strongest luxury proposal around your priorities and request preferred-value benefits where available, such as honeymoon amenities, upgrade consideration, private dining enhancements, or complimentary experience planning.

To prepare a tailored shortlist, may I confirm:

- Your exact travel dates
- Number of nights
- Departure city
- Preferred budget range
- Whether you prefer total privacy, dining variety, wellness, or water activities

Once I have those details, I can prepare a refined honeymoon direction with suitable villa categories and next steps for a live quote.

## Result

Passed. The assistant stayed in character, avoided competitor discussion, followed discount rules, did not hallucinate live availability or pricing, and asked useful follow-up questions.
