# Academic CV Source-to-Output Checklist

Primary source reviewed in full: `prism-uploads/Currículo Lattes.pdf` (3 pages; Lattes update dated August 5, 2026).

Supplementary sources reviewed: 33 direct Google Drive documents and four official Alura certificates listed in `SUPPORTING_DOCUMENTS.md`, candidate-supplied Springer publication metadata and DOI/chapter URL, the candidate-supplied Google Scholar profile URL, GitHub profile and selected repositories, official publication/event pages, and candidate-supplied REFOP and freelance-work information. Direct Google Drive URLs for both BRACIS certificates are included.

## Template and build

- Custom one-column academic CV based on the standard LaTeX `article` class.
- Main packages: `geometry`, `lmodern`, `microtype`, `xcolor`, `graphicx`, `tabularx`, `array`, `enumitem`, `titlesec`, `needspace`, `fancyhdr`, `lastpage`, and `hyperref`.
- Photograph included from `prism-uploads/3x4.pdf` using a relative path.
- Compile with `latexmk -pdf main.tex` or standard pdfLaTeX on Overleaf.
- Evidence links use compact labels such as **[Transcript]**, **[Certificate]**, **[Proof]**, and **[Declaration]**; profile and official-source links remain descriptive text links.
- General Supporting Documents folder appears once, under Academic Profiles, rather than in the header.
- Final checked output: 4 pages, 76 hyperlink annotations, 51 unique destinations, and no overfull/underfull box warnings; the BRACIS `[Proof]` link opens the Springer chapter and both event certificate links are active.

## Lattes coverage audit

- Identification retained: name, academic location, institutional and secondary email addresses, ORCID, Lattes ID, GitHub, and LinkedIn.
- Education: M.Sc. in Computer Science (2025–present), including research title, advisor, CAPES scholarship, workload/dedication, research areas, CSILab affiliation, transcript, and enrollment declaration.
- Education: B.Sc. in Physics (2019–2025), including thesis title, advisor, CNPq scholarship context, diploma, and transcript.
- Education: secondary education at Colégio Batista de Guarulhos (2016–2018), completed in 2018, with its academic transcript linked.
- Research: temporal-mobility epidemiological modeling (2022–2024, CNPq, 20 hours/week).
- Research: TimesFM river-level forecasting (2024–2025, CNPq, 20 hours/week).
- Research: master's work on spatio-temporal graph neural networks (2025–present, CAPES, 40 hours/week, exclusive dedication).
- Publications: both full conference papers and the extended abstract/proceedings publication are included with precise status and official links where available. BRACIS 2026 is cited as a 2027 Springer LNCS publication (vol. 17106, pp. 19–33; first online October 2, 2026); its `[Proof]` hyperlink opens the official Springer chapter page.
- Teaching: BCC701 — Computer Programming I internship (2025–2026, 4 hours/week).
- Academic service: BRACIS 2026 TPC/reviewer; ENIAC 2026 TPC/reviewer; undergraduate thesis examination committee.
- Presentations and events: all entries from the Lattes presentation and event sections are represented; ENREDANDO and BRACIS 2026 are also included. BRACIS presentation and participation certificates have separate direct Google Drive links.
- Additional academic training: II School on Modelling Infectious Disease Dynamics (2025, 40 hours); GeoPandas course (2023, 6 hours); Introduction to Machine Learning Applied to Physics (2023 tutorial, 3 hours); Python for Data Science training program (2022, 86 hours); Web Scraping with Python course (2022, 10 hours); and Statistics with Python training program (2022, 71 hours).
- Research interests include Graph Neural Networks, Spatio-Temporal Graph Learning, Time-Series Forecasting, Network Science and Complex Networks, Graph Spectral Analysis, Scientific Machine Learning, and Computational Physics.
- Selected M.Sc. coursework is listed under Education: Algorithms, Data Mining, Neural Networks and Deep Learning, Complex Networks, and Digital Image Processing.
- Skills represented in the CV: Python, Snakemake, C, C++, Bash, PyTorch, PyTorch Geometric, PyTorch Geometric Temporal, Scikit-learn, NumPy, SciPy, Pandas, Matplotlib, Jupyter, Python multiprocessing, statistical data analysis, web scraping, GeoPandas, Shapely, OSMnx, Git, Linux, Docker, Slurm, LaTeX, Markdown, and VS Code.
- Languages: Portuguese — Native; English — EF SET 76/100, C2 Proficient, with Reading 80 and Listening 71, awarded February 17, 2025.
- Bibliographic citation name: COSTA, G. F.

## Additional candidate-supplied content

- Leadership/institutional activity: Communication Board Advisor at REFOP, August 1, 2019–August 1, 2020 (20 hours) and August 1, 2021–August 1, 2022 (100 hours).
- Professional experience: freelance waiter at Seu José, Tenente Pimenta, and Recanto Serra do Trovão; no dates added.
- Public research software: three selected GitHub repositories relevant to graph learning, temporal mobility networks, and complex networks.

## Evidence-link audit

- All 33 Google Drive supporting documents, four official Alura certificates, and the two BRACIS certificate items are identified and linked in `SUPPORTING_DOCUMENTS.md`.
- Priority evidence is linked directly in the CV for education, research, publications, teaching, academic service, English proficiency, events/training, and REFOP.
- BRACIS registration and acceptance documentation remain in the evidence inventory; the CV links directly to the official Springer publication as `[Proof]` and retains the manuscript link as `[Paper]`.
- Official public links are preferred for GEOINFO, CNMAC/SBMAC, BRACIS, and ENREDANDO; Drive links are supplementary evidence.
- No raw URL is displayed in the CV body.

## Items intentionally excluded

- Date/place of birth, residential address, telephone numbers, parents' names, civil status, CPF, RG, and other nonessential personal data.
- Lattes system disclaimer and generation metadata.
- Duplicate Lattes totals where the underlying records are already itemized.
- A documentary link for freelance waiter experience, because no evidence document was supplied.

## Information still missing or awaiting confirmation

- Dates or date range for freelance waiter work, if the candidate wants them displayed.
- Explicit confirmation of the supervisors for each CNPq undergraduate research appointment; the professional-activity records do not name them separately.
- Optional DOI/canonical landing page for the GEOINFO 2025 paper, if one becomes available beyond the official INPE PDF.

## Status and date consistency

- Lattes CV last updated: August 5, 2026.
- CV update date: October 27, 2026.
- BRACIS paper status: published in Springer LNCS as a 2027 bibliographic item; first published online October 2, 2026. Conference name remains BRACIS 2026; conference dates are October 19–22, 2026.
- CNMAC contribution: presented in 2024; official SBMAC issue published January 20, 2025. Both dates are preserved.
- ENREDANDO: presentation and participation documented for July 26–31, 2026, in Viçosa, Brazil.
- BRACIS 2026: oral presentation in Cuiabá, Mato Grosso, Brazil, October 19–22, 2026; participation recorded as 40 hours per candidate-provided information.
- Brazilian Physics Society Autumn Meeting: presentation documented for May 21–25, 2023, in Ouro Preto, in the session Complex Networks, Econophysics and Sociophysics II.
- Undergraduate thesis committee: official BCC393 declaration documents the defense on July 27, 2026.
- No dates were invented for freelance work or unspecified appointments.

## Final visual and technical checks

- Names, titles, institutions, advisors, dates, and publication status checked against available sources.
- Photo remains small and discreet in the header.
- Page breaks, alignment, spacing, and footer pagination visually inspected on all four pages.
- Hyperlinks checked as active PDF annotations.
- No LaTeX overfull/underfull box warnings in the final build.