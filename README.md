# 🧠 Generalization of V1 Neural Representations Between Supervised and Unsupervised Learning

<div align="center">

![Python](https://img.shields.io/badge/Python-3.10+-blue.svg)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)
![Computational Neuroscience](https://img.shields.io/badge/Field-Computational%20Neuroscience-green.svg)
![Machine Learning](https://img.shields.io/badge/Machine-Learning-red.svg)
![Neuromatch Academy](https://img.shields.io/badge/Neuromatch-Academy-purple.svg)

**Neuromatch Academy 2026 Final Project**

*Investigating whether neural representations learned in the primary visual cortex (V1) during supervised learning generalize to unsupervised learning.*

</div>

---

# Abstract

Learning continuously reshapes neural representations in the brain, but an important open question remains:

> **Can neural representations learned during supervised learning generalize to unsupervised learning?**

In this project we analyze large-scale calcium imaging recordings from **50,000+ neurons** in the mouse visual cortex to investigate how learning changes neural population activity.

Using behavioral recordings, neural population analysis, and classification-based decoding, we evaluate the transferability of learned V1 representations between active (reward-driven) and passive learning paradigms.

Our results suggest that learning creates **specialized, context-dependent neural representations** that transfer only weakly across different behavioral conditions. :contentReference[oaicite:0]{index=0} :contentReference[oaicite:1]{index=1}

---

# Project Highlights

✅ Large-scale neural population analysis

✅ 50,000+ recorded neurons

✅ Behavioral and neural data integration

✅ Representation learning analysis

✅ Supervised vs Unsupervised comparison

✅ Confusion matrix evaluation

✅ Population-level visualization

---

# Repository Structure

```
.
├── SOHEIL_visual_learning_80k_neurons.ipynb
├── README.md
├── requirements.txt
│
├── figures/
│   ├── neural_activity.png
│   ├── behavior.png
│   ├── confusion_matrix.png
│   └── ...
│
├── presentation/
│   └── NMA Presentation.pdf
│
└── assets/
    └── banner.png
```

---

# Motivation

The primary visual cortex (V1) is known to undergo substantial functional reorganization during learning.

Previous studies have demonstrated that:

- visual representations become increasingly selective,
- perceptual learning modifies neural tuning,
- behavioral context influences cortical activity.

However, whether representations learned during active supervised learning remain useful in passive or unsupervised settings remains largely unexplored.

This project aims to answer that question by analyzing neural population dynamics before and after learning. :contentReference[oaicite:2]{index=2}

---

# Research Question

**Can neural representations learned through supervised learning transfer to unsupervised learning?**

Specifically, we investigate:

- How V1 neural activity changes during learning.
- Whether learned representations generalize across learning paradigms.
- How behavioral context influences neural coding.
- Whether classifiers trained in one condition perform well in another.

---

# Dataset

This project uses the large-scale dataset introduced by **Zhong et al. (2025)**.

Dataset characteristics include:

- Large-scale two-photon calcium imaging
- More than **50,000 simultaneously recorded neurons**
- Mouse visual cortex
- Multiple cortical visual areas
- Behavioral recordings
- Learning across multiple experimental sessions

The experimental task involves visual discrimination inside a virtual reality environment where mice learn through reward-based feedback. :contentReference[oaicite:3]{index=3}

---

# Methodology

## Data Processing

- Loading neural recordings
- Behavioral synchronization
- Trial extraction
- Stimulus alignment
- Data preprocessing
- Population activity extraction

---

## Behavioral Analysis

Behavioral variables include:

- Running speed
- Position
- Trial timing
- Visual stimuli
- Reward timing

These variables are synchronized with neural recordings to investigate learning-dependent changes.

---

## Neural Analysis

The notebook explores:

- Single neuron responses
- Population activity
- Neural tuning
- Learning-dependent activity
- Active vs passive representations

---

## Machine Learning Analysis

To evaluate representation transfer we compare:

### Supervised → Unsupervised

Classifier trained on supervised condition and tested on passive condition.

### Unsupervised → Supervised

Classifier trained on passive condition and tested on supervised condition.

Performance is evaluated using:

- Accuracy
- Confusion Matrix
- Cross-condition decoding

---

# Results

The project demonstrates several important findings:

- Supervised learning creates specialized V1 representations.
- Neural activity reorganizes after learning.
- Representation transfer between active and passive conditions is limited.
- Behavioral context strongly affects decoding performance.
- Learning does not produce universally transferable representations. :contentReference[oaicite:4]{index=4}

---

# Visualizations

The notebook includes visualizations such as:

- Neural activity traces
- Behavioral trajectories
- Population responses
- Running speed
- Trial alignment
- Stimulus timing
- Classification results
- Confusion matrices

> *(Replace this section with screenshots from your notebook for a much more attractive repository.)*

---

# Technologies

| Category | Tools |
|-----------|------|
| Language | Python |
| Environment | Jupyter Notebook |
| Scientific Computing | NumPy, SciPy |
| Data Analysis | Pandas |
| Visualization | Matplotlib |
| Machine Learning | scikit-learn |

---

# Installation

Clone the repository

```bash
git clone https://github.com/yourusername/V1-Generalization.git

cd V1-Generalization
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run

```bash
jupyter notebook
```

Open

```
SOHEIL_visual_learning_80k_neurons.ipynb
```

---

# Future Improvements

Potential future extensions include:

- Dimensionality reduction (PCA, UMAP, t-SNE)
- Representation similarity analysis (RSA)
- Neural manifold analysis
- Contrastive representation learning
- Deep neural network comparison
- Transformer-based neural decoding
- Cross-session representation stability
- Temporal population dynamics
- Self-supervised learning approaches

---

# Team

**Cortex Crew**

- Soheil Norouzi
- Hasti Ebrahimzadeh
- Hamidreza Fathi
- Mahla Entezari
- Mohadese Jalili
- Fatemeh Ghanbari

Neuromatch Academy 2026 Final Project

TA: Dr. Jalaleddin Norouzi

Project TA: Amritmay Biswas

Mentor: Prof. Linda Katona :contentReference[oaicite:5]{index=5}

---

# Citation

If you use this repository, please cite the original dataset and the associated publications.

```bibtex
@misc{zhong2025,
  title={Generalization of V1 Signals Between Supervised and Unsupervised Learning},
  author={Zhong et al.},
  year={2025}
}
```

---

# Acknowledgements

This work was completed as part of the **Neuromatch Academy Computational Neuroscience Program**, combining neuroscience, machine learning, and large-scale neural data analysis.

Special thanks to the Neuromatch Academy organizers, instructors, mentors, and teaching assistants for providing the dataset and educational resources.

---

# Author

## Soheil Norouzi

Biomedical Engineering • Artificial Intelligence • Computational Neuroscience

**Research Interests**

- AI for Healthcare
- Medical Signal Processing
- Brain-Computer Interfaces
- Computational Neuroscience
- Deep Learning
- Machine Learning
- Neural Representation Learning

📫 Feel free to connect through GitHub or LinkedIn!

---

## License

This repository is released under the MIT License.
