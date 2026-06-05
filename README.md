# Academic CV for Malaysian University Applications

This repository contains academic job application materials tailored for lecturer applications in Malaysia.

Template basis:

- Selected from the GitHub [`ndpvt-web/latex-document-skill`](https://github.com/ndpvt-web/latex-document-skill) template catalogue, whose academic CV direction supports multi-page academic CV content such as publications, grants/funding, teaching, awards, professional service, ORCID, and Google Scholar links.
- The final `cv.tex` here is customized for Malaysian university lecturer applications: WoS/Scopus publication grouping, PI-led project emphasis, teaching portfolio, and an information-to-confirm section.

Build:

```powershell
xelatex -interaction=nonstopmode cv.tex
xelatex -interaction=nonstopmode cv.tex
xelatex -interaction=nonstopmode short_cv.tex
xelatex -interaction=nonstopmode research_statement.tex
xelatex -interaction=nonstopmode teaching_statement.tex
xelatex -interaction=nonstopmode representative_publications_links.tex
```

Output:

- `cv.pdf` — full academic CV
- `short_cv.pdf` — two-page short CV / resume
- `research_statement.pdf` — research statement on AI-assisted age-friendly environment assessment
- `teaching_statement.pdf` — teaching statement for interior design / built environment lecturer applications
- `representative_publications_links.pdf` — one-page DOI-linked list of five representative publications
- `representative-publications/` — five selected representative publications, with DOI links and bundled open-access PDF where automated download succeeded

Information still worth confirming before formal submission:

- Expected PhD completion date, if required by the application system.
- Google Scholar profile, Scopus Author ID, Web of Science ResearcherID.
- Available start date.
- Studio/project supervision, assessment responsibilities, and student mentoring outcomes.
