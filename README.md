# LOURIM — AI for Research Seminar Series

Source materials for a four-part seminar series on using AI tools in academic research, run at the Louvain Research Institute in Management (LOURIM, UCLouvain).

## The four seminars

| # | Title | Materials |
|---|-------|-----------|
| 1 | **Tools for AI-assisted research** | [slides](seminar-1-tools/slides/) · [practical](seminar-1-tools/practical/) |
| 2 | **Responsible AI** | [seminar-2-responsible-ai/](seminar-2-responsible-ai/) |
| 3 | **Better prompting** | [seminar-3-better-prompting/](seminar-3-better-prompting/) |
| 4 | **Sustainable AI** | [seminar-4-sustainable-ai/](seminar-4-sustainable-ai/) |

## How materials are organised

Each `seminar-N-*/` folder contains:

- **`slides/`** — the theoretical talk. Both the editable Keynote source (`.key`) and a PDF export, so participants without macOS can still read the slides.
- **`practical/`** — the hands-on session. A LaTeX tutorial document (`.tex` source) plus the compiled `.pdf` handout.

## For participants

You only need the PDFs.

- Click into the seminar folder you want.
- Open `slides/*.pdf` for the talk and `practical/tutorial.pdf` for the practical handout.
- GitHub renders both PDFs in the browser, or you can download them.

You do not need to clone the repository or install LaTeX.

## For maintainers

### Rebuild the practical PDF

```bash
cd seminar-1-tools/practical
pdflatex tutorial.tex && pdflatex tutorial.tex
```

Two passes are needed so the table of contents and cross-references resolve.

### Re-export the slide deck

Open the `.key` file in Keynote, then *File → Export To → PDF*. Save next to the `.key` with the same base name.

### What the repo does **not** track

LaTeX intermediates (`.aux`, `.log`, `.out`, `.toc`, `.synctex.gz`) and macOS metadata (`.DS_Store`) are ignored — see [.gitignore](.gitignore).

## License

Materials are shared for educational use within the LOURIM seminar audience. If you want to reuse them elsewhere, please get in touch.
