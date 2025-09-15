# Cognitive Science & Analytics

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)  ![GitHub issues](https://img.shields.io/github/issues/sirimadhuri02/CognitiveScienceAndAnalytics)

## Table of Contents

* [Project Overview](#project-overview)
* [Key Features](#key-features)
* [Motivation](#motivation)
* [Data](#data)
* [Installation](#installation)
* [Usage](#usage)
* [Methodology](#methodology)
* [Folder Structure](#folder-structure)
* [Reproducibility & Experiments](#reproducibility--experiments)
* [Visualizations & Dashboards](#visualizations--dashboards)
* [Citations](#citations)
* [Contributing](#contributing)
* [License](#license)
* [Contact](#contact)

---

## Project Overview

This repository contains my work where I explore the intersection of **cognitive science** and **data analytics**. My aim is to study human behaviour, perception, and decision-making using data-driven approaches. I’ve included my code, documentation, and datasets so that the analyses are clear, replicable, and easy to build upon.

Some of the areas I’ve worked on include: cognitive load estimation, attention modeling, behavioral clustering, reaction-time analysis, psychometric predictions, and multimodal feature extraction.

---

## Key Features

* Preprocessing pipelines for behavioral and psychophysiological data (reaction times, surveys, EEG, eye-tracking).
* Feature engineering inspired by cognitive constructs such as working memory, attention metrics, and cognitive load proxies.
* Statistical analysis notebooks (ANOVA, mixed-effects models, etc.).
* Machine learning models for classification/regression with interpretability methods (SHAP, LIME).
* Interactive visualizations and dashboards using Plotly, Dash, or Streamlit.
* Reproducible notebooks and organized experiments.

---

## Motivation

I’ve always been fascinated by how people think, decide, and act. Cognitive science provides rich theories to explain this, while analytics helps test and quantify them. With this project, I wanted to create a bridge between psychological theory and practical data science methods. This is also a way for me to learn and share reproducible workflows with others interested in the same field.

---

## Data

I am careful with data privacy, so this repository contains either synthetic or anonymized datasets. When I use publicly available datasets, I’ve added links and proper citations.

* `/data/raw/` - original or downloaded datasets
* `/data/processed/` - cleaned and preprocessed versions
* `/data/synthetic/` - sample synthetic data I generated for testing

If you plan to use human-subjects data, please make sure to follow ethical guidelines and approval processes.

---

## Installation

```bash
# clone the repo
git clone https://github.com/your-username/your-repo.git
cd your-repo

# create virtual environment
python -m venv venv
source venv/bin/activate  # macOS / Linux
venv\Scripts\activate     # Windows

# install dependencies
pip install -r requirements.txt
```

---

## Usage

To explore my analyses, open the notebooks in `notebooks/`. Here’s a typical workflow I follow:

1. Place raw data in `/data/raw/`
2. Run preprocessing scripts in `/src/preprocessing/`
3. Explore results in `/notebooks/`
4. Train and evaluate models in `/src/models/`

Quick example with synthetic data:

```bash
python src/preprocessing/generate_synthetic.py --out data/processed/sample.csv
jupyter notebook notebooks/00_quick_start.ipynb
```

---

## Methodology

I’ve structured the project around three main principles:

1. **Theory-driven features** — linking cognitive concepts to measurable data.
2. **Robust preprocessing** — handling missingness, outliers, and synchronization in multimodal datasets.
3. **Transparent modeling** — prioritizing interpretability and clear documentation of choices.

---

## Folder Structure

```
/ (root)
├─ data/                   # raw and processed datasets
├─ notebooks/              # exploratory and modeling notebooks
├─ src/                    # scripts for preprocessing, feature extraction, models
├─ dashboards/             # Streamlit/Dash apps
├─ reports/                # figures and outputs
├─ requirements.txt
└─ README.md
```

---

## Reproducibility & Experiments

I set random seeds where possible and included experiment-tracking examples using MLflow or Weights & Biases. While results should be consistent, there may still be minor numerical differences across platforms.

---

## Visualizations & Dashboards

I’ve built a few lightweight dashboards to make the results easier to explore:

* `dashboards/attention_dash.py` (Dash)
* `dashboards/streamlit_demo.py` (Streamlit)

---

## Citations

If you build on this work, please cite this repository along with any original datasets referenced. A `CITATIONS.md` file will be added soon.

---

## Contributing

If you’d like to contribute, feel free to fork the repo and submit a pull request. I’d appreciate clear documentation of changes so others can follow along.

---

## License

This project is licensed under the MIT License. See `LICENSE` for details.

---

## Contact

Connect with me on LinkedIn.

---

*Made with curiosity and data — bringing together minds and metrics.*
