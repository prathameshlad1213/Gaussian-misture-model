# Gaussian-misture-model
# 🎯 Gaussian Mixture Model (GMM) for Generative AI

This project demonstrates how to implement and visualize a **Gaussian Mixture Model (GMM)** for generative modeling using **Python (scikit-learn)** in a **Google Colab** environment.

---

## 📌 Overview

Gaussian Mixture Models are powerful unsupervised learning techniques that model data as a mixture of multiple Gaussian distributions. In this project, we:

- Generate synthetic 2D data from 3 different Gaussian distributions.
- Fit a GMM to model this data.
- Visualize clusters, means, covariances, and weights.
- Generate **new synthetic samples** from the learned distribution.
- Visualize each component's Gaussian ellipse with proper weight and spread.

---

## 🚀 Run in Google Colab

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/)

---

## 🧠 Concepts Covered

- Gaussian Mixture Model (GMM)
- Expectation Maximization (EM)
- Covariance matrix interpretation
- Generative modeling
- Visualizing multivariate Gaussians with ellipses

---

## 📁 Files

| File Name        | Description                             |
|------------------|-----------------------------------------|
| `gmm_colab.ipynb` | Colab notebook with full code           |
| `README.md`       | Project documentation                   |

---

## 📊 Sample Output

![GMM Ellipse Visualization](assets/gmm_visualization.png)

> The red ❌ marks represent the mean of each Gaussian.  
> The ellipses show the shape (covariance) and transparency (weight) of each component.

---

## 🔧 Requirements

This runs entirely in **Google Colab**, but if running locally, install:

```bash
pip install numpy matplotlib scikit-learn
