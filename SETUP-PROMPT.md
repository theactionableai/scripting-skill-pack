# Setup prompt

Copy everything inside the box below and paste it into Claude Code. It takes about 30 to 45 minutes, most of it Claude interviewing you.

---

```
I just installed a scripting skill pack. Set it up for me. Work through the five parts below in order, and check in with me at the end of each part before moving on.

PART A: READ THE PACK
1. Ask me where I saved the downloaded pack folder. You need it for the skills, the README, the playbooks and the example.
2. Read every SKILL.md and every file in each skill's references/ folder, plus the README, the playbooks/ folder and examples/10k-leads-script.md.
3. Do NOT copy anything into ~/.claude yet. Copying happens in Part B, after the duplicate check.
4. Tell me in five lines or fewer what the pack does and the order a script session runs in.

PART B: ONE BRAIN, NO DUPLICATES
Before you change anything, audit what I already have.
1. List every skill in ~/.claude/skills/ and read my CLAUDE.md and any project instruction files.
2. Find anything that overlaps with the new pack: other scripting, hook, content, copywriting, storytelling or swipe-file skills, agents or prompts.
3. Show me a table: my existing thing | the pack skill it overlaps | what each one has that the other doesn't | your recommendation (keep mine, keep the pack's, or merge).
4. Wait for my yes. Then copy the pack's six skill folders into ~/.claude/skills/ (create the folder if it does not exist) and its my-context/ folder to ~/.claude/my-context/. Never overwrite an existing folder with the same name; merge instead. Then merge so there is exactly ONE skill per job. Move the best parts of the loser into the winner, then move the loser into an archive folder (do not delete it). I want one brain, not two agents arguing.
5. If I keep my notes in Obsidian, ask whether I want my-context/ to live in my vault instead. If yes, move it, then update the "Context folder path" line in my-context/README.md and every mention of ~/.claude/my-context/ in the pack's skills to the new path.

PART C: INTERVIEW ME
Ask me one section at a time. Short questions. Push for specifics and real numbers. Use my exact words wherever you can.

1. ICP. My buyer is fitness coaches doing around $20K a month who want to get to $50K to $100K, who have been burnt by mentors, and whose ads stopped working. Dig deeper: their top five pains in their own words, the questions they ask me most, their dream outcomes with numbers, the from-to transformations they want, and the "it's not your fault" story (what they were taught that stopped working, and what changed). Walk the want ladder with me: views, leads, money, easier sales, authority, ego. Which matter most to my buyer?
2. Voice. Ask me to paste 3 to 5 real samples of how I talk (video transcripts, voice notes, DMs, not polished copy). Then ask for phrases I use a lot, words I never use, and anything I've rejected in drafts before.
3. Winners. Ask for my 5 best performing reels: link, numbers (views, saves, comments, leads), the hook word for word, and why I think each worked. For each one, write the container (the hook with the subject removed).
4. Storytelling. Ask me to explain the frameworks I already use, in my words: the hero's journey, the "3am truth", and my emotional frequency approach, plus any others. Get the beats and one example for each.
5. CTAs. Ask for my comment keywords, what each one sends, and my go-to closing line.
6. Swipe file. Ask if I have any saved outliers yet (rule: accounts under 100K followers, reels over 200K views). Log any I give you.

PART D: WRITE IT DOWN
1. Fill in each file in my-context/ (icp.md, voice.md, winners.md, storytelling.md, ctas.md, swipe-file.md) from my answers. Keep each one to about a page. Use my words, not yours. Do not make anything up; leave a blank where I didn't answer and tell me which blanks are left.
2. Adapt the skills to how I work. Where my process differs from the pack (my own beat names, my storytelling frameworks, the way I like feedback), edit the pack skill so it matches me. Wire my storytelling frameworks into beat-builder for story and positioning beats. Do not create new skills unless a job has no home.
3. Show me a short list of every file you changed and why.

PART E: TEST RUN
Run one script with me end to end using the script-writer skill, so I can see it work.
1. Ask me for a topic and one or two outlier links or winners to use as the container.
2. Go topic, container, hook, body, laws pass, polish, in that order, one step at a time.
3. Spend most of the time on the hook. I give you a rough version first, then we do three or four renditions.
4. When I say it landed, save the framework to my-context/saved-frameworks.md.
5. Finish with three lines: what worked, what felt clunky, and one change to make to the skills. Wait for my yes before making that change.
```

---

After setup, start any script by saying "new script" in Claude Code.
