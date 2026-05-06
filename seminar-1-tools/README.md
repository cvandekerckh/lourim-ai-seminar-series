# Seminar 1 — Tools for AI-assisted research

## What this seminar covers

A two-part session introducing AI tools that support the research workflow, from finding the literature to producing a paper draft and a slide deck.

- **Theoretical part (slides).** Overview of the landscape of AI research tools, the risks of using them (hallucinations, bias, confidentiality, traceability, integrity, responsibility), and a live demo of the main ones.
- **Practical part (handout).** A 45-minute hands-on workshop where each participant takes a randomly assigned research topic and pushes it through a seven-tool pipeline: Research Rabbit → Elicit → NotebookLM → ChatGPT Deep Research → Jenni AI → Paperpal → Gamma. The result, finished as homework, is a short paper draft and a slide deck emailed to a researcher in the field.

## Materials

- [`slides/`](slides/) — `Session 1 - AI Tools for Research.pdf` (read-only) and `.key` (editable in Keynote).
- [`practical/`](practical/) — `tutorial.pdf` (the handout) and `tutorial.tex` (the LaTeX source).

## How to use them as a participant

1. Read `slides/Session 1 - AI Tools for Research.pdf` before the practical, or use it as a reminder afterwards.
2. During the practical, follow `practical/tutorial.pdf`. Bring a laptop, your assigned topic, and accounts for the seven tools listed in the handout's appendix.
3. Finish the rest of the pipeline at home and email your draft + slides to the researcher you identify in the literature.

## Rebuilding the practical PDF

```bash
cd practical
pdflatex tutorial.tex && pdflatex tutorial.tex
```
