# humanize

A free skill that turns flat, AI-sounding writing into something people actually want to read. It cuts what gives AI away, rewrites the rest with some life in it, and makes it sound like you.

## Use it in one line

Copy this line and send it to Claude, Claude Code or Codex:

```
Read https://raw.githubusercontent.com/allenanant/humanize/main/SKILL.md and follow it as your humanize skill. If you can install skills, install it. Then ask me for the text to humanize.
```

Then paste any text and say "humanize this".

## Install it for good

Claude Code:

```
git clone https://github.com/allenanant/humanize ~/.claude/skills/humanize
```

Codex:

```
git clone https://github.com/allenanant/humanize ~/.agents/skills/humanize
```

Start a new session. In Claude Code, type `/humanize`. In Codex, type `$humanize` or pick it from `/skills`. Or just say "humanize this".

## What it does

- **Pass 1, the words.** 20 patterns based on Wikipedia's "Signs of AI writing" guide: "it's not X, it's Y", one-line closers, forced lists of three, a dash in every sentence, stock words like "delve".
- **Pass 2, the shape.** Based on the StoryScope study (2026), which compared 61,608 stories by people and by five AI models. Structure alone told them apart with a 93.2% F1 score. This pass cuts the closing line that explains the point, names feelings plainly and keeps the loose ends real stories have.
- **Pass 3, make it worth reading.** Opens on the most interesting true moment, swaps slogans for real pictures, mixes short and long lines. If your text has no real detail, it asks you for one instead of making it up.
- **Pass 4, your voice.** A starter set of rules. Edit the Pass 4 part of [SKILL.md](SKILL.md) to make it sound like you.

It gives you the new text first, then a short list of what it changed. It never claims a text is "now human". It leaves code, quotes from real people and legal text alone.

## Commands

| Say | What happens |
|---|---|
| `humanize this` + your text | Rewrites it and lists the changes |
| `humanize --check` + your text | Only lists what reads as AI |
| `humanize <file>` | Rewrites that file in place (Claude Code, Codex) |

## Sources

- Wikipedia: [Signs of AI writing](https://en.wikipedia.org/wiki/Wikipedia:Signs_of_AI_writing)
- Russell, Rajendhran, Pham, Iyyer and Wieting: [StoryScope: Investigating idiosyncrasies in AI fiction](https://arxiv.org/abs/2604.03136) (2026)

Made by Allen Thomas at [The Growth Engine](https://thegrowthengine.net/prompt/human). MIT licence.
