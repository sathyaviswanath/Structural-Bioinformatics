# Structural Bioinformatics – Alzheimer’s Disease Protein Analysis
This project focuses on the structural and functional analysis of key protein targets associated with **Alzheimer’s disease (AD)**, a progressive neurodegenerative disorder characterized by memory loss and cognitive decline. The study integrates sequence-based analysis, structure prediction, validation and comparative structural biology to understand disease-related molecular mechanisms.

## 🧬 Proteins Studied
The following Alzheimer’s disease–associated proteins were analyzed:

1. **Amyloid-β Precursor Protein (APP)**
2. **Tau Protein (MAPT)**
3. **Beta-Secretase 1 (BACE1)**
4. **Apolipoprotein E (ApoE)**
5. **Beclin-1 (BECN1)**

These proteins play central roles in amyloid plaque formation, tau aggregation, lipid metabolism, and impaired autophagy—key pathological hallmarks of AD.

## 🔬 Project Workflow

### 1️⃣ Sequence Retrieval
- Protein sequences were retrieved from **UniProt** for all five targets.

### 2️⃣ Primary Structure Analysis
- Physicochemical properties such as molecular weight, isoelectric point, instability index, and amino acid composition were analyzed using **ProtParam**.

### 3️⃣ Secondary Structure Prediction
- Secondary structural elements (α-helices, β-sheets, coils) were predicted using **PSIPRED**.

### 4️⃣ Tertiary Structure Prediction and Validation
- 3D structures were modeled using **SWISS-MODEL**.
- Structural validation was performed using:
  - **Ramachandran Plot analysis**
  - **Verify3D**

### 5️⃣ Comparative Structural & Functional Analysis
- Predicted structures were compared with experimentally resolved structures from the **Protein Data Bank (PDB)**.
- Structural superposition and RMSD calculations were carried out using **UCSF ChimeraX**.
- Functional region conservation, residue-level interactions, and hydrogen bonding patterns were analyzed.

## 🔬 Summary of Structural & Functional Comparison

### **Table 1: Structural Comparison Metrics and Key Observations**

| Protein | RMSD (Å) | Structural Similarity | Functional Region Conservation | Key Observations |
|--------|----------|----------------------|--------------------------------|------------------|
| Amyloid Precursor Protein (APP) | 0.333 | Very High | Highly conserved | Strong backbone alignment; ~20 hydrogen bonds stabilize amyloidogenic regions; deviations limited to flexible loop regions influencing amyloid-β cleavage. |
| Tau Protein (MAPT) | 1.217 | Moderate | Partially conserved | Core regions conserved while intrinsically disordered regions show flexibility; structural deviations reflect aggregation-prone nature of Tau. |
| Beta-Secretase 1 (BACE1) | 0.530 | High | Highly conserved | Catalytic core and active site residues preserved; minimal deviations ensure efficient APP cleavage. |
| Apolipoprotein E (ApoE) | 0.773 | High | Conserved | ~20 hydrogen bonds stabilize lipid-binding regions; surface-level deviations may affect amyloid-β clearance efficiency. |
| Beclin-1 (BECN1) | 0.754 | High | Conserved | Autophagy-related domains structurally preserved; flexible termini may influence regulatory interactions. |


## 🧠 Disease-Relevant Interpretation in Alzheimer’s Context

### **Table 2: Protein-Specific Observations Interpreted in Alzheimer’s Disease Pathology**

| Protein | Role in Alzheimer’s Disease | Structural Interpretation | Pathological Implication |
|--------|-----------------------------|---------------------------|--------------------------|
| Amyloid Precursor Protein (APP) | Source of amyloid-β peptides | Conserved amyloidogenic regions with flexible cleavage sites | Subtle conformational variations may modulate amyloid-β production and plaque formation. |
| Tau Protein (MAPT) | Neurofibrillary tangle formation | Higher RMSD reflects intrinsic disorder and conformational flexibility | Structural instability facilitates hyperphosphorylation and aggregation into neurofibrillary tangles. |
| Beta-Secretase 1 (BACE1) | Initiates amyloidogenic processing | Stable catalytic domain with low RMSD | Structural integrity explains its efficiency and suitability as a therapeutic target. |
| Apolipoprotein E (ApoE) | Lipid transport and amyloid clearance | Conserved functional domains with surface variability | Structural variation may impair amyloid-β clearance, contributing to isoform-dependent AD risk. |
| Beclin-1 (BECN1) | Autophagy regulation | Moderately conserved structure with regulatory flexibility | Structural disruption may impair autophagy, leading to toxic protein accumulation. |

## 📌 Key Takeaways
- Core functional domains across all five proteins remain structurally conserved.
- Disease pathology is largely driven by **localized conformational changes**, flexibility, and regulatory region deviations rather than global structural loss.
- Structural bioinformatics provides critical insight into **amyloid formation, tau aggregation, enzymatic processing, lipid metabolism, and impaired clearance mechanisms** in Alzheimer’s disease.

## 🧪 Tools & Databases Used
- UniProt  
- ProtParam  
- PSIPRED  
- SWISS-MODEL  
- Ramachandran Plot  
- Verify3D  
- UCSF ChimeraX  
- Protein Data Bank (PDB)

## 📁 Repository Structure
- `Documentation/` – Step-wise analysis files  
- `ChimeraX/` – Structural comparison images  
- `Images/` – Visual outputs  
- `Outputs/` – Prediction and validation results  
- `Raw_Data/` – Sequence data  

---

**This project demonstrates an end-to-end structural bioinformatics workflow applied to a real-world neurodegenerative disease problem.**
