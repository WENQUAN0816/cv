# Academic CV for Malaysian University Applications

This repository contains a LaTeX academic CV tailored for lecturer applications in Malaysia.

Template basis:

- Selected from the GitHub [`ndpvt-web/latex-document-skill`](https://github.com/ndpvt-web/latex-document-skill) template catalogue, whose academic CV direction supports multi-page academic CV content such as publications, grants/funding, teaching, awards, professional service, ORCID, and Google Scholar links.
- The final `cv.tex` here is customized for Malaysian university lecturer applications: WoS/Scopus publication grouping, PI-led project emphasis, teaching portfolio, and an information-to-confirm section.

Build:

```powershell
xelatex -interaction=nonstopmode cv.tex
xelatex -interaction=nonstopmode cv.tex
```

Output:

- `cv.pdf`

Information still worth confirming before formal submission:

- Expected PhD completion date, if required by the application system.
- Google Scholar profile, Scopus Author ID, Web of Science ResearcherID.
- Available start date.
- Studio/project supervision, assessment responsibilities, and student mentoring outcomes.
