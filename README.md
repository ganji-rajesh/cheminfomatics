# Cheminformatics Journey: From Data Analyst to CADD/AI in Drug Discovery

This repository documents my transition from **AI/Data Science in finance** to **cheminformatics and computer‑aided drug design (CADD)**, with a specific goal of working in the **healthcare/life‑sciences/pharma ecosystem around Hyderabad, Telangana**.

It is a living portfolio of:
- Theory I am studying  
- Hands‑on coding exercises  
- End‑to‑end projects in virtual screening, QSAR, and molecular dynamics  

---

## 🎯 Purpose & Motivation

AI + data science roles in pure software/IT feel increasingly saturated and commoditized. At the same time, there is a clear and growing demand for **AI and data science in healthcare, life sciences, and drug discovery**, where domain knowledge matters as much as modeling skill.[web:283]

I want to:
- Leverage my **B.Sc. (Maths, Physics, Chemistry)** + **MBA in Business Analytics & Finance**  
- Combine them with **Python, ML, and data engineering**  
- Transition into **cheminformatics / CADD roles in pharma around Hyderabad**

This repo is the public record of that journey.

---

## 👤 Background

**Education**
- B.Sc. in Mathematics, Physics, Chemistry  
- MBA in Business Analytics & Finance, University of Hyderabad  

**Industry Experience**
- Data Analyst @ S&P Global (2+ years)  
- Skills: Python, Pandas, NumPy, SQL, Machine Learning, Power BI, Microsoft Fabric, financial analytics and reporting

**Transition Focus**
- Move from generic data analytics to **cheminformatics & AI‑driven drug discovery**
- Target roles: *Cheminformatics Data Scientist, CADD/AI Scientist, R&D Data Scientist (Pharma), Scientific Data Engineer*

---

## 📚 Learning Roadmap (Theory + Practice)

This repo is anchored around two core learning pillars:

### 1. Theory: IIT Madras – Computer Aided Drug Design

- **Course:** *Computer Aided Drug Design* by Prof. Mukesh Doble (NPTEL, IIT Madras)[web:170]  
- **Coverage:**
  - Drug discovery pipeline, target & lead identification
  - Drug properties, solubility, permeability, ADME/PKPD
  - Molecular modelling, force fields, basic QM
  - QSAR & 3D‑QSAR, pharmacophore modelling
  - Target‑based drug design, docking, PK/PD

I track my lecture progress and notes in this repo (see `notes/iit_madras_cadd/`).

### 2. Practice: TeachOpenCADD

- **Platform:** [TeachOpenCADD](https://projects.volkamerlab.org/teachopencadd/) – open‑source, Python‑based talktorials for CADD and structural bioinformatics[web:159]  
- **What I focus on:**
  - Data access (ChEMBL, PDB, KLIFS)
  - Descriptors, fingerprints, similarity & clustering
  - Basic ML/QSAR workflows in Python
  - Protein/ligand handling and docking
  - Introductory molecular dynamics & trajectory analysis

I gradually adapt the talktorials into my own workflows inside `notebooks/teachopencadd_adapted/`.

---

## 🧪 Core Projects in This Repo

Each project is designed to be **portfolio‑grade**, reproducible, and aligned with real‑world CADD/cheminformatics work.

### 🧬 Project A – Virtual Screening with AutoDock Vina

**Goal:**  
Identify potential inhibitors for a known target (e.g., SARS‑CoV‑2 Main Protease, Mpro) using structure‑based virtual screening.

**Key Steps:**
- Prepare target protein (e.g., PDB: 6LU7 or similar) from RCSB PDB  
- Prepare ligand library (ZINC15 / NCI Diversity Set)  
- Use **AutoDock Vina** for high‑throughput docking  
- Rank compounds by predicted binding affinity and inspect top hits in PyMOL

**Skills Demonstrated:**
- Structure‑based drug design (SBDD)
- Protein/ligand preparation, PDBQT conversion
- Automated docking pipelines, batch processing
- Basic binding‑mode and interaction analysis

**Folder:** `projects/virtual_screening/`

---

### 🧪 Project B – QSAR Model for Activity / Toxicity Prediction

**Goal:**  
Build machine learning models that predict molecular bioactivity or toxicity without docking.

**Key Steps:**
- Fetch bioactivity data (IC50, etc.) from **ChEMBL**
- Clean and standardize data (e.g., convert IC50 → pIC50)
- Compute RDKit descriptors & fingerprints (e.g., ECFP4)
- Train and evaluate models (Random Forest, SVM, etc.)
- Optionally visualize results via Power BI / Fabric dashboards

**Skills Demonstrated:**
- Ligand‑based drug design (LBDD) & QSAR
- Cheminformatics with RDKit
- Scikit‑learn ML workflow: train/test split, CV, hyperparameter tuning
- Model interpretation (feature importance, performance metrics)

**Folder:** `projects/qsar_model/`

---

### 🧪 Project C – Molecular Dynamics (MD) of a Protein

**Goal:**  
Show that proteins are dynamic by simulating a small protein (e.g., Lysozyme) in explicit solvent and analyzing structural stability.

**Key Steps:**
- System setup and solvation for Lysozyme
- Run ~10 ns MD using **GROMACS**
- Analyze RMSD, RMSF, and basic stability metrics
- Summarize how flexibility could impact binding and design

**Skills Demonstrated:**
- Molecular dynamics basics
- Linux/HPC workflows, job scripts
- Trajectory analysis and plotting

**Folder:** `projects/md_simulation/`

---

## 🗂 Repository Structure

Planned layout (may evolve as the journey continues):


---

## 🛠️ Tech Stack

**Languages & Libraries**
- Python, NumPy, Pandas, scikit‑learn
- RDKit (cheminformatics)
- Matplotlib / Seaborn (visualization)

**CADD / Cheminformatics Tools**
- AutoDock Vina (docking)
- PyMOL (visualization)
- GROMACS (molecular dynamics)
- TeachOpenCADD notebooks/workflows[web:159]

**Data / Analytics**
- Power BI, Microsoft Fabric (for dashboards and storytelling)
- SQL for dataset handling where relevant

---

## ✅ Progress Tracking

I will keep a lightweight progress log in `notes/progress_log.md`, including:

- ✅ Completed lectures (IIT Madras CADD)  
- ✅ TeachOpenCADD talktorials finished and adapted  
- ✅ Milestones for each project (MVP → v1.0 → refinements)  
- 🐞 Issues encountered and how they were solved  

This acts both as a **self‑reflection diary** and as **evidence for recruiters/interviewers**.

---

## 🎯 End Goals

By maintaining this repository, I aim to:

1. Reach **intermediate level** in cheminformatics & CADD, grounded in:
   - Solid theory (IIT Madras CADD)[web:170]  
   - Practical, reproducible pipelines (TeachOpenCADD)[web:159]  
2. Build **three strong, reusable projects** that demonstrate:
   - Virtual screening capability
   - QSAR/ML proficiency
   - MD and structural analysis basics  
3. Use this portfolio to apply for roles in:
   - Pharma/CROs in and around **Hyderabad, Telangana**
   - Life‑science AI/CADD startups
   - R&D analytics / scientific data science teams

---

## 🤝 Feedback & Collaboration

If you:
- Work in CADD/cheminformatics  
- Are hiring for such roles in Hyderabad / India  
- Or just want to share ideas, critique, or improvements  

Feel free to open an **Issue**, a **Pull Request**, or connect with me on LinkedIn ([link to be added here](https://www.linkedin.com/in/ganjirajesh/)).


