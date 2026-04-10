# Prompt engineering 101

> The single skill that makes everything else work better.

---

## What is prompt engineering?

Prompt engineering is the practice of writing clear, structured instructions that get AI to produce useful, consistent output. It's less about "tricks" and more about giving the AI the same information you'd give a smart colleague who's new to the task.

---

## The five-part prompt structure

Every effective agile prompt follows this pattern:

```
ROLE     → Who the AI should be
CONTEXT  → What information it needs
TASK     → What you want it to do
FORMAT   → How you want the output structured
TONE     → Who the audience is
```

### Example — weak prompt

```
Write a sprint goal.
```

Output: generic, could apply to any team, not useful.

### Example — strong prompt

```
ROLE: You are an experienced Scrum Master.

CONTEXT:
- Sprint 14, 2-week sprint
- Team: 5 developers, 1 QA, 1 UX
- Stories planned: password reset flow, session timeout handling, login error messages
- Business context: preparing for a security audit in 6 weeks

TASK: Draft 3 versions of a Sprint Goal that are outcome-focused (not task lists).

FORMAT: Number each option. Under each, add one sentence explaining why it works.

TONE: The goal should be motivating for the team and clear to non-technical stakeholders.
```

Output: three specific, usable Sprint Goals with rationale.

---

## The most important principle: context is everything

The AI doesn't know your team, your organisation, your sprint, or your stakeholders. The more you tell it, the better the output. Don't be afraid to paste a lot of context — a longer prompt with good information will almost always outperform a short vague one.

---

## Useful techniques

### Specify the output format explicitly

```
Format the output as:
- A table with columns: Action, Owner, Due Sprint
- Maximum 3 rows
```

### Ask for alternatives

```
Give me 3 versions — one for a technical audience,
one for business stakeholders, one for the team itself.
```

### Iterate, don't start over

```
Good, but make version 2 shorter and more outcome-focused.
Remove all technical jargon.
```

### Use follow-up prompts

```
What are the risks with this plan that I haven't considered?
```

```
What questions should I ask my team to validate this Sprint Goal?
```

---

## Prompts to avoid

| Avoid | Why |
|---|---|
| "Write me a retrospective" | Too vague — no team context, no format, no audience |
| "Is this a good sprint goal?" | Yes/no questions get yes/no answers — ask for improvement instead |
| "What should I do about my team?" | No context — give observations, not generalisations |
| "Be concise" without a word count | "Concise" means different things — say "under 150 words" |

---

## Practice exercise

Take your last retrospective's sticky notes and try this prompt. Iterate until you get something you'd actually use:

```
You are an Agile Coach. Below are raw retrospective inputs from my team.

[paste inputs]

1. Group into 3–5 themes with a one-line summary of each.
2. For the top theme, run a 5 Whys root cause analysis.
3. Suggest 2 SMART action items with suggested owners (use role titles, not names).

Format as sections with clear headers. Keep language direct and actionable.
```
