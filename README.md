# POME Project Paper - Demand Forecasting for SaaS Feature Prioritization

## File Structure

This paper is for the IEEE Access journal submission:

```
POME/Paper/
├── access.tex              # Main document (compile this)
├── ieeeaccess.cls          # IEEE Access formatting class
├── IEEEtran.cls            # IEEE base formatting class
├── README.md               # This file
├── figures/                # All figures and images
└── (compiled outputs)
    ├── access.pdf          # Generated PDF
    ├── access.aux
    ├── access.bbl
    ├── access.blg
    └── access.log
```

## Paper Overview

**Title**: Demand Forecasting for Product Design Decisions in Software Firms: A Data-Driven Framework for SaaS Feature Prioritization

**Authors**: 
- Bindu Ashwini C (Department of Placement and Training, RV College of Engineering)
- Manish Tandurkar (Department of CSE, RV College of Engineering)
- Manish H Parashar (Department of CSE, RV College of Engineering)
- Nikhil N Bharadwaj (Department of CSE, RV College of Engineering)

**Journal**: IEEE Access

**Publication Date**: January 22, 2026

## How to Compile

1. Ensure all dependencies are installed (LaTeX distribution like MiKTeX or TeX Live)
2. Navigate to the paper directory
3. Compile the main file: 
   ```bash
   pdflatex access.tex
   ```
4. If you have bibliography/citations to process:
   ```bash
   pdflatex access.tex
   pdflatex access.tex
   ```
5. The output PDF will be generated as `access.pdf`

### Using latexmk (Recommended)
For automatic compilation with all dependencies resolved:
```bash
latexmk -pdf access.tex
```

## Adding Figures

1. Place all image files in the `figures/` directory
2. Reference them in your LaTeX code:
   ```latex
   \begin{figure}[htbp]
   \centerline{\includegraphics{figures/your_image.png}}
   \caption{Your caption here.}
   \label{fig:yourlabel}
   \end{figure}
   ```

## Tips

- **LaTeX Comments**: Use `%` to add comments in your .tex files
- **Labels**: Use consistent naming for labels (e.g., `fig:architecture`, `sec:intro`)
- **Cross-references**: Use `\ref{label}` to reference figures, sections, equations
- **Backup**: Keep regular backups of your work
- **Version Control**: Consider using Git for better collaboration

## Common LaTeX Commands

- Section: `\section{Title}`
- Subsection: `\subsection{Title}`
- Bullet list: `\begin{itemize} \item ... \end{itemize}`
- Numbered list: `\begin{enumerate} \item ... \end{enumerate}`
- Bold: `\textbf{text}`
- Italic: `\textit{text}`
- Citation: `\cite{reference_key}`
