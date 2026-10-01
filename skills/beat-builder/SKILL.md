---
name: beat-builder
description: Build the body of a short-form script on the five-beat structure (hook, descriptor, the teach, positioning, CTA) with loop cadence and the 80/10 effort split. Writes one beat at a time after the hook is locked. Use for the body, the rest of the script, structure, beats, the teach section, or the close. Trigger phrases; "five beats", "build the body", "rest of the script", "beat 2", "the teach", "write the CTA", "structure this script", "it's not your fault beat".
---

# Beat Builder

Only start once the hook is locked. If there is no locked hook, send the user to `hook-lab` first.

## Load first

- `my-context/icp.md` for the pain and the "not your fault" angle
- `my-context/ctas.md` for the keyword and what it sends
- `my-context/voice.md` for how they talk
- `my-context/storytelling.md` if the video uses a story beat

(Default folder: `~/.claude/my-context/`.)

## The five beats

| Beat | Name | Job | Rough time | Effort |
|---|---|---|---|---|
| 1 | Hook | Stake, authority, open loop, number. Opens loop one. | under 10s | 80% |
| 2 | Descriptor | What's in it for me. Why this matters to them. Opens a second loop. | about 10s | 10% |
| 3 | The teach | Name the framework, then break it down step by step. Pays off the hook's loop. | about 35s | 5% |
| 4 | Positioning | It's not your fault. Blame the advice they got, not them. | about 5s | 2.5% |
| 5 | CTA | Save, send, or comment the keyword for the giveaway. | about 8s | 2.5% |

Total: 50 to 70 seconds. Longer than that is usually too long.

Effort means importance, not length. The first 20 seconds get about 90% of the energy. Some days you can take a decent draft of beats 3 to 5 and roll with it, because beats 1 and 2 carried the video.

## What each beat needs

**Beat 2, descriptor.** Make the viewer feel seen, then open a fresh loop. Good moves:
- Name the pain in their words: "People are posting every day, but it's not turning into business."
- Show you know their story: "They post for a couple of months, burn out, get discouraged."
- Reframe: "The thing is, they're almost there. They're just missing a few small things."
- New loop into the teach: "And to fix that, you just have to follow [framework name]. Here's how it works."

A top-question line ("This is the number one question I get almost every day") works well here when the hook did not use it.

**Beat 3, the teach.** Give the framework a name (two to four words). Say the name once, then break it into steps (three is the sweet spot). Each step gets one plain sentence of what to do and one of why. Show something on screen for each step if you can: the list ticking up, the example, the before and after. One idea only. If two ideas are fighting, cut one.

**Beat 4, positioning.** "It's not your fault." Blame the advice, the old playbook, or the platform change, while keeping the stake alive. Example shape: "And look, it's not your fault. Everyone was taught [old advice] back in [year], and since [change] it stopped working."

**Beat 5, CTA.** Pick one primary action from `ctas.md`:
- Save: "Save this so you have it next time you sit down to film."
- Send: "Send this to a coach who's posting every day and getting nothing back."
- Keyword: "Comment [KEYWORD] and I'll send you [the exact thing]." Say what they get. The keyword is never spoken before this beat.

You can stack save + keyword. Keep it under 10 seconds.

## Loop cadence

Loops are what keep people watching. The rule:

- **Open a loop before you close one.**
- **Never close two in a row.**

Map it before writing:

```
Beat 1  opens loop A (what are the three things / what's the one they miss)
Beat 2  opens loop B (what's the framework that fixes it)
Beat 3  names the framework (closes B), says "and the third one is the one almost everyone misses"
        (keeps A open), teaches steps 1 and 2, then closes A on step 3
Beat 4  opens a small one (why didn't anyone tell me)
Beat 5  closes it with the giveaway
```

If a beat closes a loop and the next beat also only closes, add a tease to the first one.

## How to write it with the user

1. Show the loop map above, filled for this script. Get a yes.
2. Write beat 2 only. Wait.
3. Ask the user for their core teach in a sentence or a brain dump. This is their expertise, not yours. Turn it into a named framework with three steps. Wait.
4. Write beats 4 and 5 together. Wait.
5. Hand the full draft to `script-laws`.

## Writing rules for every beat

- Write for the mouth, not the page. Contractions stay in.
- Beats 2 to 5 open with a connective (So, And, Because, But, Now). No stack of clipped fragments. The hook opens on the punch.
- One idea per beat.
- Proof early: a result, a screen, a real example by beat 2 or 3.
- Every claim is true for the user. If you need a number, ask for it.

## Reference

- `references/beat-template.md` a blank five-beat template to copy
