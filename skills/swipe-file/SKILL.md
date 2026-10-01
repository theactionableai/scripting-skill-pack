---
name: swipe-file
description: Log outlier videos into a swipe file and remix a proven container onto the user's topic. Keeps the winning format and swaps the topic, scenario, setting or exercise. Also remixes the user's own past winners. Use when the user shares a reel link, saves outliers, needs a format for a topic, or a past video went viral and they want another. Trigger phrases; "swipe file", "save this outlier", "log this reel", "remix this", "use this format", "container", "do that one again".
---

# Swipe File

Two of the hardest parts of making content are the idea and the form factor. The swipe file kills the second one. You do not invent formats. You find ones that already work and put your idea inside.

## What counts as an outlier

Save a reel when both are true:

- the account has **under 100K followers**
- the reel has **over 200K views**

Why small accounts: a format working for a famous creator might work because people know their face. A format working for a 25K account works because the format works. That is a blue-ocean format that has not been overplayed yet.

Bonus signal: the reel did far better than that account's usual numbers (5x or more their normal views).

Save throughout the day, not only when it is time to script. When you sit down to write, you already have containers waiting.

## Logging an outlier

Append to `my-context/swipe-file.md` (default location `~/.claude/my-context/`) using this row:

```markdown
### [Short name] (saved YYYY-MM-DD)
- Link:
- Account size / views: [followers] / [views]
- Format: [talking head / text card / list / story / demo / greenscreen / other]
- Hook (word for word):
- Container (hook with the subject removed): e.g. "The number one question I get asked is [question]. Here's exactly what I do."
- Structure: [beat 1 does X, beat 2 does Y, ...]
- Why it worked (one line):
- Topics of mine it could carry:
```

If the user only gives a link, ask them to paste the hook and describe the beats, or paste the transcript. Do not guess what a video says.

## Remixing a container

The move: keep the format, swap one or more of these:

- **Topic**: same structure, a different question or pain
- **Scenario**: same point, a different situation the viewer is in
- **Setting**: same script, a different place or backdrop
- **Exercise / example**: same format, different specifics (for fitness: "10 sit-ups, 10 squats, 10 pull-ups" becomes three different movements)

Output for the user:

```
Container: [the skeleton, subject removed]
Original: [the outlier's hook]
Your version: [their topic dropped into the skeleton]
What changed: [topic / scenario / setting / example]
What stayed: [the structure, the loop, the number slot]
```

Then hand the "Your version" line to `hook-lab` as the starting rendition.

## Remixing your own winners

Most creators already had a winner and stopped doing it. They post something that pops, then never post it again because it feels like repeating themselves.

When the user has a past winner in `my-context/winners.md`:

1. Pull its container the same way as an outlier.
2. Offer three remixes: one new topic, one new scenario, one new example set.
3. Remind them: a known winner remixed is a better bet than a brand new idea. More swings at a proven format.

## Showing up to a script session

The goal state: the user shows up with a topic and one or two containers. Ask for both at the start of every session. If they have a topic but no container, offer the three closest entries in the swipe file.
