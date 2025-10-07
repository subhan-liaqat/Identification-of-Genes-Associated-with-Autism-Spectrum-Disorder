# Identification of Genes Associated with Autism Spectrum Disorder  
**Network-Propagation Based Semi-Supervised Learning**

_Author: Subhan Liaqat_  
_Email: mughalsubhan946@gmail.com_

---

## 🧠 Overview
This project implements a **Network-Propagation-Based Semi-Supervised Learning** approach to identify and prioritize genes associated with **Autism Spectrum Disorder (ASD)**.  
The analysis integrates known ASD genes, negative control gene sets, and protein–protein interaction (PPI) data to propagate labels and rank candidate genes based on their association likelihood.

---

## 📓 Repository Contents
.
├── README.md
├── LICENSE
├── requirements.txt
├── Concept-Paper.pdf
└── FYP-Code.ipynb

yaml
Copy code

- **FYP-Code.ipynb** — main notebook containing data preprocessing, propagation model, results, and visualizations  
- **Concept-Paper.pdf** — detailed project write-up and methodology  
- **requirements.txt** — dependencies needed to run the notebook  
- **LICENSE** — MIT open-source license  

---

## ⚙️ Setup Instructions
```bash
# clone the repository
git clone https://github.com/subhan-liaqat/Identification-of-Genes-Associated-with-Autism-Spectrum-Disorder.git
cd Identification-of-Genes-Associated-with-Autism-Spectrum-Disorder

# create and activate virtual environment
python -m venv .venv
source .venv/bin/activate      # mac/linux
# .venv\Scripts\activate       # windows

# install dependencies
pip install -r requirements.txt
▶️ Running the Notebook
Launch Jupyter:

bash
Copy code
jupyter notebook
Open FYP-Code.ipynb

Run all cells sequentially to:

Load and preprocess data

Construct the protein–protein interaction network

Perform network propagation using Random Walk with Restart (RWR)

Rank candidate genes

Visualize and interpret results

📊 Results Summary
Algorithm: Random Walk with Restart (λ = 0.9)

Performance Metrics: AUROC, AUPRC, and MCC used for evaluation

Biological Insights: Top-ranked genes show enrichment in synaptic and neural signaling pathways, overlapping with known ASD candidates.

(See full results and tables in the notebook.)

🧾 Requirements
nginx
Copy code
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
📄 License
This project is licensed under the MIT License.
See LICENSE for details.

📬 Contact
For questions or collaboration:
📧 mughalsubhan946@gmail.com

Thank you for visiting this repository! 🌱
