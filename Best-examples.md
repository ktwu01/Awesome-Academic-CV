# Best-examples

Sacha http://sachaepskamp.com/

Alex https://alexchristensen.github.io/

Tyler https://www.ktylerwilcox.me/

Ross https://github.com/Rjacobucci/CV/blob/master/rj_cv.pdf

MJ https://drive.google.com/file/d/149eRAfH300P91Nd4hHjrEs9MhCNPmUdW/view

Donny https://donaldrwilliams.github.io/

Sam Trejo https://scholar.princeton.edu/sites/default/files/strejo/files/_trejo_cv.pdf


Latex CV template

https://www.overleaf.com/latex/templates/tagged/cv

# Best‑Examples: Polished CV Templates for Researchers

> **Purpose**
> Show concrete, copy‑pasteable templates that demonstrate best practices for academic, research and R\&D résumés.
> Use them as starting points, adapt them to your domain, and cross‑check with the accompanying **Checklist.md**.

---

## 📑 Table of Contents

1. [How to Use These Examples](#how-to-use)
2. [Style Conventions](#style-conventions)
3. [Example 1 – Early‑Stage PhD Student (1 page)](#ex1-phd-early)
4. [Example 2 – Senior PhD Candidate (2 pages)](#ex2-phd-senior)
5. [Example 3 – Postdoctoral Researcher (2 pages)](#ex3-postdoc)
6. [Example 4 – Industry R\&D Scientist (2 pages)](#ex4-industry)
7. [Example 5 – Data Scientist With Publications (1–2 pages)](#ex5-data)
8. [Example 6 – Fellowship/Grant CV (Structured 2 pages)](#ex6-fellowship)
9. [Citation & License](#citation)

---

## <a id="how-to-use"></a>1 | How to Use These Examples

* **Copy** the skeleton into your editor (LaTeX or Markdown).
* **Replace** bracketed placeholders (`[Your Name]`, `[Title]`, …).
* **Remove** comment markers `%%` once customised.
* **Run** every edited file through the automated linter in **Formatting‑Guidelines.md**.
* **Verify** with **Checklist.md** before submission.

---

## <a id="style-conventions"></a>2 | Style Conventions

| Feature         | Guideline                                                          |
| --------------- | ------------------------------------------------------------------ |
| Font            | 10–11 pt sans‑serif (Helvetica/Arial) or serif (Times) consistent. |
| Margins         | 0.6–0.75 inch (narrow but not cramped).                            |
| Section headers | ALL CAPS or Title Case, left‑aligned, bold.                        |
| Bullet points   | Start with a **strong verb**, end without period when ≤1 line.     |
| Order           | Reverse‑chronological within each section.                         |
| File name       | `Lastname_Firstname_CV_YYYY.pdf`.                                  |

*For LaTeX users*: load `moderncv` or `europecv` class; suppress colour if printing.

---

## <a id="ex1-phd-early"></a>3 | Example 1 – Early‑Stage PhD Student (1 page)

```latex
%% EARLY‑STAGE PHD CV – 1 PAGE – clean, concise         %%
%% Compile with XeLaTeX or LuaLaTeX                     %%
\documentclass[11pt,a4paper]{moderncv}
\moderncvstyle{classic}
\moderncvcolor{black}
\usepackage[scale=0.8]{geometry}
\name{ARuna}{Patel}
\title{PhD Student · Hydrology & Remote Sensing}
\address{Department of Earth Sciences · University of Michigan}{}
\phone{+1 (734) 555‑1234}
\email{apatel@umich.edu}
\social[github]{arunapatel}
\begin{document}
\makecvtitle

\section{Research Interests}
Land–atmosphere feedback, soil moisture retrieval, data assimilation.

\section{Education}
\cventry{2023–}{Ph.D. Earth & Environmental Sciences}{University of Michigan}{Ann Arbor}{}{Advisor: Prof. Z‑L Yang}
\cventry{2019–2023}{B.Sc. Geophysics (Honours)}{Peking University}{Beijing}{GPA 3.92/4.00}{Thesis: *Satellites as Virtual SM Sensors*}

\section{Selected Projects}
\cvitem{2024}{Implemented Noah‑MP \textit{sub‑grid infiltration} module in Fortran 90, reducing RMSE of runoff by 18 \% vs GLDAS benchmark.}
\cvitem{2023}{Generated 10‑year AMSR‑E soil‑moisture climatology (Python, xarray); open‑sourced dataset  \href{https://github.com/arunapatel/soilmoisture}{\faGithub}.}

\section{Technical Skills}
\cvitem{}{Python (NumPy, Pandas, PyTorch) • Fortran 90 • Git  • GNU/Linux}

\section{Publications}
\cvitem{Under review}{Patel, A., \& Yang, Z. L. (2025). *Rock moisture parameterisation improves Noah‑MP*. WRR.}

\section{Honours}
\cvitem{2024}{NSF GRFP Honorable Mention}

\section{Professional Service}
\cvitem{2024}{Reviewer, \textit{Hydrology & Earth System Sciences}}

\end{document}
```

### Why It Works

* **One page** keeps hiring committees focused.
* **Quantified impacts** (+18 % improvement) demonstrate value.
* **Clean hierarchy** via bold section titles, short bullet‑like cvitems.

---

## <a id="ex2-phd-senior"></a>4 | Example 2 – Senior PhD Candidate (2 pages, Markdown)

```markdown
# Drisana Chen · CV

**Email:** dchen@stanford.edu   |   **GitHub:** drisana‑chen   |   **ORCID:** 0000‑0002‑3456‑7890

## Profile
Atmospheric scientist leveraging physics‑based and data‑driven models to predict sub‑seasonal drought.

## Education
| Year | Degree & Institution | Details |
|------|---------------------|---------|
| 2020–2025 | **Ph.D. Civil & Environmental Engineering**, Stanford University | GPA 3.96/4.00; Advisors: Prof. Sally Thompson & Prof. Gabriel Katul |
| 2016–2020 | **B.Eng. Hydraulic Engineering**, Tsinghua University | Thesis finalist, National Excellent Graduate |

## Publications (peer‑reviewed)
1. **Chen, D.**, Thompson, S., *et al.* (2025). Hybrid LSTM–Noah forecasting of groundwater storage. **JHM**.
2. **Chen, D.** & Katul, G. (2024). Evaluating wood‑moisture capacitance in WRF‑Hydro. **WRR**, 60(7), e2024WR03456.

## Conference Papers & Talks
* AGU 23: *Coupling land and machine learning for S2D hydro‑forecast* (oral).

## Awards
* **2024** – AGU Horton Research Grant (\$10 000)
* **2023** – Stanford Graduate Fellowship (top 5 %)

## Leadership & Teaching
* **TA**, CEE 156: Environmental Fluid Mechanics (4 quarters).
* **Mentor**, Stanford Women in STEM, 3 undergraduates.

## Selected Projects
* **Noah‑MP–ML Coupling** (2024): Integrated PyTorch LSTM with Noah‑MP via CFFI, cutting runtime 42 %. [Code](https://github.com/drisana-chen/noah‑ml).
* **Open Hydro Data Portal** (2023): Designed PostgreSQL + FastAPI backend; ~7 TB served.

## Skills
Python, Fortran, C++, TensorFlow, Docker, AWS, LaTeX.
```

### Highlights

* **Table layout** for education enhances scannability.
* **Links** ↓ to code and DOIs satisfy open‑science reviewers.
* Awards and funding emphasise competitiveness.

---

## <a id="ex3-postdoc"></a>5 | Example 3 – Postdoctoral Researcher (LaTeX, compact 2 pages)

> See `examples/Postdoc_Compact.tex` for full source.  Here is the key section layout:

```latex
\section{Research Summary}
Created the first global rock‑moisture climatology; integrated into NASA LDAS.

\section{Appointments}
2025–now  \textbf{Postdoctoral Scholar}, UC Berkeley, Earth & Planetary Science
2020–2025  Graduate Research Assistant, UT Austin, Jackson School

\section{Publications – 8 selected of 16}
* \textbf{Lee, J.}, Rempe, D.
  *Rock moisture controls montane drought resilience.* **Nature Geoscience**, 2025.
```

### Tips for Postdocs

* **Appointments** section replaces “Education” as focal point.
* Limit publications to **5–10 high‑impact**; full list → ORCID link.

---

## <a id="ex4-industry"></a>6 | Example 4 – Industry R\&D Scientist (2 pages, résumé‑style)

```markdown
## Key Takeaways
1. Problem‑Action‑Result bullets per experience.  
2. Patent + product launch metrics trump publication count.

### Experience
**Climate AI Inc.** — Senior Research Scientist   *Austin, TX*   2024–present  
* Built deep‑learning soil‑moisture API → 60 enterprise clients, ARR \$3 M.  
* Led 4‑member team migrating Fortran model to GPU (25× speed‑up).

### Patents
US 17/987,654 — *System for Rock‑Moisture Sensing Using CubeSats*.
```

---

## <a id="ex5-data"></a>7 | Example 5 – Data Scientist With Publications (Hybrid)

```markdown
### Profile Snapshot
Physicist turned ML engineer applying Bayesian optimisation to renewable‑energy forecasting. Seeking R&D roles.

### Selected ML Publications (peer‑reviewed compsci venues)
| Year | Venue | Contribution |
|------|-------|--------------|
| 2024 | ICML ‘24 | Introduced **MoistNet**, a graph‑neural network for soil‑moisture prediction (Top 5 % paper award). |
| 2023 | NeurIPS | Benchmarked Physics‑Guided Neural Networks vs Noah‑MP on 10 basins. |

### Github Highlights
* `MoistNet` (⭐ 3.1k): end‑to‑end pipeline; 1000 stars in first month.
* `hydro‑bench` (⭐ 800): open benchmark with MAE/ NSE metrics.
```

---

## <a id="ex6-fellowship"></a>8 | Example 6 – Fellowship / Grant CV (Structured)

> **Key principle:** Align headings with review criteria (e.g., *Research Excellence*, *Leadership*, *Broader Impacts*).

```markdown
# Jane K. Doe — CV for NSF Earth Sciences Postdoctoral Fellowship

## Research Excellence
* 9 peer‑reviewed articles; h‑index 8.  
* PI on DOE grant \$120k (2023‑2025).

## Leadership & Outreach
* Founded “Code Blue”, free climate‑coding bootcamp (200+ participants).

## Broader Impacts
* Built bilingual hydrology curriculum adopted by 3 high schools.
```

---

## <a id="citation"></a>9 | Citation & License

Content released under MIT License. Cite as: *Best‑CV‑Polish‑Guide: Examples*, v1.0 (2025).


* Some of the CV are from https://github.com/zhanglj37/Tutorial-on-PhD-Application
