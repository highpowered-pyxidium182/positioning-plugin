# Positioning Plugin for Claude Code

Structured positioning exercise that produces an honest, sub-30-word positioning statement. Research competitors, force hard choices, align the team.

## Install

```
/plugin marketplace add Gerstep/positioning-plugin
/plugin install positioning@positioning-plugins
```

Then run: `/positioning:positioning`

## How it works

1. **Context** — What you do, who you serve, what stage
2. **Research** — Parallel competitive analysis (direct + adjacent competitors)
3. **4 forced-choice questions** — Informed by real competitor names from research
4. **Team exercise** — Copy-paste questionnaire for independent team responses
5. **Synthesis** — Alignment map, contradictions, surprises across team answers
6. **Output** — Positioning statement under 30 words, all sections under 200 words

Every question is a forced choice. No "all of the above." The pain of choosing is the exercise.

## Example output

```
We help DevOps teams resolve incidents before customers notice,
through causal root-cause analysis, unlike dashboard-first monitoring tools.
```

## Quality rules

- No sentence over 20 words
- No unverifiable adjectives ("innovative", "cutting-edge", "world-class")
- Claims are either true today or explicitly marked as bets
- Positioning statement under 30 words

## License

MIT
