# Instructor Companion Guide

A practical guide for faculty using or adapting *Two Ways to Change a System* in an asynchronous online graduate course on integrative health, program planning, or implementation science.

This guide is part of an open educational resource. See [`README.md`](README.md) for tool overview, theoretical foundations, and licensing.

---

## What the tool is — and isn't

**It is** a metacognitive scaffold that asks students the questions two contrasting frameworks would ask, anchored to their own evidence-informed project, with a companion diagnostic for projects that stalled.

**It isn't** a graded assessment, a substitute for the source papers, or a step-by-step prescription. Students do the thinking; the tool structures the space.

## Learning outcomes it supports

The tool maps cleanly to these graduate-level outcomes. Adapt to your program's language:

- Apply a theory-based intervention design framework (Intervention Mapping) to a problem of practice.
- Analyze the institutional context — free space, field status, jurisdictions, allies — relevant to advancing integrative-health innovation.
- Synthesize across two distinct theoretical lenses to inform a project plan.
- Diagnose the institutional and evidentiary conditions under which a past project succeeded or failed.
- Articulate the evidence base behind a proposed project and identify remaining gaps.

## Where it fits in a course

The tool sits well mid-to-late in a course on integrative-health program planning, implementation science, organizational change, or evidence-based practice. Recommended pre-requisites:

- Students have read or are concurrently reading the source papers (Fernandez et al., 2019; Heinze & Weber, 2016; optionally Reay et al., 2017).
- Students have a working project idea — real or hypothetical.
- Some prior exposure to logic models and behavior-change theory is helpful but not required (the framework primers fill the gap).

Time investment: ~60–90 minutes per lens on first pass. Students should expect to return across the term as their project evolves.

## Four assignment patterns

### Pattern 1 — Pre-class scaffold

Assign the source papers plus one lens (Blueprint, Build, or both depending on the week's focus). Students bring their downloaded `.txt` export to the synchronous session or post it to a discussion board before class.

- **Grading approach:** completion plus a one-paragraph reflection on what was unclear or surprising.
- **What it gives you:** a shared starting point that surfaces where students are stuck before you teach into it.

### Pattern 2 — Comparative reflection

Students complete both lenses on the same project, then write a 500–750 word reflection on where the two views agreed, where they pushed against each other, and what that tension means for the project.

- **Suggested rubric criteria:** substantive engagement with both frameworks; specificity of the project examples; honest treatment of disagreement between the lenses; integration into a next step.
- **What it gives you:** a piece of writing that demonstrates synthesis across frameworks, which is harder to fake than completion of either lens alone.

### Pattern 3 — Diagnostic case study

Use *Why it Stalled* on a published case study (or a project a colleague is willing to share). In pairs or small groups, students compare diagnoses and ask: what would each of the two ways have done differently from the start?

- **What it gives you:** historical reasoning skills, plus a low-stakes context in which to practice the diagnostic before students apply it to their own work.

### Pattern 4 — Longitudinal artifact

Students return to the tool across the term — say, at weeks 4, 8, and 14. They export at each timepoint and write a short reflection on how their thinking has evolved.

- **Grading approach:** track the evolution of thinking, depth of self-check engagement, and integration of new evidence.
- **What it gives you:** a record of growth that's much richer than a single end-of-term paper.

## Discussion questions for sync or async sessions

Use any of these after students have spent time in the lenses:

- What did the Blueprint reveal about your project that the Build couldn't have? What did the Build reveal that the Blueprint couldn't?
- Where in your project does the evidence already support your reasoning, and where are you reasoning ahead of the evidence?
- Who in your institution would resist this project — and which lens better predicted who and why?
- What is the smallest visible action you could take in the next week, given everything both lenses surfaced?
- If your project stalled three years from now, which lens would have predicted it?

## Debriefing prompts

When students have completed both lenses, the metacognitive layer is where the learning consolidates. Ask:

- What was *easy* in one lens that was *hard* in the other? What does that tell you?
- Did the lenses agree on what mattered most? Where did they disagree, and why?
- What did you notice about your own thinking as you moved between them?

## Common student stumbling points

**"I don't know which lens is right for my project."** Both probably are. The lenses encode different stances toward how institutions change, not different kinds of projects. Encourage time in *both* for any non-trivial work.

**"I want the tool to give me the answer."** That's the design. The tool asks the questions; the thinking belongs to the student. If a prompt feels impossible, it's usually pointing at exactly where to spend time.

**"The Blueprint feels too academic; the Build feels too political."** Both observations are accurate. The lenses encode different assumptions about how change happens. The tension between them is part of the learning.

**"I'm intimidated by the empty box."** Direct students to the optional sentence stems on the first prompt of each lens. Use the starters, then edit freely.

**"I don't have enough evidence yet."** That's fine. The tool acknowledges it. Have students select "Still seeking" in the evidence base section — the lenses then surface what evidence they need to find next.

## Assessment strategies

The tool deliberately doesn't grade. Suggestions for assessing student engagement with it:

- A rubric for the reflection paper (see sample below).
- Peer review of exported text in small groups.
- A brief oral defense (5–7 minutes) of one lens to the instructor or in office hours.
- A portfolio piece that evolves across the term.

### Sample 4-criterion rubric for the comparative reflection

| Criterion | Below expectations | Meets expectations | Exceeds expectations |
|---|---|---|---|
| **Framework fidelity** | Conflates or misuses key terms (e.g., method vs. application; free space vs. resources) | Uses framework vocabulary accurately, with reasonable distinctions | Uses framework vocabulary precisely and notices where the source papers are themselves contested |
| **Project specificity** | Project described in generalities | Project described with concrete actors, settings, resources | Project specificity supports a tight argument; non-obvious details surface |
| **Engagement with tension** | Treats the two lenses as interchangeable | Names where the lenses agreed and where they diverged | Engages the tension productively — uses it to refine the project |
| **Evidence anchoring** | Evidence base not addressed or vaguely referenced | Identifies what evidence supports the project and what remains open | Cites specific sources; identifies the next evidence move with clarity |

## Adapting for your own context

The tool is one self-contained HTML file with no external dependencies beyond Google Fonts. To adapt for your domain:

- **Swap the source papers and lens prompts** for frameworks in your field. The pedagogical pattern (primer + prompts + self-checks + stems) generalizes.
- **Change the lens accent colors** in the CSS root variables (`--blueprint`, `--build`, `--stall`).
- **Add or remove prompts** — each is its own `<article class="prompt">` block.
- **Adjust the evidence base prompt** to match your course's research methods language.

Forks and pull requests welcome under CC BY 4.0.

## FAQ

**Will my students' work be sent anywhere?** No. All work autosaves only to the student's browser localStorage. Nothing leaves the device unless the student downloads or copies it.

**What if a student clears browser cache?** They lose their work. Tell students at intake to download or copy at the end of each session.

**Can students use this on phones?** Yes. The layout is responsive. Sentence stems work especially well on small screens for quick capture between shifts.

**Can I host it on Canvas or another LMS?** Yes. The HTML is self-contained. Embed it as a webpage, or upload as a file students can open in-browser.

**Can I add my own self-check rubric items?** Yes — each prompt's self-check is an HTML list inside `<ul class="self-check-items">`. Add or remove items as your course requires.

**How long does it take students to complete?** Plan on 45–90 minutes per lens at first pass. Students who use the sentence stems and engage the self-checks tend toward the longer end and learn more.

---

*This guide is licensed under CC BY 4.0 along with the rest of the resource. Designed in collaboration with Claude Opus 4.7 cowork (2026).*
