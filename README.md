# Scripting Skill Pack

A set of Claude Code skills that turn Claude into a scripting partner for short-form video. Built by Cooper Simson for Pat Hong after our 9/23 call.

The idea in one line: you bring the topic and one or two proven containers, Claude helps you nail the hook, then the rest of the script falls out fast.

This is not "AI writes your content." It is the 10-80-10 loop. You do the first 10% (the concept and a rough hook). Claude does the 80% (drafts, options, section by section). You do the last 10% (polish, your voice, your sauce).

## The six skills

**script-writer** (start here). The orchestrator. Say "new script" and it walks you through the whole session in order: topic, container, hook, body, polish. It works section by section, never the whole script at once, and when a script lands it saves the framework so the next one is faster.

**topic-ladder.** Turns a vague idea into a topic your buyer actually cares about. Every topic gets attached to a pain, a burning question, a desire, or a transformation, then pushed down the "want ladder" from views to leads to money, easier sales, authority and ego.

**swipe-file.** How to save outliers and remix them. The rule: accounts under 100K followers with a reel over 200K views. Keep the proven format, swap the topic, scenario, setting or exercise. Includes a log template.

**hook-lab.** The 4-part hook: a high-stakes sensational angle, authority (borrowed or earned), an open loop, and a specific number. Put it on the viewer's aspiration. Comes with a gate checklist and a bank of hook shapes you fill in with your own subject.

**beat-builder.** The five-beat structure: hook, descriptor, the teach, positioning, CTA. Plus the loop cadence (open a loop before you close one, never close two in a row) and the effort split (80% of your energy on beat 1).

**script-laws.** The judgment layer. Eight short laws and a kill list of things that make a script die. script-writer runs every full draft past this one before showing you; hook-lab has its own hook gate.

## What else is in here

- `playbooks/` short human versions of each idea, for reading over coffee. No Claude needed.
- `examples/10k-leads-script.md` the script we built live on the call, with every hook rendition so you can see how it got better.
- `my-context/` blank templates for your ICP, voice, winners, storytelling frameworks, CTAs, swipe file and saved frameworks. Setup fills these in with you.
- `SETUP-PROMPT.md` one prompt that installs all of this into your existing Claude setup.

## Install

1. Clone or download this folder.
2. Open Claude Code and paste the whole of `SETUP-PROMPT.md` into it.
3. When it asks, tell it where you saved this folder.

That's it. Claude does the copying for you, after it checks the skills you already have so nothing gets duplicated or overwritten, interview you for your ICP, voice and winners, fill in `my-context/`, then run one test script with you end to end.

## How a session feels once it is set up

You: "new script. Topic: coaches posting every day with zero leads. Here are two outliers: [link] [link]."

Claude pulls your context, ties the topic to a pain, maps the container from the outliers, and asks you for your rough hook. You go back and forth three or four times on the hook only. Once it lands, beat 2, then the teach, then the close. When you like it, say "save the framework."

## One rule above all

80% of the work is the first 10 seconds. If the hook is not there, do not touch the body.
