# Identification of Genes Associated with Autism Spectrum Disorder  
**Network-Propagation Based Semi-Supervised Learning**

---

## 🧠 Project Overview

This repository contains a computational method to identify and rank genes potentially associated with **Autism Spectrum Disorder (ASD)** using a **network-propagation (semi-supervised) approach**. The entire process—from data preprocessing to propagation and analysis—is documented within the main notebook.

---

## 📂 Repository Structure

Identification-of-Genes-Associated-with-Autism-Spectrum-Disorder/
├── LICENSE
├── README.md
├── requirements.txt
├── Concept-Paper.pdf
└── FYP-Code.ipynb

yaml
Copy code

- **FYP-Code.ipynb** — The main Jupyter notebook: includes data loading, preprocessing, propagation algorithm, evaluation, and results.  
- **Concept-Paper.pdf** — The write-up / methodology description of the project.  
- **requirements.txt** — Lists Python dependencies needed to run the notebook.  
- **LICENSE** — The open-source license (e.g., MIT).  

---

## ⚙️ Setup & Installation

```bash
# Clone the repository
git clone https://github.com/subhan-liaqat/Identification-of-Genes-Associated-with-Autism-Spectrum-Disorder.git
cd Identification-of-Genes-Associated-with-Autism-Spectrum-Disorder

# (Optional but recommended) Create a virtual environment
python -m venv .venv
source .venv/bin/activate     # macOS / Linux
# .venv\Scripts\activate      # Windows

# Install dependencies
pip install -r requirements.txt
▶️ Running the Notebook
Launch Jupyter Notebook / Lab in the repo directory:

bash
Copy code
jupyter notebook
Open FYP-Code.ipynb

Execute cells in order. The notebook includes:

Data import and preprocessing

Building or loading a PPI network

Label initialization (positive / negative genes)

Network propagation (Random Walk with Restart)

Evaluation (AUROC, AUPRC, MCC)

Visualization and interpretation of top candidate genes

📊 Results & Findings
The notebook provides performance metrics such as AUROC, AUPRC, and MCC.

It also shows pathway enrichment analyses and a ranked list of top candidate genes enriched for ASD-relevant biological processes.

You can export tables and plots from the notebook (e.g. as .csv, .png) for supplementary material.

📋 Dependencies
Below is a sample of packages required (see full list in requirements.txt):

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
📜 License
This project is released under the MIT License.
See the LICENSE file for details.

✉️ Contact & Citation
If you use or extend this work, please cite the accompanying concept paper and credit the author.
For questions, feedback or collaboration, reach out: mughalsubhan946@gmail.com

Thank you for exploring this project! 🚀
