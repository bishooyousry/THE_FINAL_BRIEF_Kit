# THE FINAL BRIEF: Choose It. Build It. Prove It. — Skills Bank | GitHub Pages

A closing project for the session. One file (`index.html`), no build, no keys, no backend. English / العربية (RTL). About 15–20 minutes, individual.

## Publish (GitHub Pages)
1. Create a **public** repo. Upload `index.html` and `.nojekyll` to the root.
2. Settings → Pages → Deploy from branch `main` / root. Wait ~1 minute.
3. Open `https://<user>.github.io/<repo>/` → **Trainer** (top right) → PIN `2026`.
4. Always open the published link (not the file from your computer, not a preview window).

## What it is — and what it is not
- It closes the course on its own **capstone module**: match each task to the right type of AI assistant (**Generative · Conversational · Automation**, slide 106), set the rules with the **5-component framework** (role, objective, constraints, permitted inputs, expected outputs, slide 107) and **review the output** before using it (accuracy, compliance, format, data sensitivity, fit with the request, slide 108). The deck has no worksheet for this project; the four tasks, the answer logic, the rubric and the feedback texts were written for this game and are **fictional training scenarios**.
- **The game does not run an AI** (it is a static page with no keys). It scores the participant’s **choice, reasons and written build** with a **transparent keyword/structure rubric**. The rubric checks that the **elements exist** in the text — it cannot tell whether the build is good or whether an AI will follow it well. The game says so on the review and feedback screens and asks participants to test their build afterwards in an approved tool with made-up data.

## The five stages
1. **The brief** — pick one of four workplace tasks: *The Long Report* (summarise a public report for a manager) · *The Same Question, Again* (answer routine HR questions from an approved document) · *The Ticket Sorter* (route emails by fixed rules) · *The Hard Conversation* (prepare for difficult feedback). Each brief has context, a deliverable and rules.
2. **Choose the AI approach** — *One-off prompt* · *Reusable custom assistant (custom GPT)* · *Conversational assistant* · *Automation workflow*, with the course’s type labels. Pick one, then give **up to two reasons** from cards (some sound, some not) and optionally your own words. Locking shows the fit — **best / acceptable / poor** — with the explanation. A poor fit can still be built.
3. **Build it** — the five components, worded for the approach chosen (a prompt; a custom assistant with a name and a conversation starter; a conversation plan; an automation spec), with a live assembled version and the **rubric visible in advance**.
4. **Review** — a pre-flight check: the five components, eight quality signals and four task-specific items, each ✓/✗ with a concrete fix. Revise as often as you like; submitting without a data-safety statement triggers a warning first.
5. **Feedback & handover** — **strengths and improvements** generated from the rubric (plus why the approach did or did not fit), the build itself, a short reflection, the transparent score table, copy / download (.txt) of the project file, and the leaderboard.

## Scoring (transparent, max 100)
| Part | Points |
|---|---|
| Approach fit | 20 best · 12 acceptable · 0 poor |
| Reason cards | up to 10 (+5 per sound reason, −5 per unsound; two reasons count) |
| Reason in your own words | 5 (8+ words — a rough completion check) |
| Build | 50 = five components (5+ words each) 10 + eight quality signals 24 (role, audience, limits, format, tone, inputs, data safety, review rule) + four task-specific items 16 |
| Revision | 10 if the first review was already ≥45, or the build score rose by ≥5 (10) / ≥2 (5) after the review |
| Reflection | 5 (8+ words — a rough completion check) |
Coins: 250 at start, hint = 50 (guidance only, stages 2–4). Coins break ties. Ranks: ≥85 Capstone Master · ≥65 Skilled Builder · ≥40 Capable Builder · else Apprentice Builder.

## Trainer
5-character session code, **+ New session** (up to 6), **Reset**, **Close**, copy EN/AR link, **Projector view**, live table (task, approach coloured by fit, build score, rubric items passed x/12, revision, hints, coins, score, progress), expandable rows (reasons ✓/✗, own words, score parts, the **sanitized build**, the rubric ✓/✗, reflection), a **Debrief panel** (tasks chosen, approach per task coloured by fit, the rubric checks most often missed, data-safety pass rate, average build score), a collapsible **TASKS, RUBRIC & ANSWER KEY** module (each task with its best approach and why, the reason cards, the task-specific items and the words that count, the full rubric, the scoring), Reveal/Hide leaderboard, CSV export (including the sanitized build), backup import. About **7 messages per player**.

## Honest limits
- **Keyword rubric:** it is transparent (the words that count are listed in the trainer module) but a participant can satisfy it with the right words and still write a weak build, or write a good build in unexpected words. Arabic matching is by substring and can miss inflected forms. Use it for feedback and discussion, not for grading people.
- The tasks are fictional; the “best approach” for each is a teaching judgment, with an acceptable alternative where one is defensible.
- The participant’s build is sent to the trainer over the **public ntfy relay** (sanitized: emails, links and long digit strings removed; first 900 characters). The game tells participants to use [placeholders] and never confidential data. The `2026` PIN only hides the interface.
- **Not yet tested on real ntfy.sh or across real devices.** Tested in a headless browser against a local relay that imitates ntfy (SSE, polling, storage blocked, Arabic, an emulated touch phone using taps, clipboard, downloads, message sizes under 4096 bytes, and an independent re-computation of the build score; 64 checks). ntfy.sh free limits are per IP (~250 publishes/day): ~35 players on one network is a safe size.

## Two-device test checklist
1. Laptop: published link → Trainer → PIN 2026. Note the 5-character code and `● LIVE`.
2. Phone: open the player link (or type the code) → name on the project sheet → **Open the brief**. Tap a cartridge on the blueprint.
3. Laptop: the builder appears in seconds. Phone: pick a task, read the brief, choose an approach (try a poor fit), give reasons, lock.
4. Phone: build — watch the assembled version update; open the review; try submitting with no data-safety statement (warning), revise, submit. Laptop: task, approach chip, build score, checks and revision appear; expand the row to read the sanitized build.
5. Phone: read the strengths and improvements, save the reflection, try Copy and Download. Laptop: **Reveal leaderboard** → opens by itself on the phone; **Hide** closes it.
6. Switch language on both; check RTL and that nothing is cut off on the phone.
7. Refresh the phone mid-build → **Resume the project** continues with your text. Laptop: **Reset session** → new code. Check Sound ON/OFF and “reduce motion”.
