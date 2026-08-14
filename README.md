# answer-first

**Sentence one is the answer.** Ten rules that stop your agent burying the point in paragraph four.

Once invoked they apply for the rest of the conversation. They do not expire when the topic changes.

## Install

```
/plugin marketplace add charlie947/answer-first
/plugin install answer-first@answer-first
```

Or drop `skills/answer-first/SKILL.md` into `~/.claude/skills/answer-first/`.

## What changes

**Before.** Three paragraphs of context, a summary of what it did, then the number you asked for.

**After.** The number, then the context, then one line telling you what to do next.

The rules cover: bottom line up front, lead with the next action, number multi-step work, end on one next thing, no tangents, restate where you are, real time estimates, flat tone on errors, cap options at five but never cap findings, and no preamble or closers.

## Credit

The ten rules are adapted from the open-source [i-have-adhd](https://github.com/ayoubghriss/i-have-adhd) project, MIT licensed, Copyright (c) 2026 Ayoub Ghriss. The skill packaging, the BLUF rule and the later additions are mine. Both copyright lines are in the LICENSE and the notice is preserved in the skill itself.

## Licence

MIT.
