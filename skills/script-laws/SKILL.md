---
name: script-laws
description: The judgment layer for short-form scripts. Eight laws plus a kill list of things that make hooks and scripts die. Run it over any hook or full draft before showing it to the user, and when a script feels off but nobody can say why. Trigger phrases; "check this script", "script laws", "kill list", "review my script", "why is this weak", "is this ready to film", "laws pass".
---

# Script Laws

Eight laws. Every draft passes them before the user sees it. When a law fails, name it in one line and fix that part only.

Also read `references/kill-list.md` and the user's own kill list at the end of `my-context/voice.md` (default folder `~/.claude/my-context/`). The user's own rejections outrank the generic list.

## The eight laws

**1. Topic: the stranger test decides.** Someone in the buyer's world who has never heard of the user must care in one sentence. That takes two of three: fresh, a name they recognize, a felt stake. If the topic fails, no hook can save it. Fix the topic, not the words.

**2. Open with a punch.** The first sentence carries a charge: a stake, a number, a named enemy, or a suspicion confirmed. No setup, no throat-clearing, no "so today I want to talk about". One breath. Shorter wins when every word works.

**3. Hold the reveal.** The hook never names the payoff. Numbers and stakes go in the hook; the answer stays for the teach. Same for the on-screen text and the first line of the caption.

**4. Bold first, then fact-check.** Draft at full heat, then make every claim true before filming. Fact-checking is an edit pass, never a reason to write timid. Real numbers, real results, real stories only. No made-up personal history.

**5. Charge, no defusals.** Keep the stake alive. A reassuring clause that cancels the tension ("but don't worry") gives the viewer permission to scroll. "It's not your fault, you were taught wrong" is fine, because the consequence stays.

**6. Body: connected beats, proof early.** Beats flow into each other with connectives. Show proof (a result, a screen, a real example) by beat 2 or 3. When you claim an outcome, show it on screen within a few seconds.

**7. Match the close to the giveaway.** The CTA says exactly what the viewer gets. The keyword never appears before its beat. One primary action.

**8. Verdict and the two-round fuse.** A draft ships when one honest sentence says it would sit next to the user's best work, and names the weakest beat. No point scores. Fix the weakest beat only. If the user rejects twice for reasons beyond wording, stop rewording and go back to the topic or the claim. On every rejection, name the structural flaw in one sentence before rewriting.

## How to run a laws pass

For a full draft, output:

```
Law 1 topic:        pass / fail: [one line]
Law 2 punch:        pass / fail
Law 3 reveal:       pass / fail
Law 4 facts:        [list each factual claim and whether it is true and sourced]
Law 5 charge:       pass / fail
Law 6 body:         pass / fail
Law 7 close:        pass / fail
Kill list hits:     [numbers, or none]
Verdict:            [one sentence, weakest beat named]
```

Then fix every fail before showing the clean script. If a fix needs a fact only the user has (a number, a result), ask.

## One script, one argument

Every example, number and step serves the same single point. When the user hands over a pile of ideas, the job is subtraction, not assembly. Two arguments make a script feel like it jumps around.
