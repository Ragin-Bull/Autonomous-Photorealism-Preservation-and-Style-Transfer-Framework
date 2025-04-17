# Intricate Edge‑Adaptive Deep Interactive Colorization for Mitigating Chromatic Dispersion Effects

**Shatansh Patnaik (20MA20067)**  
Integrated M.Sc. in Mathematics and Computing  
IIT Kharagpur, Spring 2024–25  

---

## 📖 Overview

This repository contains the project report and associated materials for:

> **Intricate Edge‑Adaptive Deep Interactive Colorization for Mitigating Chromatic Dispersion Effects**  
> *Project‑IV (MA57302)*  
> *Supervisor: Dr. Sourav Mukhopadhyay*  
> *Submitted: April 17, 2025*

We propose an interactive colorization framework that uses sparse user scribbles and an edge‑enhancing network to reduce color‑bleeding artifacts along object boundaries. Extensive experiments on ImageNet, COCO‑Stuff and Places205 demonstrate significant improvements over state‑of‑the‑art baselines in PSNR, LPIPS and a novel Cluster Discrepancy Ratio (CDR) metric.

---

## Clone the repository
```bash
git clone https://github.com/<your‑username>/edge‑adaptive‑colorization.git
cd edge‑adaptive‑colorization

pip install -r requirements.txt

python scripts/utils.py --prepare-data --input-dir data/raw --output-dir data/processed
```
