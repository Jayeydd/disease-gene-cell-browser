# UCSC Cell Browser — FBN1 / Marfan Syndrome Activity

**Student:** Jade Angela

**Date:** 2026-09-26

**Gene:** FBN1 (Fibrillin 1)

**Disease:** Marfan syndrome

---

## Part A — Introduction
FBN1 encodes fibrillin-1, a major structural component of extracellular microfibrils in connective tissue. Pathogenic variants cause **Marfan syndrome** — a disorder affecting the heart, aorta, eyes, skeleton, and skin. This activity uses single-cell RNA sequencing data from the UCSC Cell Browser to identify which cell types in the human heart express FBN1.

---

## Part B — Dataset Selection
| Item | Information |
|---|---|
| Dataset Name | Heart Cell Atlas — Overview |
| Tissue/Organ | Adult human heart |
| Relevance | Marfan syndrome weakens connective tissue in heart valves, aorta, and vessel walls. FBN1 produces fibrillin-1 to strengthen these structures — this dataset includes fibroblasts, vascular cells, and cardiomyocytes where FBN1 functions. |
| Species | Human (Homo sapiens) |
| Reference | Litviňuková et al. (2020) *Nature* |
| Dataset URL | https://cells.ucsc.edu/?ds=heart-cell-atlas |

**Screenshot 1 — Dataset Selected:**
![Dataset Info](images/01_dataset.jpg)

---
## Part C — Understand the Cell Map

| Question | Answer |
|---|---|
| a. Visualization type | UMAP (Uniform Manifold Approximation and Projection) |
| b. One dot represents | A single individual cell from the adult human heart |
| c. Clusters represent | Groups of cells with similar gene-expression profiles — corresponding to specific cell types or functional states |
| d. Three visible cell-type labels | Fibroblast, Endothelial, Smooth muscle cells |

**Screenshot 2 — UMAP Cell Map:**
![UMAP Cell Map](images/02_umap_map.jpg)

---
 ## Part D — FBN1 Gene Expression
 | Question | Answer |
 |---|---|
 | a. Assigned gene symbol | FBN1 |
 | b. Dataset used | Heart Cell Atlas — Global (486k cells) |
 | c. Expression pattern | Restricted — not uniformly expressed across all cells; concentrated in specific clusters |
 | d. Strongest expression clusters | Fibroblast cluster (highest levels — orange/brown coloring) |
 | e. Low/no expression clusters | Endothelial cells, Atrial/Ventricular Cardiomyocytes, Myeloid, Lymphoid — mostly light blue, near-zero detection |
 **Screenshot 3 — FBN1 Expression Map:**
 ![FBN1 Expression](images/03_fbn1_expression.jpg)

 ---
## Part E — Cell Types Expressing FBN1

| Question | Answer |
|---|---|
| a. Strongest expression cluster | Fibroblasts — selected and clearly the most prominent cluster with FBN1 activity |
| b. Second detectable cluster | Smooth_muscle_cells / Pericytes — visible but lower signal |
| c. Low/undetected clusters | Endothelial, Atrial/Ventricular Cardiomyocytes, Myeloid, Lymphoid — faint/near baseline |
| d. Expression pattern | Highly cell-type restricted — concentrated in fibroblasts that build connective tissue |
| e. Biological explanation | FBN1 produces fibrillin-1, the main structural protein in connective tissue. Fibroblasts are the primary cells that synthesize and secrete this extracellular matrix — so they show the highest expression. Smooth muscle cells also support vessel walls but at lower levels. Cardiomyocytes and endothelial cells have different specialized functions and do not produce significant fibrillin-1. |

**Screenshot 3 — Selected Fibroblast Cluster & FBN1 Expression:**
![FBN1 Cell Types](images/03_cell_types_expression.jpg)

---
## Part F — Expression Plot (Dot Plot)

| Question | Answer |
|---|---|
| a. Selected cells / cluster examined | Fibroblast cluster |
| b. Expression compared to other clusters | FBN1 shows the highest expression in fibroblasts — both average level (color intensity) and percentage of cells expressing it (dot size) are far greater than in any other cell type. Smooth muscle cells and pericytes show faint signal; all other clusters are near baseline. |
| c. Additional insight from the plot | The UMAP map shows spatial distribution; the dot plot quantifies **both expression magnitude and prevalence**. It reveals that FBN1 is not just high in a few cells — it is a consistent feature of fibroblasts. This supports its biological role: fibrillin-1 is a core extracellular matrix protein produced broadly by connective tissue–making cells, not by other heart cell types. |

**Screenshot 4 — FBN1 Dot Plot by Cell Type:**
![FBN1 Dot Plot](images/04_expression_plot.jpg)

