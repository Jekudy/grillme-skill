# grillme — Socratic Deep Interview Skill for Claude Code

A Claude Code plugin that turns Claude into a Socratic interviewer. Instead of giving answers, it asks powerful questions to help you discover what you already know but haven't articulated yet.

## What it does

- Conducts structured interview waves (surface → deep → insight)
- Uses analytical lenses: strategic, systemic, psychological, devil's advocate
- Tracks assumptions (verified vs unverified)
- Turns risks into concrete questions
- Produces a comprehensive summary with facts, decisions, risks, and next steps

## Install

```bash
claude plugin install "grillme@https://github.com/Jekudy/grillme-skill"
```

## Usage

In Claude Code, say any of:
- `/grillme`
- "задавай вопросы" / "grill me" / "допроси меня"
- "интервью" / "расспроси меня" / "вопросы?"

Works for any domain: product decisions, architecture, personal choices, planning, research.

## How it works

1. **Wave 1** (3-5 questions): basics — goals, context, constraints
2. **Wave 2** (2-4 questions): clarifications — edge cases, conflicts, dependencies
3. **Wave 3+** (1-3 questions): deep — contradictions, implicit assumptions, blind spots

Between waves, Claude provides a summary with facts, assumptions, and risks converted into next questions.

## License

MIT
