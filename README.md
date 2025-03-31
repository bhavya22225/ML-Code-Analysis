# ML-Code-Analysis
Clustering and Visualizing Programming Solutions using Transformer-based Models (CodeBERT &amp; CodeT5+)

# Overview
This project leverages CodeBERT and CodeT5+ to generate embeddings for programming solutions and applies clustering techniques (DBSCAN, UMAP, t-SNE) to visualize the patterns in the code.

# Folder Structure
ML-Code-Analysis/
├── dataset.csv              # Dataset file
├── ML-CodeBERT.ipynb           # CodeBERT-based analysis
├── ML-CodeT5+.ipynb            # CodeT5+ based analysis
├── README.md                 # Documentation
├── requirements.txt          # Python dependencies

# Installation
1. Clone the Repository
   git clone https://github.com/bhavya22225/ML-Code-Analysis.git
   cd ML-Code-Analysis

2. Create a Virtual Environment
   python -m venv ml_env
   source ml_env/bin/activate

3. Install Dependencies
   pip install -r requirements.txt

# Usage
1. Run CodeBERT Analysis
   python ML-CodeBERT.py
   
3. Run CodeT5+ Analysis
   python ML-CodeT5+.py

# Technologies Used
Transformers: CodeBERT, CodeT5+
Libraries: transformers, pandas, sklearn, matplotlib

# Results
Extracts embeddings from CodeBERT & CodeT5+
Applies clustering for code similarity analysis
Generates visualizations


   


