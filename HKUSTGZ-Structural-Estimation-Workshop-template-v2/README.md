# HKUST(GZ) Structural Estimation Workshop

Private repository for the HKUST(GZ) Structural Estimation Workshop.

The workshop is organized around **learning structural estimation by implementing models**, rather than only reading papers. The repository therefore keeps the model, data, numerical methods, tutorial materials, reproducible code, and presentation files together.

## Workshop Format

- Reading group
- Coding/tutorial sessions
- Replication presentations
- Discussion of implementation and numerical issues

## Main Goals

By the end of the workshop, participants should be able to:

1. Understand the main logic of structural estimation.
2. Translate an economic model into estimable equations or computational objects.
3. Choose appropriate estimation methods for different model structures.
4. Implement calibration, MLE, GMM, SMM, simulation, and numerical optimization.
5. Read structural papers with attention to identification, computation, and data construction.
6. Replicate selected empirical or computational results and explain the implementation clearly.

## Repository Structure

```text
HKUSTGZ-Structural-Estimation-Workshop/
├── README.md
├── schedule.md
├── presentation_guidelines.md
├── .gitignore
│
├── 2026/
│   ├── week01_...
│   │   ├── README.md
│   │   ├── slides/
│   │   ├── tex/
│   │   ├── papers/
│   │   ├── tutorial/
│   │   └── code&data/
│   ├── week02_...
│   └── ...
│
├── templates/
│   ├── weekly_template.md
│   └── presentation_template.tex
│
└── shared-resources/
    └── README.md
```

## What Goes Where?

| Folder | Content |
|---|---|
| `slides/` | PDF or PPT presentation files |
| `tex/` | LaTeX/Beamer source files |
| `papers/` | Assigned readings and related papers |
| `tutorial/` | Method notes, exercises, notebooks, and step-by-step tutorials |
| `code&data/` | Replication code, toy data, scripts, and data documentation |

> Large or confidential raw data should not be committed to GitHub. Put a `README.md` in `code&data/` explaining the data source, download instructions, or local path instead.

## Weekly Workflow

### Before the session

1. The presenter updates the weekly `README.md`.
2. Upload the assigned readings to `papers/`.
3. Put tutorial material in `tutorial/`.
4. Put code and shareable data in `code&data/`.
5. Put LaTeX source in `tex/`.
6. Upload the compiled slides to `slides/`.

### During / after the session

1. Update the README with implementation issues or discrepancies if useful.
2. Commit revised code/tutorial material.
3. Keep replicated tables, figures, or moments in the relevant weekly folder.

## Naming Convention

Recommended:

```text
author_year_short_title.pdf
week04_demand_estimation_slides.pdf
main.tex
logit_tutorial.ipynb
replication_main.py
data_dictionary.md
```

Avoid vague names such as:

```text
final.pdf
final_v2.pdf
new.py
test2.ipynb
```

## Repository Policy

This is a private internal research repository. Please do not redistribute unpublished manuscripts, restricted data, preliminary research materials, or other participants' work without permission.
