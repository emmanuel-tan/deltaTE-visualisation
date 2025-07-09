# deltaTE Project: Ribo-seq + RNA-seq Integration and Visualisation

This project demonstrates a testable, shareable workflow for analyzing differential translation efficiency from Ribo-seq and RNA-seq data. 

### Phase 1: Preprocessing and Quantification in Google Colab Notebook
- Goal: Prepare RNA-seq and Ribo-seq gene-level expression estimates from raw FASTQ reads.
- Methods: Read filtering, pseudoalignment (e.g., Salmon), transcript- and gene-level quantification.

View the project:
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/emmanuel-tan/deltaTE-qc-visualisation/blob/main/deltaTe_analysis.ipynb)

⚠️ Note:
Colab is great for testing small data or exploring the workflow logic, but it's not practical for full-scale, production-level analyses. Storage limits, session timeouts, and limited CPU/RAM mean real datasets are better run locally or on a cluster.

### Phase 2: Differential TE Analysis Visualisation in Webapp
- Goal: Identify genes with significant changes in translational efficiency
- Methods: deltaTE statistical framework (ΔRNA, ΔRibo, ΔTE modeling).

Outputs:
- Interactive visualisations of deltaTE output for result exploration
- Top gene lists classified by regulatory pattern (exclusive TE changes, buffering, etc.)

[Check out the web app](https://delta-te-viewer.streamlit.app/)

### Contact
Feel free to contact me with any feedback, comments, or ideas at emmanueltan2000@gmail.com or on [Linkedin](https://www.linkedin.com/in/emmanuel-tan-0b89051b3/)
