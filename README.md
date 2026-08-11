<h1 align="center">Tianyi MA</h1>
<h3 align="center">Quantitative Research · Stochastic Modelling & Optimisation · Infrastructure Valuation</h3>

<p align="center">
  <a href="https://www.linkedin.com/in/tyma/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?logo=linkedin&logoColor=white&style=for-the-badge"/>
  </a>
  <a href="mailto:Tianyi-Ma@outlook.com">
    <img src="https://img.shields.io/badge/Email-Contact-000?logo=maildotru&logoColor=white&style=for-the-badge"/>
  </a>
  <a href="https://steedpower.com">
    <img src="https://img.shields.io/badge/Homepage-000?logo=safari&logoColor=white&style=for-the-badge"/>
  </a>
</p>

<!--
CV BADGE REMOVED ON PURPOSE. The old one pointed at
TSdreamer/TSdreamer/blob/main/HaotianMa_CV.pdf — a file named under a
former name, and almost certainly an outdated CV. Upload the current PDF,
then add the badge back with the real path. A dead or stale CV link is
worse than no CV link.

TWITTER BADGE REMOVED. Add it back only if the account is one you are
happy for a hiring manager to read end to end.
-->

---

## Profile

Quantitative researcher; UCL PhD in Systems Modelling and Optimisation, awarded 2026, specialising in stochastic modelling, numerical optimisation and statistical model validation. Five years of computational modelling applied to infrastructure valuation — pricing the physical layer that compute and automation run on.

Work spans the full model lifecycle: formulation, calibration against observed data, implementation, out-of-sample testing, and interpretation into a decision. Five peer-reviewed publications and two manuscripts under review; first and corresponding author on five. Journal peer reviewer for Elsevier and IEEE titles.

---

## What I actually build

**Stochastic simulation at scale** — a 20-year Monte Carlo engine at 15-minute resolution, roughly 0.7 million time steps per path, solved repeatedly across scenario sets rather than at a single base case. Restructured the solve path to take a multi-day computation down to an error-checked overnight run.

**Surrogates that hold up** — reduced-order models cross-validated against the full engine to roughly 500× faster revaluation, with approximation error quantified and bounded before any result is released.

**Optimisation under uncertainty** — two-stage stochastic programmes with recourse and non-anticipative first-stage decisions, over 100 coupled scenarios with tail events deliberately retained rather than averaged away.

**Model challenge** — out-of-sample robustness and optimality metrics, hypothesis testing with multiplicity control, reconciliation of reduced models against physical benchmarks. The point is to establish whether a conclusion is driven by a real effect, a binding constraint, or a modelling artefact.

---

## Toolset

| | |
|---|---|
| **Languages** | Python, C++, MATLAB, SQL |
| **Python** | pandas, NumPy, SciPy, scikit-learn, Matplotlib — modular, object-oriented libraries with unit tests, validation harnesses and version control |
| **C++** | CMake builds, Python bindings for compute-bound solver routines |
| **Stochastic** | Ornstein–Uhlenbeck and mean-reverting calibration, Monte Carlo, scenario construction and k-means reduction, uncertainty propagation |
| **Statistics** | Hypothesis testing with multiplicity control, out-of-sample validation, goodness-of-fit, VaR / CVaR / expected shortfall, P10/P50/P90 |
| **Optimisation** | Two-stage stochastic programming with recourse, MILP via PuLP/CBC, dual-based interpretation of binding constraints |
| **ML** | Surrogate and reduced-order modelling, cross-validation with error bounds, recurrent networks for sequence data, SHAP, TensorFlow/Keras |

---

## Repositories

- **[PriceModel](https://github.com/TianyMa/PriceModel)** — end-to-end price-forecasting pipeline: data ingestion, feature and sequence construction, RNN training and evaluation, split into modular components for reuse and testing. *(Python)*
- **[ML-STOCK-PRICE](https://github.com/TianyMa/ML-STOCK-PRICE)** — machine-learning study on equity price series, with scripted experiments, input data, diagnostic outputs and a written report documenting method and limitations. *(Python / Jupyter)*
- **[LifecycleValuation](https://github.com/TianyMa/LifecycleValuation)** — lifecycle-cost and asset-valuation model: uncertain inputs propagated through state evolution to levelised cost, with parameter checks, bounded error reporting and a reproducible run path. *(Python)*
- **[Interactive Simulations](https://github.com/TianyMa/Chemical-and-Process-Engineering-Interactive-Simulations)** — notebooks for scenario analysis, sensitivity testing and communication of dynamic system behaviour to non-specialist reviewers. *(Jupyter)*

<!--
TWO THINGS TO FIX BEFORE THIS README GOES LIVE:

1. ACCOUNT SPLIT. This README lives on TSdreamer; every repo above is on
   TianyMa, which is the account the CV links to. Right now your work is
   split across two accounts and a third org (TS-energy). Pick ONE as the
   professional account, move or fork the repos you want seen, and point
   everything — CV, LinkedIn, this README — at that one.

2. LifecycleValuation is still named Degradation-PEMWE on GitHub. Rename
   it (Settings > Repository name; GitHub redirects the old URL), or
   change the name and link here and in the CV back to Degradation-PEMWE.
   The link 404s until one of those happens.

REMOVED FROM THE OLD PIN LIST:
  - awesome-machine-learning — a fork of a well-known public list.
    Pinning a fork as a highlight reads as padding.
  - Machine_Learning_MEA_Optimization, Gradient-Boosting-Tree,
    Simscape-Battery-Library — put back any that you would be happy to
    walk someone through line by line. That is the only test that matters.
-->

---

## Publications

Published as *H. Ma* and *T. Ma*; † denotes first and corresponding author.

1. **T. Ma**†, G. Qiao, X. Zhang, D. Hou, C. Spataru, G. Nikiforidis, S. Du. "Degradation-Aware Assessment of Dominant Factors in Performance, Durability, and Cost of Proton Exchange Membrane Water Electrolysers." *International Journal of Hydrogen Energy*, 264 (2026) 156855. [doi](https://doi.org/10.1016/j.ijhydene.2026.156855)
2. **H. Ma**†, G. Nikiforidis, C. Spataru. "System Modelling and Sizing Optimisation of PEM-Integrated Hybrid Energy Storage for Data-Centre Resilience." *IET Conference Proceedings*, 2025(44), 149–154. [doi](https://doi.org/10.1049/icp.2025.4902)
3. **H. Ma**†, G. Nikiforidis, S. Du. "Multiscale Modelling and Electrochemical Validation of PEM Electrolyser-Coupled Hybrid Energy Storage Systems." *IEEE SPIES*, pp. 1–6, 2025. [doi](https://doi.org/10.1109/SPIES67451.2025.11381511)
4. S. Ishaq, **H. Ma**, Y. Li, G. Nikiforidis. "Design and Optimisation of Binder-Free rGO/AlO(OH)/Al₂O₃ Aerogels for Energy Storage." *Materials Today Sustainability*, 31 (2025) 101217. [doi](https://doi.org/10.1016/j.mtsust.2025.101217)
5. Y. Li, J. Ren, **H. Ma**, A. N. Campbell. "Technical and Economic Performance Assessment of Blue Hydrogen Production Using a New Configuration Through Modelling and Simulation." *International Journal of Greenhouse Gas Control*, 134 (2024) 104112. [doi](https://doi.org/10.1016/j.ijggc.2024.104112)

**Under review**

6. **H. Ma**†, C. Spataru, W. Yang, X. Lv, G. Nikiforidis, P. Carvalho, S. Du. "Uncertainty-Aware Optimisation of PEM-Integrated Hybrid Energy Storage for Data Centres: Cost, Carbon, and Resilience Trade-offs." *Applied Energy*, 2026.
7. **H. Ma**†, G. Nikiforidis, C. Spataru. "Operational Modelling and Resilience-Oriented Sizing of Hybrid Battery–Hydrogen Storage Systems for Mission Critical Data Centres." *IET Smart Grid*, 2026.

---

## Background

**Education**

- **PhD, Systems Modelling and Optimisation** — University College London, 2024–2026. Thesis: *Multiscale Modelling and Optimisation of the PEM Electrolyser–Battery Hybrid Storage System for Data Centre Reliability*. Supervisors: Prof. Catalina Spataru, Dr Georgios Nikiforidis.
- **MSc by Research, Systems & Control** — University of Warwick, 2022–2024, Distinction. Supervisor: Prof. Sai Gu, FREng.
- **Doctoral research, Chemical Engineering & Computer Science** — University of Birmingham, 2021–2022. Registered; degree not awarded.
- **MSc, Sustainable Energy Engineering** — University of Nottingham, 2019–2021, Distinction.
- **BEng, Energy and Power Engineering** — Southeast University, 2015–2019. Outstanding Graduate, top 5%.

**Experience**

- **CATL** — Quantitative Researcher, Markets, Valuation & Technology Strategy. London, Nov 2025 – present.
- **Huawei European Research Institute** — Quantitative Researcher, Simulation & Asset Valuation. Munich, May 2023 – May 2025.
- **Global Energy Interconnection Research Institute (GEIRI)** — Quantitative Analyst, Commodity Price Risk & Asset Valuation. Berlin & Birmingham, Oct 2021 – Apr 2023.
- **University College London** — Doctoral Researcher, Stochastic Optimisation & Model Validation. London, Nov 2024 – Jul 2026.
- **XPeng Europe** — Business Analyst. Amsterdam, Netherlands.
- **WMG, University of Warwick** — Research Assistant. Coventry, UK.

<!--
XPENG AND WMG: confirmed real on 11/08/2026, simply never carried onto the
CV. They are listed here without dates because none have been given. Fill
them in — undated entries on a public profile read as padding, and a
recruiter comparing this page with the CV will notice two roles that exist
in one document and not the other.

Then do two things, in this order:
  1. Add both to the CV.
  2. Re-check the overlap timeline there. The CV already carries two
     flagged overlaps (Huawei against full-time UCL registration, CATL
     against the same). Warwick 2022-2024 also overlaps GEIRI
     Oct 2021 - Apr 2023. WMG sits at Warwick and XPeng in Amsterdam, so
     both will land somewhere in that already-crowded window. Work out
     what was concurrent and what was sequential BEFORE either document
     goes out, not when an interviewer asks.
-->

<!--
EVERY LINE IN THIS SECTION MATCHES THE CV EXACTLY. If you change one,
change both, or you have two public documents disagreeing about your own
history. See the removal notes at the foot of this file.
-->

---

<!--
================= WHAT WAS REMOVED FROM THE OLD README, AND WHY =================

This is not a tidy-up. The previous version contradicted the verified CV
in the following places. Each of these is checkable by anyone who reads
both documents, and both are public.

FACTS THAT WERE WRONG
 1. "PhD candidate" — the degree was awarded 28 July 2026.
 2. "PhD, Quantitative Energy Systems" — the award title is
    "PhD Systems Modelling and Optimisation". Award titles are fixed
    text on the Statement of Award; do not paraphrase them.
 3. "M.Sc., Electrical & Electronic Engineering — Nottingham" — it is an
    MSc in Sustainable Energy Engineering. Wrong subject entirely.
 4. "M.Res., Control Engineering — Warwick" — it is an MSc by Research in
    Systems & Control.
 5. Huawei located in Nuremberg, dated 2024 — the CV says Munich,
    May 2023 – May 2025.
 6. GEIRI located in Munich — the CV says Berlin & Birmingham. The old
    README had the two employers' cities swapped.
 7. Birmingham was missing entirely. It is on the CV, stated as
    registered and not awarded, because Hedd returns it either way.

CLAIMS WITH NO EVIDENCE BEHIND THEM
 8. "GAN-based augmentation, 822 → 12,300 samples, R² = 0.94,
    MAE = 0.028 V". These figures came from the IEEE EEEIC paper, which
    you confirmed you do not hold. The paper was struck from the CV and
    "GAN-based data augmentation" was struck from the skills section with
    it. It cannot stay here.
 9. The whole "Data-Driven Portfolio Risk Modelling & Optimisation"
    project: "150+ market data sources", "<3% forecast error" on returns
    and VaR, "Sharpe +12.5%", "manual workload reduced ~70%". None of it
    appears anywhere in five years of CV drafts. The one ±3% figure you
    do have is GEIRI lifetime operating cost calibrated against observed
    data — a different quantity, in a different job. If this project is
    real, it needs a repo and a method note before it goes back up.
10. The Huawei "Investment Support / Energy Trading Models" role:
    ESG mandates, hedging strategy design, SFDR and EU Taxonomy reporting,
    collaboration with portfolio managers and risk teams. The CV
    describes the same employer and period as simulation and lifecycle
    valuation of a 12.9 MW hybrid asset. These are two different jobs.
    One of them is the real one. Decide which, then make both documents
    say it.
11. XPeng Europe and WMG — RESTORED 11/08/2026, confirmed real. They are
    on this page now but still not on the CV, and still undated. That is
    a gap between two public documents. Close it: dates first, then add
    both to the CV, then re-check the overlap timeline.
12. "ESG risk analytics, EU Taxonomy & SFDR alignment", "PINNs",
    "PyBaMM", "COMSOL", "Julia", "Simscape", "GITT, EIS, OCV analysis".
    Dropped, not because they are false, but because a skills list is a
    list of things you can be interviewed on for five minutes. Add back
    any you can defend at that depth.

IDENTITY
13. Old header: linkedin.com/in/htma, HaotianTeemo@outlook.com, a CV file
    named HaotianMa_CV.pdf, repos on TSdreamer and TS-energy. The CV uses
    Tianyi Ma, linkedin.com/in/tyma, Tianyi-Ma@outlook.com, and TianyMa.
    Two identities, half-migrated. Pick the destination and finish the
    move: LinkedIn URL, GitHub account, email, and the CV filename.
    Publications stay under the name each was published with — that is
    citation accuracy, not inconsistency, and the note at the top of the
    Publications section explains it.

POSITIONING
14. "ESG- and climate-aligned investment modelling" and the closing
    "Long-Term Direction" block. Dropped. You are applying to G-Research,
    Jane Street, GIC and DRW. None of them is buying an ESG modeller,
    and a mission statement on a GitHub profile is read the same way it
    would be read on a CV: as conviction offered where evidence was
    asked for.
================================================================================
-->