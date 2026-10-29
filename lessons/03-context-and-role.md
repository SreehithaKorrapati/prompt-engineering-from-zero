# Lesson 03: Give context and a role

## The technique

Tell the model **who it should act as** and **who the answer is for**. A role sets the expertise and style; context sets the situation. Together they change vocabulary, depth and priorities.

## Weak prompt

```
Explain overfitting.
```

## Strong prompt

```
Act as a patient data science tutor. Explain overfitting to someone who
has just learned linear regression. Use one everyday analogy and one
tiny numeric example. Keep it under 150 words.
```

## Why it works

- **Role** (patient tutor) sets tone and teaching style
- **Audience** (knows linear regression) sets the depth
- **Requirements** (analogy and example) make it concrete
- **Limit** (150 words) keeps it focused

## Tip

Roles help most with tone and depth. They do not make the model know things it doesn't. For facts, give the model the source material in the prompt.

## Template

```
Act as [role]. I am [who you are / level].
Goal: [what you're trying to achieve].
[Task]. Format: [format]. Length: [limit].
```

## Try it yourself

Ask the same question as "a strict reviewer", "a friendly mentor" and "a skeptical manager". Note how each answer differs.
