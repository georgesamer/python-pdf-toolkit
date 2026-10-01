# python-pdf-toolkit

A collection of Python notebooks and scripts demonstrating programmatic PDF generation, custom styling, and layout design using **ReportLab** (Canvas & Platypus) and **FPDF**.

## What's Inside

```
python-pdf-toolkit/
├── data/           # Input data and assets used by the notebooks
├── pdfc.ipynb      # PDF generation examples (ReportLab Canvas)
├── pdfh.ipynb      # PDF generation examples (layout and styling)
└── README.md
```

## Topics Covered

- Low-level drawing with the ReportLab **Canvas** API (text, lines, shapes, images)
- High-level document layout with ReportLab **Platypus** (paragraphs, tables, flowables, page templates)
- Building PDFs with **FPDF** (headers, footers, cells, multi-page documents)
- Custom styling: fonts, colors, spacing, and alignment
- Generating PDFs from data stored in the `data/` folder

## Requirements

- Python 3.8+
- Jupyter Notebook or JupyterLab
- Libraries:
  - `reportlab`
  - `fpdf` (or `fpdf2`)

## Installation

```bash
git clone https://github.com/georgesamer/python-pdf-toolkit.git
cd python-pdf-toolkit
pip install reportlab fpdf2 jupyter
```

## Usage

Start Jupyter and open one of the notebooks:

```bash
jupyter notebook
```

Then run the cells in order. Generated PDF files are saved in the working directory.

## Libraries

| Library | Used for |
|---------|----------|
| [ReportLab Canvas](https://docs.reportlab.com/) | Precise, coordinate-based drawing |
| [ReportLab Platypus](https://docs.reportlab.com/) | Automatic page layout and flowing content |
| [FPDF](https://py-pdf.github.io/fpdf2/) | Simple, lightweight PDF creation |

## Author

**George Samer** - [@georgesamer](https://github.com/georgesamer)
