# Identification of Genes Associated with Autism Spectrum Disorder using Network-Propagation Based Semi-Supervised Learning

---

## 🧠 Project Overview

This repository implements a **Network-Propagation-Based Semi-Supervised Learning** approach to identify and prioritize genes associated with **Autism Spectrum Disorder (ASD)**.  
It integrates known ASD genes, negative control gene sets, and protein–protein interaction (PPI) networks to propagate labels and rank candidate genes by association likelihood.  
All steps — preprocessing, propagation, evaluation, and visualization — are performed inside a single Jupyter Notebook.

---

## 📂 Repository Structure
```
Identification-of-Genes-Associated-with-Autism-Spectrum-Disorder/
├── FYP-Code.ipynb
├── Data/
│ ├── SFARI-Gene_genes.csv
│ ├── negative_genes.csv
│ └── ppi_network_largest_component.edgelist
├── README.md
└── requirements.txt
```
- **FYP-Code.ipynb** → main notebook containing data loading, propagation algorithm, and result analysis  
- **Concept-Paper.pdf** → project concept and detailed methodology  
- **requirements.txt** → dependencies required to run the notebook  
- **LICENSE** → MIT open-source license  

---

## ⚙️ Setup & Installation

# Clone the repository
```
git clone https://github.com/subhan-liaqat/Identification-of-Genes-Associated-with-Autism-Spectrum-Disorder.git
cd Identification-of-Genes-Associated-with-Autism-Spectrum-Disorder
```
# (Optional but recommended) Create a virtual environment
```
python -m venv .venv
source .venv/bin/activate      # macOS / Linux
# .venv\Scripts\activate       # Windows
```
# Install dependencies
```
pip install -r requirements.txt
```
---

## ▶️ Running the Notebook

1. Launch Jupyter Notebook:
   jupyter notebook

2. Open **FYP-Code.ipynb**  
3. Run all cells sequentially to:
   - Load and preprocess data  
   - Construct or load the PPI network  
   - Initialize positive/negative gene labels  
   - Perform network propagation (Random Walk with Restart)  
   - Evaluate performance (AUROC, AUPRC, MCC)  
   - Visualize results and rank candidate genes  

---

## 📊 Results & Findings

- **Algorithm:** Random Walk with Restart (λ = 0.9)  
- **Metrics:** AUROC, AUPRC, and MCC used for evaluation  
- **Key Findings:** Top-ranked genes show strong enrichment for synaptic signaling, neuronal communication, and pathways linked to ASD.  
- Full tables, metrics, and plots are available in the notebook.

---

## 📋 Dependencies

These are the primary packages required (see full list in requirements.txt):
```
numpy  
scipy  
pandas  
networkx  
scikit-learn  
matplotlib  
seaborn  
tqdm  
gseapy  
requests  
```
---

## 📄 License

This project is released under the **MIT License**.  
See the LICENSE file for full details.

---

## ✉️ Contact & Citation

If you use or build upon this work, please cite the accompanying concept paper and credit the author.  
For questions or collaboration:  
📧 **mughalsubhan946@gmail.com**

---

Thank you for visiting this repository! 🌱
