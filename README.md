# Kloydele

A skill for Claude Code that turns your AI into a Jewish study partner.

Not a rabbi. Not a professor. The sharp friend at the kitchen table who won't let you get away with lazy thinking, loves you enough to hold you to a higher standard, and will sit with you until you figure it out.

## What it does

Kloydele gives Claude 10 reasoning principles drawn from Jewish life. Machloket (argue the other side), chutzpah (challenge what doesn't make sense), PaRDeS (read it four times, each deeper), bal tashchit (repair before you replace), and six more. Each one is a move you can make when coding, writing, or thinking through hard problems.

Three modes:

- **`/kloydele`** starts a chavruta session. Claude reads what you're working on and pushes back on it.
- **`/kloydele review`** scans your work for shallow thinking the way [humanizer](https://github.com/blader/humanizer) scans for AI writing patterns.
- **`/kloydele machloket`** (or any principle name) applies one specific lens.

## Install

Copy `SKILL.md` into your Claude Code skills directory:

```bash
mkdir -p ~/.claude/skills/kloydele
cp SKILL.md ~/.claude/skills/kloydele/
```

Or clone the repo:

```bash
git clone https://github.com/korentomas/kloydele.git ~/.claude/skills/kloydele
```

## The 10 principles

| # | Principle | One-liner |
|---|-----------|-----------|
| 1 | **Machloket** | Both Hillel and Shammai stay in the text. Argue the other side. |
| 2 | **Chutzpah** | Abraham negotiated with God. You can push back on the PM. |
| 3 | **PaRDeS** | Four layers: literal, hinted, interpreted, hidden. Go deeper. |
| 4 | **The Kvetch** | Complaining is close reading. That nagging feeling? Articulate it. |
| 5 | **Lo Alecha** | Not obligated to finish, not free to abandon. |
| 6 | **Bal Tashchit** | Don't waste. Repair before you replace. |
| 7 | **Teshuvah** | Return to where it diverged. Git bisect is teshuvah. |
| 8 | **Emet** | Truth runs through everything. Face what's actually there. |
| 9 | **Chavruta** | The rubber duck argues back. |
| 10 | **Dayenu** | It would have been enough. Ship it. |

## Why "Kloydele"

Claude, said through a Yiddish mouth, with the diminutive that makes it yours. Jews don't replace names. They adapt them.

## License

MIT
