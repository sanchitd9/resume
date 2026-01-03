**Resume (LaTeX)**

A single page resume template written in LaTeX using a small custom class.

**Files**
- **Source:** [resume.tex](resume.tex) - main LaTeX source.
- **Class:** [resume.cls](resume.cls) - layout/class definitions.

**Build**
- **Requirements:** TeX Live (pdflatex) or `latexmk`.

- **Build with latexmk (recommended):**
```bash
latexmk -pdf resume.tex
```

**Edit**
- **Update content:** Edit [resume.tex](resume.tex) to change text, contact info, or sections.
- Change the name and contact lines in [resume.tex](resume.tex).
- Edit or reorder sections and bullet points inside [resume.tex](resume.tex).
- Tweak styling (fonts, spacing) in [resume.cls](resume.cls) if you need different layout.

**License / Credits**
- The `resume.cls` is based on a LaTeXTemplates.com class; preserve the original header and copyright notice when distributing.