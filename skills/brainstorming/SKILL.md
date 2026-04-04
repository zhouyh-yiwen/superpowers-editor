---
name: brainstorming
description: Use when shaping a publishing idea, exploring audience fit, comparing editorial angles, or finding the best hook before drafting a pitch, campaign, or recommendation.
---

# Brainstorming Editorial Angles

Use this skill whenever the work is still fuzzy and needs judgment before writing. The goal is not to produce finished copy. The goal is to identify the strongest angle, audience, and promise.

**Announce at start:** "I'm using the brainstorming skill to explore the strongest angle before writing."

## Use This For

- Deciding what a book is really about
- Clarifying who the most promising readers are
- Comparing 3-5 possible selling points or recommendation angles
- Finding the best cut for a post, launch note, recommendation, or discussion outline
- Stress-testing whether an idea is specific, honest, and interesting enough

## Do Not Use This For

- Writing the final proposal report
- Drafting the final post in one shot
- Inventing quotes, sales numbers, endorsements, or market proof
- Treating raw ingestion as the goal instead of using the material to make an editorial decision

If the direction is already clear and the task is to organize a report or work sequence, use `proposal-planning`.
If the angle is chosen and the next step is to prepare a reader-facing writing route, use `copywriting-brief`.

## Core Rules

- Scope first. If the request bundles several independent editorial decisions, separate them before going deeper.
- One key decision at a time.
- Audience first. Identify who should care before shaping the message.
- Purpose first. Be clear whether the output is for internal judgment, reader interest, recommendation, or launch conversation.
- Angle first. Generate multiple candidate angles before choosing one.
- Clarity over cleverness.
- Specificity over vagueness.
- Honesty beats hype.
- Do not sound like generic AI marketing copy.
- Full-book material is allowed. EPUB, TOC, sample chapters, summaries, proposal notes, and excerpts are all valid inputs.
- Reading the source is not a separate skill. Use the source material only to support a real editorial decision.
- When the input is a full book or large manuscript, extract candidate angles and supporting materials before recommending a direction.

Read `content-angle-style.md` before presenting final angles.  
Use `angle-reviewer.md` as a self-review checklist before recommending a direction.

## Process

1. **Read the material**
   Review the manuscript summary, catalog copy, table of contents, sample chapter, full manuscript, EPUB, or any notes the user already has.

   If the input is a full book or EPUB:
   - scan the structure first
   - identify recurring themes, tensions, stories, scenes, or arguments
   - collect concrete materials that could support different editorial angles
   - do not summarize the whole book unless that is the task

2. **Check scope before refining**
   If the request really contains several different jobs, stop and separate them first.

   Examples:
   - proposal logic
   - title direction
   - reader-facing angle
   - launch messaging

   If needed, state which decision should be solved first and leave the others for later.

3. **Define the decision**
   Clarify what needs to be decided now:
   - book positioning
   - target reader
   - value proposition
   - recommendation angle
   - post angle

   Do not try to settle several of these at once. Pick the most immediate one and work on that first.

4. **Find the audience tension**
   Ask focused questions or infer from the material:
   - Who is most likely to care?
   - What problem, curiosity, fear, aspiration, or identity does this connect to?
   - Why would that person pay attention now?

5. **Generate candidate angles**
   Produce 3-5 distinct angles. Each one must include:
   - one-sentence angle
   - target reader
   - what makes it compelling
   - what kind of emotional or intellectual pull it uses
   - what risk or weakness it has
   - which book materials could support it

6. **Compare and recommend**
   Compare the candidate angles, then recommend one primary angle and one backup angle.

7. **Hand off cleanly**
   End with a concise package the next step can use:
   - recommended primary angle
   - backup angle
   - intended reader
   - core promise
   - evidence or book material to lean on
   - open questions if any

8. **Let the user choose when useful**
   If 2-3 routes are genuinely viable, present the candidate angles and supporting materials in a way that lets the user choose.

   Do not force a recommendation-only answer when comparison is the real need.
   Do not silently lock a route if the real decision is still open.

## Control Flow

After brainstorming, choose the next step based on what the user needs:

- if they need an internal report or proposal structure → `proposal-planning`
- if they need a reader-facing writing route → `copywriting-brief`
- if they only needed the angle decision, stop after the recommendation

## Output Format

Use this structure unless the user asks for something else:

### Decision
- What is being decided

### Candidate Angles
- Angle 1: ...
- Angle 2: ...
- Angle 3: ...

### Supporting Materials
- which scenes, examples, claims, or details from the book support each angle

### Recommendation
- Primary angle
- Backup angle
- Why this is the strongest choice now

### Materials To Use
- specific chapter/theme/story/data point to rely on

### Open Questions
- only include if they materially affect the decision

## Quality Bar

Good outputs:
- identify the real decision being made
- make the audience visible
- connect the book to a real reader need or curiosity
- sound like an editor making a judgment
- stay grounded in the actual material
- surface multiple usable routes from the book, not just one abstract takeaway
- identify which concrete materials support which route

Bad outputs:
- try to solve positioning, title, audience, and campaign all at once
- repeat the content summary in prettier words
- produce interchangeable slogans
- confuse "interesting topic" with "effective angle"
- default to broad claims like "thought-provoking" or "highly relevant"
- read the whole book and still fail to extract usable hooks or materials
