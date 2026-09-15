# CS deck assets

Build artifacts for Milton Middle School CS, hosted on GitHub Pages at
<https://bsitkoff.github.io/cs-deck-assets/>. Nothing here is edited by hand —
regenerate it from the source repo instead.

| Folder | What | Source |
|---|---|---|
| `g6-u*-scratch-*` | Pre-rendered Scratch block SVGs for the Grade 6 slide decks, so Gamma can fetch them at generation time | `tools/render_scratch_svg.py` |
| `attendance-questions` | Attendance warm-up question slides | `curriculum-setup-2627` |
| `guided-notes` | Printable one-page guided-notes sheets, one per video, plus an index at [`guided-notes/`](https://bsitkoff.github.io/cs-deck-assets/guided-notes/) | `tools/render_handout_pdf.py` in `curriculum-setup-2627` |

**These are student-facing and public.** Guided-notes sheets are blank fill-in
pages: no answer keys, no teacher notes. Keep it that way — anything with
answers or teacher material belongs in the private curriculum repo, not here.
