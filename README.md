# CV - Akindu Delgahagoda

This repository contains the LaTeX source code for my Curriculum Vitae.

## 🚀 Overview

The CV is written in LaTeX and is automatically compiled and deployed using GitHub Actions.

- **Latest PDF Version:** [Download CV](https://AkinduID.github.io/my-cv/akindu_delgahagoda_cv.pdf)
- **Viewer:** [View Online](https://AkinduID.github.io/my-cv/)

## 🛠️ Automated Build

This repository includes a GitHub Actions workflow (`.github/workflows/latex-compile.yml`) that triggers on every push to the `main` branch.

**Workflow steps:**
1.  **Checkout:** Retrieves the latest code.
2.  **Compile:** Uses `xu-cheng/latex-action` to build `main.tex` into a PDF.
3.  **Prepare:** Moves the PDF and generates a simple HTML viewer.
4.  **Deploy:** Pushes the artifacts to the `gh-pages` branch.

## 📝 Editing

To edit the CV locally:

1.  Clone the repository:
    ```bash
    git clone https://github.com/AkinduID/my-cv.git
    ```
2.  Open `main.tex` in your preferred LaTeX editor (e.g., VS Code with LaTeX Workshop, Overleaf, or TeXShop).
3.  Build the project using your local LaTeX distribution (TeX Live, MiKTeX, etc.).

## 📂 Structure

- `main.tex`: The main LaTeX source file.
- `.github/workflows/`: Contains the CI/CD configuration.
- `public/`: (Generated during build) Contains the deployable assets.
