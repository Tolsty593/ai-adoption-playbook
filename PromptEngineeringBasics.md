# Prompt Engineering Basics

A prompt is the request you give to an AI tool. The quality of the answer depends heavily on the quality of the prompt. This page explains how to write prompts that get useful results the first time.

## Effective Prompt Structure

A good prompt has three core parts.

### Objective

Clearly state what you want.

Example:

> Write a professional email responding to a customer enquiry.

Start with a verb that names the task: write, summarise, compare, explain, list, rewrite.

### Context

Provide background information.

Example:

> The customer is asking about delayed delivery of a software deployment.

The tool knows nothing about your situation unless you tell it. Include what a new colleague would need to know to do the job.

### Output Format

Specify expectations.

Example:

> Provide bullet points followed by a summary paragraph.

Say how long the answer should be and what shape it should take: a table, a numbered list, a short paragraph, an email.

### Putting it together

> Write a professional email responding to a customer enquiry. The customer is asking about delayed delivery of a software deployment. The delay is two weeks, caused by additional security testing, and the new date is confirmed. Provide bullet points covering the reason and the new date, followed by a summary paragraph. Keep the tone apologetic but confident.

## Optional Extras

Add these when the three core parts are not enough.

| Element | What it does | Example |
| --- | --- | --- |
| Audience | Sets the level of detail and language | "The reader is a non-technical senior manager." |
| Role | Gives the tool a point of view | "Act as an experienced service desk analyst." |
| Tone | Sets the style | "Friendly and reassuring, without jargon." |
| Constraints | Sets limits | "No more than 150 words. Do not mention pricing." |
| Examples | Shows what good looks like | "Follow the style of this example: ..." |

## Before and After

| Weak prompt | Stronger prompt | Why it is better |
| --- | --- | --- |
| "Write about password security." | "Write five tips on creating strong passwords for office staff who are not technical. Use plain English and one sentence per tip." | Names the audience, the number of points and the style |
| "Summarise this." | "Summarise the report below in three bullet points for a manager deciding whether to approve the budget. Put the main risk first." | Says who it is for, why they need it and what matters most |
| "Fix this email." | "Rewrite the email below so that it is shorter and more polite. Keep every date and name exactly as it is." | Says what to change and what to leave alone |

## A Reusable Template

Copy this, fill in the brackets and delete any line you do not need.

```text
Task: [what you want produced]
Context: [background the tool needs to know]
Audience: [who will read it]
Format: [length and layout, for example "five bullet points" or "a table"]
Tone: [for example formal, friendly, plain English]
Constraints: [anything to include, avoid or keep unchanged]
```

## Refining the Answer

The first answer is a starting point. Follow up in the same conversation instead of starting again.

| If the answer is | Try saying |
| --- | --- |
| Too long | "Cut this to half the length." |
| Too complicated | "Rewrite this in plain English for someone new to the subject." |
| Too general | "Make this specific to a team of ten people in a finance department." |
| The wrong format | "Put this in a table with columns for task, owner and date." |
| Missing something | "Add a section on the risks." |
| Not convincing | "What are the weaknesses in this answer?" |

You can also ask the tool to help with the prompt itself:

> Before you answer, ask me any questions you need to give a better response.

## Best Practices

- **Be specific.** Say exactly what you want, including length and level of detail.
- **Provide context.** Give the background, the purpose and any facts the tool needs.
- **Define audience.** Say who will read the result and what they already know.
- **Request structured outputs.** Ask for bullet points, tables or numbered steps when they will be easier to use.
- **Iterate and refine.** Treat the first answer as a draft and improve it with follow-up instructions.

## Common Mistakes

| Mistake | What to do instead |
| --- | --- |
| One-line prompts with no background | Add the context a new colleague would need |
| Asking for several unrelated things at once | Ask for one thing at a time |
| Leaving the format to chance | Say how long and in what layout |
| Starting a new conversation after every poor answer | Refine the answer with a follow-up |
| Including confidential details that the task does not need | Leave them out or replace them with placeholders |

## Before You Use the Result

A well-written prompt improves the answer, but it does not guarantee that the answer is correct. Check facts and figures, read the whole output, and follow the guidance in [AI Best Practices](AIBestPractices.md).

## Related documents

- [Getting Started with AI](GettingStarted.md)
- [AI Best Practices](AIBestPractices.md)
- [Common AI Support Questions](CommonUserQuestions.md)
- [Adoption Framework](AdoptionFramework.md)
