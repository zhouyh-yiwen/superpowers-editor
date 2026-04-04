---
name: requesting-review
description: Use when a proposal plan, writing brief, or other editorial work product is ready for critique and you want an independent AI review before sharing or revising it.
---

# Requesting Review

Use this skill when a draft artifact already exists and should be reviewed by a separate AI pass before you continue. The goal is to ask for review with clear scope, not to defend the work or patch it immediately.

**Announce at start:** "I'm using the requesting-review skill to prepare an independent review pass."

## Use This For

- Sending a proposal plan for critique before a topic meeting
- Sending a writing brief for challenge before drafting
- Stress-testing an angle, argument, or structure against likely objections
- Getting a clean second-pass review without mixing in your own reasoning

## Do Not Use This For

- Revising feedback that has already arrived
- Brainstorming a new angle from scratch
- Producing a final artifact without critique

If feedback already exists, use `receiving-review`.

## Core Rules

- Review scope must be explicit.
- The reviewer should see the work product and the goal, not your full chain of thought.
- Ask for critique from relevant perspectives, not generic praise.
- Prefer short, decision-oriented review points over essay-length analysis.
- Prefer multiple role-based feedback items, similar to a real circulation-for-comment process.
- Do not pre-answer objections before the review has happened.
- Prioritize content questions first: title, reader, selling point, distinctness, focus, and spreadability.
- Only include operational lenses like pricing or print run when the user explicitly asks for them.

## Process

1. **Name the artifact**
   State what is being reviewed:
   - proposal plan
   - proposal report draft
   - writing brief
   - recommendation angle package

2. **State the goal**
   Clarify what the artifact is trying to achieve:
   - internal approval
   - topic-meeting readiness
   - clearer reader route
   - stronger evidence
   - fewer weak points

3. **Choose review lenses**
   Pick only the lenses that matter. Common lenses:
   - editorial logic
   - audience fit
   - sales / market objection
   - marketing / spreadability
   - channel or launch practicality
   - title strength
   - comparables / market proof
   - clarity / repetition / missing proof
   - focus / over-breadth risk

4. **Prepare the review request**
   Ask the reviewing AI to:
   - act like several reviewing colleagues rather than one merged voice
   - return short, separate comments from distinct perspectives
   - focus on title, reader fit, selling point clarity, distinctness, topic sharpness, marketing route, and evidence gaps
   - point to missing proof, weak logic, or confused audience positioning
   - suggest what needs revision, not just what feels off

5. **Hand off cleanly**
   End with a compact review request another AI can answer directly.

## Output Format

### Artifact
- what is being reviewed

### Goal
- what the artifact needs to accomplish

### Review Lenses
- the perspectives the reviewer should use

### Material To Review
- the actual artifact or the exact portion under review

### What The Reviewer Should Return
- 3-6 short feedback items
- each item with a role or lens
- concrete concern or support point
- revision implication if applicable

### Preferred Review Shape
Use a circulation-for-comment style:
- `Feedback 1 (sales): ...`
- `Feedback 2 (marketing): ...`
- `Feedback 3 (editorial): ...`
- `Feedback 4 (channel): ...`

## Quality Bar

Good review requests:
- are specific about the artifact and its purpose
- ask for critique from named perspectives
- make the reviewer examine title, audience fit, selling point clarity, focus, marketing route, and missing proof
- encourage short independent comments rather than one blended review memo
- are short enough for another AI to act on immediately

Bad review requests:
- ask only for "feedback"
- hide the real decision the artifact must support
- invite generic praise
- bundle too many unrelated artifacts into one request
