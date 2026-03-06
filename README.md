<div align="center">

# CS-471 · Machine Learning

**Comprehensive Study Notes & Exam Preparation**

[![LaTeX](https://img.shields.io/badge/Built%20with-LaTeX-008080?style=flat-square&logo=latex&logoColor=white)](https://www.latex-project.org/)
[![Python](https://img.shields.io/badge/Python-3.x-3776AB?style=flat-square&logo=python&logoColor=white)](https://www.python.org/)
[![MiKTeX](https://img.shields.io/badge/Compiler-MiKTeX-4A90D9?style=flat-square)](https://miktex.org/)
[![NUST](https://img.shields.io/badge/SEECS-NUST-003366?style=flat-square)](https://seecs.nust.edu.pk/)

<br>

*7 weeks · 41 exam questions · 120+ pages of notes*

</div>

---

## About

This repository is a fully self-contained study system for **CS-471 Machine Learning** at SEECS NUST. Raw lecture slides were programmatically extracted using a Python pipeline, then transformed into polished, structured LaTeX documents — complete with color-coded concept boxes, step-by-step mathematical derivations, worked examples, and practice questions. A dedicated exam question bank with full solutions covers the entire course syllabus.

> **Author:** Sohaib Sarwar &nbsp;|&nbsp; **Instructor:** Dr. Hashir Kiani &nbsp;|&nbsp; **Institution:** SEECS, NUST

---

## What's Inside

<table>
<tr>
<td width="50%">

**<img src="https://cdn.jsdelivr.net/npm/@fortawesome/fontawesome-free@6.7.2/svgs/solid/book-open.svg" width="14" alt="Lecture Notes icon" /> Lecture Notes** — 7 weeks of hand-crafted LaTeX notes compiled from original slides. Each document includes a table of contents, color-coded concept boxes, complete derivations, and practice problems.

</td>
<td width="50%">

**<img src="https://cdn.jsdelivr.net/npm/@fortawesome/fontawesome-free@6.7.2/svgs/solid/file-signature.svg" width="14" alt="Exam Question Bank icon" /> Exam Question Bank** — 41 questions spanning all 7 weeks, categorised by difficulty `[E]` `[M]` `[H]`, each with a detailed beginner-friendly solution immediately following.

</td>
</tr>
<tr>
<td>

**<img src="https://cdn.jsdelivr.net/npm/@fortawesome/fontawesome-free@6.7.2/svgs/solid/diagram-project.svg" width="14" alt="Extraction Pipeline icon" /> Extraction Pipeline** — A Python pipeline (`pymupdf`, `pdfplumber`) that parses the original lecture PDFs to extract text, tables, and layout — the backbone of the note generation process.

</td>
<td>

**<img src="https://cdn.jsdelivr.net/npm/@fortawesome/fontawesome-free@6.7.2/svgs/solid/gears.svg" width="14" alt="Reproducible Build icon" /> Reproducible Build** — Every PDF is reproducible from source. All `.tex` files are clean, well-commented, and compile deterministically with any standard LaTeX distribution.

</td>
</tr>
</table>

---

## Repository Structure

```
Machine Learning Course/
│
├── Course Lectures/
│   ├── Week 1/   ── Intro to ML, Linear Regression, Gradient Descent
│   │   ├── CS-471-Lecture 1.pdf          ← original lecture slides
│   │   ├── lecture_notes.tex             ← LaTeX source (43 KB)
│   │   └── lecture_notes.pdf             ← compiled notes · 17 pages
│   │
│   ├── Week 2/   ── Learning Rates, Evaluation Metrics, Classification
│   │   ├── CS-471-Lecture 2-1.pdf
│   │   ├── CS-471-Lecture 2-2.pdf
│   │   ├── lecture_notes.tex             ← LaTeX source (39 KB)
│   │   └── lecture_notes.pdf             ← compiled notes · 17 pages
│   │
│   ├── Week 3/   ── Logistic Regression, Cross-Entropy Loss
│   │   ├── CS-471-Lecture 3-1.pdf
│   │   ├── lecture_notes.tex             ← LaTeX source (28 KB)
│   │   └── lecture_notes.pdf             ← compiled notes · 11 pages
│   │
│   ├── Week 4/   ── Multiclass, Softmax, Model Evaluation
│   │   ├── CS-471-Lecture 4-1.pdf
│   │   ├── CS-471-Lecture 4-2.pdf
│   │   ├── lecture_notes.tex             ← LaTeX source (38 KB)
│   │   └── lecture_notes.pdf             ← compiled notes · 18 pages
│   │
│   ├── Week 5/   ── Regularisation, Cross-Validation, Decision Trees
│   │   ├── CS-471-Lecture 5-1.pdf
│   │   ├── CS-471-Lecture 5-2.pdf
│   │   ├── lecture_notes.tex             ← LaTeX source (42 KB)
│   │   └── lecture_notes.pdf             ← compiled notes · 17 pages
│   │
│   ├── Week 6/   ── Gini, Entropy, ID3, C4.5, CART
│   │   ├── CS-471-Lecture 6-1.pdf
│   │   ├── CS-471-Lecture 6-2.pdf
│   │   ├── lecture_notes.tex             ← LaTeX source (43 KB)
│   │   └── lecture_notes.pdf             ← compiled notes · 18 pages
│   │
│   └── Week 7/   ── Pruning, Ensembles, Random Forest, XGBoost
│       ├── CS-471-Lecture 7-1.pdf
│       ├── CS-471-Lecture 7-2.pdf
│       ├── lecture_notes.tex             ← LaTeX source (45 KB)
│       └── lecture_notes.pdf             ← compiled notes · 19 pages
│
├── Exam_Practice/
│   ├── exam_questions.tex                ← LaTeX source (66 KB)
│   └── exam_questions.pdf                ← 41 questions + solutions · 29 pages
│
├── venv/                                 ← Python virtual environment
├── requirements.txt                      ← Python dependencies
└── README.md
```

---

## Syllabus Coverage

| # | Week | Core Topics | Pages |
|---|------|-------------|-------|
| 1 | **Intro to ML** | ML definition & taxonomy · Supervised / Unsupervised / RL · Linear Regression · MSE loss · Gradient Descent · Normal Equation | 17 |
| 2 | **Optimisation & Evaluation** | Learning rate strategies · Decreasing schedule · Train/Val/Test split · MAE · MSE · RMSE · R² · Binary classification · Hinge loss | 17 |
| 3 | **Logistic Regression** | Sigmoid hypothesis · Binary cross-entropy derivation · GD update rule · 3-point classification worked example · Loss function taxonomy | 11 |
| 4 | **Multiclass & Metrics** | OvR / OvO strategies · Softmax · Categorical cross-entropy · Confusion matrix · Precision · Recall · F1 · ROC / AUC · Bias-variance tradeoff | 18 |
| 5 | **Generalisation** | Learning curves · K-Fold CV · LOOCV · Feature selection & engineering · L1 / L2 regularisation · Early stopping · Decision tree intro · **Threshold finding** | 17 |
| 6 | **Decision Trees I** | Gini impurity · Entropy & Information Gain · **CART threshold search** · ID3 · C4.5 (Gain Ratio / SplitInfo) · CART · Stopping criteria · Golf dataset | 18 |
| 7 | **Decision Trees II & Ensembles** | C4.5 missing values · CART regression · Pre/post-pruning · χ² pruning · C4.5 error-based pruning · Bagging · Random Forest · Boosting · XGBoost | 19 |

---

## Exam Question Bank

`Exam_Practice/exam_questions.pdf` — **29 pages · 41 questions · full solutions**

Every question is tagged by difficulty and immediately followed by a step-by-step, beginner-friendly solution.

| Difficulty | Tag | Description |
|------------|-----|-------------|
| Easy | `[E]` | Direct recall, single formula, one-step computation |
| Medium | `[M]` | Multi-step derivation, algorithm trace, numerical worked example |
| Hard | `[H]` | Exam-level — design decisions, cross-week integration, open reasoning |

| Section | `[E]` | `[M]` | `[H]` | Total |
|---------|--------|--------|--------|-------|
| Week 1 | 3 | 3 | 1 | 7 |
| Week 2 | 0 | 4 | 0 | 4 |
| Week 3 | 0 | 2 | 2 | 4 |
| Week 4 | 1 | 2 | 1 | 4 |
| Week 5 | 2 | 2 | 2 | 6 |
| Week 6 | 1 | 3 | 2 | 6 |
| Week 7 | 1 | 2 | 2 | 5 |
| Mixed (All Weeks) | 0 | 0 | 5 | 5 |
| **Total** | **8** | **18** | **15** | **41** |

---

## LaTeX Design System

All notes share a consistent, color-coded tcolorbox layout for instant visual parsing.

| Environment | Accent | When it appears |
|-------------|--------|-----------------|
| `keybox` | Blue | Core definitions, key ideas, central formulas |
| `exbox` | Green | Step-by-step worked examples |
| `practbox` | Red | End-of-section practice questions |
| `summbox` | Gray | Quick-reference summaries and cheat sheets |
| `altbox` | Yellow/Orange | Alternative methods, shortcuts, tricks |
| `warnbox` | Red | Common mistakes, pitfalls, misconceptions |
| `derivbox` | Blue | Full mathematical derivations |

All hyperlinks use `hidelinks` — no red link borders appear in any compiled PDF.

---

## Key Formulas

<details>
<summary><strong>Linear Regression</strong></summary>

```
h(x)  =  wᵀx
MSE   =  (1/n) Σ (yᵢ − ŷᵢ)²
w_new =  w_old − α ∇_w Loss
αₜ    =  α₀ / √t          (decreasing schedule)
```
</details>

<details>
<summary><strong>Logistic Regression</strong></summary>

```
p̂  =  σ(s)  =  1 / (1 + e^{−s})
L  =  −[ y log p̂ + (1−y) log(1−p̂) ]       (binary cross-entropy)
w_new  =  w_old − α Σᵢ (p̂ᵢ − yᵢ) xᵢ
```
</details>

<details>
<summary><strong>Softmax & Multiclass</strong></summary>

```
P(y=k | x)  =  exp(sₖ) / Σⱼ exp(sⱼ)
L  =  − Σₖ yₖ log P(y=k | x)              (categorical cross-entropy)
```
</details>

<details>
<summary><strong>Decision Trees</strong></summary>

```
Gini(S)      =  1 − Σₖ pₖ²
H(S)         =  − Σₖ pₖ log₂ pₖ
IG(S, A)     =  H(S) − Σᵥ (|Sᵥ|/|S|) H(Sᵥ)
GainRatio    =  IG / SplitInfo
SplitInfo    =  − Σᵥ (nᵥ/n) log₂(nᵥ/n)
Threshold t* =  argmax_t [ Gini(S) − weighted_Gini(t) ]
```
</details>

<details>
<summary><strong>Regularisation & Evaluation</strong></summary>

```
L_L2  =  L_data + λ Σⱼ wⱼ²          (Ridge — shrinks weights)
L_L1  =  L_data + λ Σⱼ |wⱼ|         (Lasso — sparsity)

Precision  =  TP / (TP + FP)
Recall     =  TP / (TP + FN)
F1         =  2PR / (P + R)
```
</details>

<details>
<summary><strong>Ensemble Methods</strong></summary>

```
Random Forest:  k = floor(√n) features per split
XGBoost:        ŷ = Σ_b η · f_b(x)    (η = shrinkage / learning rate)
Chi-squared:    χ² = Σₖ [(pₖ − p̂ₖ)²/p̂ₖ + (nₖ − n̂ₖ)²/n̂ₖ]
```
</details>

---

## Python Pipeline Setup

The `venv/` environment powers the PDF parsing and note-generation pipeline.

```bash
# 1. Create virtual environment
python -m venv venv

# 2. Activate
venv\Scripts\activate        # Windows
source venv/bin/activate     # macOS / Linux

# 3. Install dependencies
pip install -r requirements.txt
```

| Package | Role |
|---------|------|
| `pymupdf` | High-performance PDF parsing — text, layout, images |
| `pdfplumber` | Table extraction and visual layout debugging |
| `Pillow` | Image processing for rendered PDF pages |
| `pytesseract` | OCR fallback for scanned or image-only slides |
| `sumy` | Extractive summarisation (LSA / LexRank algorithms) |
| `nltk` | Tokenisation and language utilities for `sumy` |

---

## Recompiling PDFs

Requires [MiKTeX](https://miktex.org/) or any TeX distribution with `pdflatex`.

```powershell
# Any week — replace "Week 2" as needed
Set-Location "Course Lectures\Week 2"
pdflatex -interaction=nonstopmode lecture_notes.tex   # pass 1 → generates .toc
pdflatex -interaction=nonstopmode lecture_notes.tex   # pass 2 → embeds TOC
Remove-Item -Force *.aux, *.log, *.out, *.toc
```

```powershell
# Exam question bank
Set-Location "Exam_Practice"
pdflatex -interaction=nonstopmode exam_questions.tex
pdflatex -interaction=nonstopmode exam_questions.tex
Remove-Item -Force *.aux, *.log, *.out, *.toc
```

> **Why two passes?** The first pass writes the `.toc` auxiliary file. The second pass reads it and typesets the Table of Contents. Skipping the second pass produces a PDF with a blank or missing TOC.

---

<div align="center">

**CS-471 Machine Learning &nbsp;·&nbsp; SEECS NUST**

*Sohaib Sarwar*

</div>
