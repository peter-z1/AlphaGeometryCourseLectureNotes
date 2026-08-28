# Euclidean Geometry and AI

Lecture notes by Steven Creech and Peter Zenz for a Fall 2025 special-topics
course at Brown University on Euclidean geometry, automated reasoning, and
artificial intelligence.

**[Read the compiled lecture notes](lecture_notes.pdf)** ·
[LaTeX source](lecture_notes.tex)

## Repository contents

- `lecture_notes.tex` and `lecture_notes.pdf`: the source and compiled notes;
- `Homework1.tex` through `Homework10.tex`: the standalone assignment
  handouts;
- `Ref.bib`: the bibliography; and
- `figures/`: figures used by the notes.

The solver, synthetic-data pipeline, language model, datasets, checkpoints,
and tests discussed in the notes belong to a separate course-code project and
are not distributed in this lecture-notes repository. Part III uses
[AlphaGeometryRE](https://github.com/foldl/AlphaGeometryRE) as its public
reference implementation.

## Building the notes

Install a current LaTeX distribution with `latexmk`, then run:

```powershell
latexmk -g -pdf -interaction=nonstopmode -halt-on-error lecture_notes.tex
```

The build uses BibTeX and reads `Ref.bib` automatically.

## Funding acknowledgment

These notes grew out of a course offered with support from the project
*AIMing: Building Automated Reasoning System for Hyperbolic Geometry and
Beyond*.

This material is based upon work supported by the U.S. National Science
Foundation under award No. 2522850. Any opinions, findings, and conclusions or
recommendations expressed in this material are those of the authors and do
not necessarily reflect the views of the U.S. National Science Foundation.

## License and attribution

Except for identified third-party material, the authors' original course
material is available under the
[Creative Commons Attribution 4.0 International License](LICENSE.md).
The NSF logo, upstream software excerpts, and externally authored problem
material are excluded from that license. See
[THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md) for details.

A suggested citation is:

> Steven Creech and Peter Zenz, *Euclidean Geometry and AI*, 2025–2026,
> <https://github.com/peter-z1/AlphaGeometryCourseLectureNotes>.
