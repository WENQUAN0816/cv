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

- PhD completion status and exact award date.
- Google Scholar profile, Scopus Author ID, Web of Science ResearcherID.
- Current employment status after 2023 and available start date.
- Courses taught with years, level, class size, and language of instruction.
- Supervision/mentoring record.
- Two or three academic referees with institutional emails.
