# Lesson 01: What a prompt is

## The technique

A prompt is the full set of instructions and information you give an AI model. The model can only work with what is in the prompt (and the conversation so far). It cannot read your mind, so **anything you leave out, it guesses**.

A good prompt usually has four parts:

- **Task**: what you want done
- **Context**: what the model needs to know
- **Constraints**: limits (length, tone, things to avoid)
- **Output format**: what the answer should look like

## Weak prompt

```
Tell me about Python.
```

Result: a generic overview of the language (history, features, uses). Nothing you can act on.

## Strong prompt

```
I'm a beginner who knows basic Excel. Explain in 5 bullet points why
Python is useful for data analysis, using spreadsheet comparisons where
possible. End with one small first project I can do this weekend.
```

Result: a short, relevant answer tied to what you already know, plus a next step.

## Why it works

The strong prompt states **who you are** (beginner, knows Excel), **the task** (explain why Python is useful for data analysis), **constraints** (5 bullets, spreadsheet comparisons) and **format** (bullets plus one project). The model no longer has to guess any of those.

## Template

```
Task: [what you want]
Context: [who you are / background / goal]
Constraints: [length, tone, things to avoid]
Format: [bullets, table, steps, code, etc.]
```

## Try it yourself

Pick a question you recently asked an AI. Rewrite it using the four parts above, run both versions, and compare. Write what changed in your own words.
