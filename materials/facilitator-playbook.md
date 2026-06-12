# Facilitator Playbook

The complete run-of-show for "Roadmapping for Success". Read it end-to-end before you run the session. It is the only thing you need on the day.

Default total length: **90 minutes**. A 2-hour variant is described in Appendix C. All timings marked [Inference] are facilitator defaults; adjust freely to your room.

---

## Timeline at a glance

| Block | Title | Time | Cumulative | Mode |
| --- | --- | --- | --- | --- |
| 1 | Intro & theory | 0:00–0:15 [Inference] | 0:15 | Plenary |
| 2 | Scenario build | 0:15–0:45 | 0:45 | Team build |
| 3 | Distractors round 1 | 0:45–1:00 [Inference] | 1:00 | Team build |
| 4 | Final distractor | 1:00–1:10 [Inference] | 1:10 | Team build |
| 5 | Team presentations | 1:10–1:25 [Inference] | 1:25 | Plenary |
| 6 | Close & harvest | 1:25–1:30 | 1:30 | Plenary |

The build time across Blocks 2–4 totals **~55 minutes**. That is the load-bearing number; protect it.

---

## Materials & room setup

- One copy of `materials/scenario-victory-fashion.md` per participant. Print double-sided.
- One full set of distractor cards per team. Print, cut, sort into three piles: General (G1, G2), Per-team (T1–T10), Final.
- Flip-chart paper or large sticky paper, one sheet per team. Coloured markers and sticky notes.
- The four SVG examples on screen, ready to switch to during Block 1. Have the anti-pattern queued up last.
- Optional but recommended: print one A3 copy of the Victory as-is landscape per team.

Tables of **3–6 people**, ideally with a mix of architects, product owners, and delivery roles per table. Six is the upper limit; beyond that, conversations fragment.

---

## Block 1 — Intro & theory (0:00–0:15)

### Beat 1.1 · The hook (1 min)

> **You say:** "Show of hands — who in this room has been on a programme where you saw the roadmap once, at the kick-off, and then watched it quietly vanish? Keep your hand up if it then re-appeared at the end as evidence that you delivered something different from what was planned."

Most hands go up. That is the room you are teaching.

### Beat 1.2 · The numbers (2 min)

Show the Standish Group CHAOS trend. The headline: roughly **24% of all IT projects are considered failed** [Unverified — confirm against the latest CHAOS report before you cite it on stage], with another ~50% "challenged", and the trendline across Waterfall → Agile → SAFe has not meaningfully improved.

> **You say:** "We are not going to fix this with a slide. But every failed programme we have personally seen had the same three symptoms: scope creep, mismanaged dependencies, and stakeholders who had forgotten *why* the work was being done. The cheapest insurance against all three is a roadmap people actually use."

### Beat 1.3 · What a roadmap is and is not (3 min)

Two columns on the slide. Read them straight. Resist the temptation to soften the "is NOT" column — that is where the laughs and the recognition live.

- Are: as-is → to-be · capabilities to delivery · visibility · business value · audience · single view.
- Are NOT: SoWs · backlogs · rigid · task-oriented · detail-heavy · the answer to everything.

### Beat 1.4 · The four types (8 min)

Show the four example SVGs in this order:

1. **Business Capability Roadmap.** 90 seconds. Audience: execs. Language: business outcomes. Point at the dashed dependency.
2. **Business Feature Roadmap.** 90 seconds. Audience: product owners. Note on-track vs at-risk colour. Trace the *Identity & SSO → Case deflection bot → Entitlement checks* dependency chain out loud.
3. **Technology System Roadmap.** 90 seconds. Audience: architects and delivery. Note the swimlanes by technical concern. Highlight the ISO certification milestone.
4. **`roadmap_final_v7_FINAL(2).pptx`.** 90 seconds. Audience: nobody. Watch the laugh land. Then drop the line:

> **You say:** "Every team in this room has shipped a version of this. The point of today is to send you home with the tools to never ship one again."

### Beat 1.5 · The traceability rule (1 min)

Frame Business Capability vs Technology System along the **Salesforce Well-Architected** pillars (Trusted, Easy, Adaptable). [Unverified — confirm pillar wording at https://architect.salesforce.com/well-architected before delivery; do not quote from memory.]

The rule: **every line on the technology roadmap must trace back to at least one business capability**. No orphans.

### Watch-outs for Block 1

- Do not spend more than 15 minutes here. The room came to build, not to listen.
- If the room is unusually senior, compress to 10 minutes by dropping Beats 1.1 and 1.2 entirely.
- Do not over-define "Well-Architected". One sentence is enough; teams will ask if they want more.

---

## Block 2 — Scenario build (0:15–0:45)

### Beat 2.1 · Form teams and hand out (2 min)

Self-organise into teams of **3–6**. Hand out the Victory scenario. Display the as-is landscape on screen.

> **You say:** "Read the scenario together for five minutes. Then, before you draw anything, agree at the table on two things: which **type** of roadmap you are building, and **why** that type for this audience. Write your answers in the corner of your sheet so the facilitators can see them."

### Beat 2.2 · The build (25 min)

Teams build. Facilitators circulate. Carry a marker but do not draw on their sheets.

**Do** — at each table, ask one of these questions:

- "Who is the audience for this roadmap?" (If they cannot answer in one sentence, they are building the anti-pattern.)
- "Which business goal does this line serve?" (Pick any line they have drawn.)
- "What is your single explicit dependency?" (If they have none, they are not yet at a roadmap.)

**Do not** — do not correct over-engineering. Do not point out missing items. Let the distractors do that work in Block 3.

### Watch-outs for Block 2

- Teams will try to do everything. They will run out of time. **This is the design**, not a problem to fix.
- Teams that finish early are wrong. Push them: "What happens to this if the CFO cuts capex by 30%?" — and they discover they have not actually thought about it.
- If a team is silent, ask "who is the loudest stakeholder in your scenario right now?" — it usually unlocks the conversation.

---

## Block 3 — Distractors round 1 (0:45–1:00)

### Beat 3.1 · The drop (2 min)

Move to each table with the two General cards (G1, G2) and one Per-team card. Read the breaking-news narrative out loud at the table — do not just hand the cards over. The voicing matters.

> **You say (at the table):** "Breaking news. *[Read the narrative.]* You have ten minutes. What moves on your roadmap?"

### Beat 3.2 · Adapt, do not restart (12 min)

Walk the room. Watch for the two failure modes:

- **Teams that restart.** Stop them. "You are not redrawing the roadmap. You are showing how it absorbed this change. Put the old items in red; draw the new ones in green over the top." This is the most important coaching moment in the whole session.
- **Teams that ignore the distractor.** "You have decided this doesn't affect the roadmap. Who do you call to confirm that, and what do you tell them?" — usually surfaces the stakeholder conversation they were avoiding.

Teams that adapt cleanly should be told so, out loud, at the table. Confidence at this stage is fuel for the presentations.

### Watch-outs for Block 3

- If you handed out the General cards on paper at the start, you robbed yourself of the drop. Hold them back.
- Per-team cards should be **genuinely different** per team — that is what makes the presentations interesting in Block 5.

---

## Block 4 — Final distractor (1:00–1:10)

### Beat 4.1 · The curveball (2 min)

Drop the same final card on every team simultaneously. Default is **T3 · New CEO with B2C focus**.

> **You say (to the room):** "One more. The board has just appointed a new CEO with a strong direct-to-consumer pedigree. Her first all-hands is Monday. Wednesday she wants to be walked through *your* roadmap and told how it accelerates the consumer story. You have eight minutes."

### Beat 4.2 · The squeeze (8 min)

The teaching point lands in this block. Teams with capability-first roadmaps adapt by re-weighting and re-emphasising. Teams with thinly disguised project plans start scrabbling. Let the difference happen. Do not rescue.

### Watch-outs for Block 4

- The eight minutes is short on purpose. Real stakeholder change is also short. Resist requests to extend.
- Some teams will get more out of the discussion than out of the redraw. That is fine — make sure they nominate one person to articulate the *thinking* in the presentations.

---

## Block 5 — Team presentations (1:10–1:25)

### Beat 5.1 · The frame (1 min)

> **You say:** "Two minutes per team. Tell us: which roadmap type did you build, who is the audience, and — the important one — *how did your roadmap change as the world moved on you?* Save the original layout for last."

### Beat 5.2 · Presentations (rotate, ~2 min per team)

For a room of six teams, this is 12 minutes plus rotation overhead — you will be tight. For larger rooms, ask teams to nominate one representative and run a "speed round" of 60 seconds.

### Beat 5.3 · The rubric

Score informally in your head against four criteria. Call out a team that did one of them especially well; you do not need to score every team on every criterion.

| Criterion | Question | Watch for |
| --- | --- | --- |
| **Traceability** | Does every line on the roadmap connect to a business capability or goal? | Orphans, technical-debt items disguised as features |
| **Sequencing** | Are dependencies explicit, and do they survive the distractors? | Bars on top of each other with no order signalled |
| **Audience fit** | Does the roadmap match its stated audience? | Exec roadmaps with technical jargon; system roadmaps with no architecture |
| **Adaptability** | How gracefully did the distractors get absorbed? | Whole-sheet redraws (bad); coloured-over deltas (good) |

### Watch-outs for Block 5

- Do not let one team dominate. The 2-minute clock is non-negotiable.
- The best presentations are usually the ones that admit something they got wrong. Reward that explicitly.

---

## Block 6 — Close & harvest (1:25–1:30)

### Beat 6.1 · The takeaway

> **You say:** "A roadmap that cannot change is a poster. A roadmap that changes transparently is a power tool. Everything we did today was to give you the second one."

### Beat 6.2 · The harvest

Three quick prompts to the room — single-sentence answers, popcorn-style:

1. "One thing you'll do differently in your next roadmap."
2. "One thing this session got wrong about your reality."
3. "One distractor we should add for next time."

Note the third one — it is how the kit gets better.

### Beat 6.3 · The handoff

Point everyone at https://github.com/rammc/roadmapping-for-success — the kit is theirs to run with their own teams. CC BY 4.0; attribution welcome; tell us where you ran it.

---

## Appendix A — Flex & contingency

### If you are short on time

- Skip Beats 1.1 and 1.2; start at "What a roadmap is and is not". Saves 3 minutes.
- Drop Block 4 entirely; run the General + Per-team distractors as your only round. Saves 10 minutes.
- Run Block 5 as a "share-out" — one nomination from the room per criterion — instead of full team presentations. Saves up to 10 minutes.

### If you have extra time

- Add a deliberate **15-minute "stakeholder interview" mid-build**: one facilitator plays the new CEO, teams have to pitch their roadmap as-is for 2 minutes each.
- Expand Block 6 into a **20-minute reflection** on the four roadmap types: where in their own work would each show up?

### If a team is stuck

- Sketch the four-swimlane skeleton for them silently on a fresh sheet (Sales / Service / Platform / Marketing or Ops / Infrastructure / Compliance / Security depending on roadmap type chosen). They almost always restart from there.

### If a team is over-confident

- Drop a second per-team distractor on them quietly. Usually T7 or T8 — the ones that require an honest conversation about cuts.

---

## Appendix B — Watch-outs for the whole session

- **Do not facilitate from the front during Block 2.** The session belongs to the tables once you have handed out the scenario. Front-of-room facilitation in Block 2 produces front-of-room roadmaps.
- **Track time on a visible clock.** Build time is the load-bearing variable. Everything else can flex.
- **Reward honesty.** Teams that say "we got this wrong" during their presentation are the ones who learned the most. Make that visible.
- **Mark your assumptions.** Anything in this kit marked [Inference] or [Unverified] should be checked before you say it on stage. Update the kit when you find a better answer.

---

## Appendix C — 2-hour variant

For 120 minutes, expand the build phase and the presentations. Suggested split:

| Block | Title | Time | Cumulative |
| --- | --- | --- | --- |
| 1 | Intro & theory | 0:00–0:20 | 0:20 |
| 2 | Scenario build | 0:20–0:55 | 0:55 |
| 3 | Distractors round 1 | 0:55–1:15 | 1:15 |
| 4 | Final distractor | 1:15–1:30 | 1:30 |
| 5 | Team presentations | 1:30–1:55 | 1:55 |
| 6 | Close & harvest | 1:55–2:00 | 2:00 |

Use the extra time in Block 5 to score teams against the full rubric out loud — the public scoring is the strongest teaching moment in the longer format.

---

## Appendix D — What to bring home

After the session, send participants:

- A link to this repository.
- A note inviting issues and pull requests with their own distractors (see Beat 6.2).
- The four example SVGs as standalone files (in `/examples`).

If you adapted the kit, fork it. If you improved it, open a pull request — that is the whole point.
