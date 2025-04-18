# Network Intrusion Data Visualization

A QT application for for visualizing netwrok intrusion data.  
It provides PCA, t-SNE, K-means clustering, bar/pie charts of attack labels, and a PyQt5 desktop app.

---

## Features

-   **PCA** - 3D scatter plots
-   **t-SNE** - 2D embeddings
-   **K-means** - cluster visualization
-   **Graphs** - bar or pie chart of attack-type distribution
-   **GUI** - PyQt5

---

## Installation

```bash
pip install pandas numpy scikit-learn matplotlib pyqt5
```

Requirements:

-   Python 3.8+
-   pandas, numpy, scikit-learn, matplotlib, pyqt5

---

## Usage

To launch the PyQt GUI:

```bash
python qt_gui.py
```

Steps:

1. Load CSV
2. Select analysis method (PCA, t-SNE, K-means, Graph)

---
