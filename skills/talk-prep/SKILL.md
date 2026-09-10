---
name: talk-prep
description: >
  Prepare a short talk or presentation that fits its time slot and lands one
  idea: find the red thread (main idea ≠ topic), budget the time (plan for 80 %
  of the slot, ~150 spoken words per minute, intro 20 % / core 70 % / close 10 %),
  build a 30-second opening and a closing that adds nothing new, cut slides
  until less is more, and rehearse answers to objections. Use when the user
  asks for a talk, a lightning talk, a 5-minute pitch, speaker notes, a talk
  track, "what should I say", timing help, or feedback on a presentation
  outline. Pairs with html-slide-deck (the slides) and meme-assets (the humour).
---

# Talk prep

A talk is a **contract with the audience**: you promised one idea in N minutes.
Everything in this skill exists to keep that contract. Slides are a visual aid,
not the talk — you are the best visual aid you have.

## Workflow

1. **Red thread first.** Before any slide, write the main idea in one or two
   sentences. Test it with the four questions below. If it fails, you have a
   topic, not an idea — keep working.
2. **Budget the time.** Plan content for **80 % of the slot** (5 min slot →
   4 min of speech ≈ 600 words). Split it intro 20 % / core 70 % / close 10 %.
3. **Outline the core** as 3–4 beats that each carry the red thread forward.
   One beat = one slide = one thing to remember. Cut anything that doesn't
   move the thread.
4. **Write the opening** (first 30 seconds) and **the close** (last 10 %)
   verbatim. The middle can be bullet-level notes; the edges must be exact.
5. **Write the talk track** — spoken text with timestamps and the word count
   per beat. Save it next to the slides (`sources/talk-track.md` or similar).
6. **Prepare objections.** List the 5–7 pushbacks you expect and one
   reformulating reply for each (see `references/objections.md`).
7. **Rehearse with the visual aids you will actually use**, time it, cut until
   it lands under 80 %. Then cut once more.

## The red thread

- **Topic ≠ main idea.** "Our new data server" is a topic. "You can get an
  answer about a customer in one question instead of five admin tools" is an idea.
- It builds the skeleton (intro → core → close), keeps the logical order, and
  gives the talk its emotional charge.
- Four tests: *Can I say it in one or two sentences? Is it new to this audience?
  Is it interesting to them (not to me)? Is it factual and realistic?*
- Strong threads are single-value words made concrete: simplicity, safety,
  speed, independence, trust, change, results, freedom, quality…
- Weak: "I'd like to share a few experiences from my trip and some thoughts
  on travel." Strong: "On that trip I learned when you can trust strangers and
  when you definitely can't — here are two very different cases."

## Timing rules

| Rule | Number |
|---|---|
| Plan content for | **80 %** of the allocated time |
| Average speaking pace | **~150 words / minute** — fewer is better |
| Intro / core / close | **20 % / 70 % / 10 %** |
| First impression | formed in **~30 seconds** |

Overfilled talk = under-explained content. It is *information management*:
quality over quantity. If you had more time, you would write a shorter talk
(Pascal: "I would have written a shorter letter").

Word budgets that work: 3 min → ~360 words · 5 min → ~600 · 10 min → ~1 200 ·
20 min → ~2 400. Count them in the talk track.

## Opening (20 %)

- Make contact with the room first; you have 30 seconds for the first impression.
- Hooks that work: a personal story, a quote, a surprising fact, a question you
  *don't* answer yet, a statistic. **Careful with jokes** — a joke that misses
  costs more than a hook that is merely fine.
- Connect the hook to the red thread within the first minute.
- Say what the goal is, why *they* should listen, and how the talk is structured
  (including when you will take questions).

## Core (70 %)

- One beat per slide. 3–5 short bullets per slide, or better: one sentence
  and one picture.
- Argue on all three of Aristotle's channels: **ethos** (why trust you — real
  numbers, real production, your role), **pathos** (a story with a person and a
  consequence), **logos** (the mechanism, the cause and effect). A talk that is
  all logos is a spec sheet; all pathos is a sermon.
- Storytelling = framing the idea as a story that informs, teaches or inspires.
  A story has a person, a problem, a turn, and a result. Use a real one.
- Real data or no data. Every number has a source and a date.

## Close (10 %)

- Summarize in one breath, tie back to the red thread, then end with a clear
  recommendation, a challenge, a personal example or a quotation.
- **After the summary, add nothing new.** No "one more thing", no extra slide.
- Thank the audience and stop. Silence after the last sentence is fine.

## Visual aids — less is more

- You are the best visual aid. Slides support, they don't compete.
- One visual aid at a time. Never read a slide aloud.
- Minimize noise: one typeface, few sizes, few colours, aligned edges,
  consistent spacing. Photos over clip art (Unsplash is fine), tables only when
  a number matters and is highlighted, animation only when it shows change.
- Rehearse *with* the aids. A demo with no fallback is not a demo.
- Humour: a real meme (see the `meme-assets` skill) beats a joke you have to
  tell. Two or three per five minutes is plenty.

## Delivery

- Non-verbal channel dominates: body language and voice carry most of the
  impression, words the least. Mindset first — you believe it, they will.
- Body synchronised with words: posture, gestures, facial expression, eye
  contact, breath.
- Voice parameters to vary deliberately: pitch, volume, **tempo (slow with
  pauses beats fast without)**, colour, articulation.
- Pause after the important sentence. The pause is where the audience thinks.

## Audience and objections

- Know the audience: why should *they* listen? Expect the unexpected.
- Agree upfront when questions come (during / at the end).
- Classify each question: logical or emotional? Answer the kind that was asked.
- Only the motivated can motivate — if you are not sold, they won't be.
- Objection protocol: listen actively → appreciate the question → check you
  understood it → **reformulate it positively** → hand it back with an open
  *How…?* / *What…?* question. Avoid *Why…?* — it sounds like an accusation.

## Deliverables

For a talk request, produce:

1. **Red thread** — one or two sentences at the top of the talk track.
2. **Talk track** — timestamped spoken text with word counts, in the user's
   language, saved as Markdown next to the deck.
3. **Slides** (if asked) — via `html-slide-deck`; one beat per slide, speaker
   notes as HTML comments, memes via `meme-assets` if humour is wanted.
4. **Objection sheet** — expected pushbacks with prepared replies.
5. **Rehearsal checklist** — `references/checklist.md`.

## Anti-patterns

- Writing slides before the red thread exists.
- Filling 100 % of the slot. You will run over; everyone always does.
- New information after the summary.
- Reading bullets aloud; slides that are the script.
- Answering the objection you *wish* they had asked.
- Jokes as hooks; memes with English text you cannot rewrite.
