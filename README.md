<div align="center">

# 🦁 Quantile-Quantile (Q-Q) Plot — Normality Diagnostics Masterclass
### **Lindenwood University — Interactive Data Science & Machine Learning Masterclass**

[![Live Interactive Lab](https://img.shields.io/badge/Launch_Interactive_Lab-Live_Demo-C5B358?style=for-the-badge&logo=googlechrome&logoColor=black)](https://sagarkalauni.github.io/qq-plot/)
[![Course](https://img.shields.io/badge/Course-MTH_34500-000000?style=for-the-badge&logo=academia&logoColor=C5B358)](#)
[![Author](https://img.shields.io/badge/Faculty-Sagar_Kalauni,_M.S.-1E293B?style=for-the-badge&logo=github&logoColor=white)](https://github.com/SagarKalauni)

</div>

---

## 📖 Overview

An interactive diagnostic visualization for **Normal Quantile-Quantile (Q-Q) Plots**. Designed for Lindenwood University statistics and regression students to visually link distribution shapes (right/left skewness, leptokurtic heavy tails, platykurtic light tails, and bimodality) to their signature geometric patterns on a Q-Q plot.

> 🔗 **Launch the Live Interactive Application:** [**https://sagarkalauni.github.io/qq-plot/**](https://sagarkalauni.github.io/qq-plot/)

---

### 📐 Mathematical Formulation

Given ordered sample observations $x_{(1)} \le x_{(2)} \le \dots \le x_{(n)}$, the normal Q-Q plot pairs the $i$-th order statistic $x_{(i)}$ against the corresponding theoretical standard normal quantile $z_{(i)}$:

$$p_i = \frac{i - 0.5}{n}, \qquad z_{(i)} = \Phi^{-1}(p_i)$$

where $\Phi^{-1}(\cdot)$ is the probit function (inverse cumulative distribution function of $\mathcal{N}(0, 1)$). If the sample originates from $\mathcal{N}(\mu, \sigma^2)$, the points $(z_{(i)}, x_{(i)})$ lie approximately on the reference line:

$$x_{(i)} \approx \mu + \sigma z_{(i)}$$

---

## ✨ Key Interactive Features

- **Synchronized Density & Q-Q Canvas:** View the empirical histogram/KDE side-by-side with the live Q-Q plot.
- **Distribution Presets:** Instantly switch between Normal, Right-Skewed (Log-Normal/Exponential), Left-Skewed, Heavy-Tailed (Student's $t$ / Cauchy), and Uniform distributions.
- **Interactive Outlier Injection:** Drag or add points to see how tail departures bend the ends of the Q-Q curve.
- **Regression Residual Diagnostics:** Understand how to verify the $\varepsilon_i \sim \mathcal{N}(0, \sigma^2)$ assumption in OLS regression.

---

## 🎓 Pedagogical & Course Context

- **Institution:** Lindenwood University (*College of Science, Technology, and Health*)
- **Course Curriculum:** MTH 34500 — Regression Analysis & MTH 34200 — Probability & Mathematical Statistics II
- **Instructor & Author:** **Sagar Kalauni, M.S.** (*Full-Time Faculty in Data Science*)
- **Tech Stack:** HTML5, Tailwind CSS, **D3.js** (Dynamic Data Visualization), **MathJax** (LaTeX Mathematical Rendering), Vanilla ES6+ JavaScript (Zero-Dependency Client-Side Execution).

---

## 🚀 Running Locally

Because this visualizer is engineered as a self-contained, zero-build client-side application, you can run it immediately in any modern browser:

```bash
# Clone the repository
git clone https://github.com/SagarKalauni/qq-plot.git

# Navigate into the project directory
cd qq-plot

# Open index.html directly in your browser or serve locally:
python -m http.server 8000
```

---

## 🔗 Explore the Complete Interactive Masterclass Suite

| Module | Topic | Live Link |
| :--- | :--- | :---: |
| **Linear Regression** | Ordinary Least Squares & Residual Minimization | [Launch](https://sagarkalauni.github.io/linear-regression/) |
| **Logistic Regression** | Sigmoid Probabilities & Binary Cross-Entropy | [Launch](https://sagarkalauni.github.io/logistic-regression/) |
| **Regularization ($L_1 / L_2$)** | Lasso vs. Ridge Constraint Geometry | [Launch](https://sagarkalauni.github.io/Regularization/) |
| **K-Nearest Neighbors** | Instance-Based Learning & Distance Metrics | [Launch](https://sagarkalauni.github.io/knn/) |
| **Support Vector Machine** | Maximum-Margin Hyperplanes & Soft Margin $C$ | [Launch](https://sagarkalauni.github.io/support-vector-machine/) |
| **RBF Kernel SVM** | Non-Linear Kernel Trick & $(\gamma, C)$ Tuning | [Launch](https://sagarkalauni.github.io/rbf-kernel-svm/) |
| **Decision Tree (CART)** | Recursive Splitting, Gini & Entropy | [Launch](https://sagarkalauni.github.io/decision-tree/) |
| **Random Forest** | Bagging & Ensemble Variance Reduction | [Launch](https://sagarkalauni.github.io/random-forest/) |
| **Voting Classifier** | Hard Majority vs. Soft Probability Voting | [Launch](https://sagarkalauni.github.io/voting-classifier/) |
| **K-Means Clustering** | Lloyd's Algorithm, Voronoi & Elbow WCSS | [Launch](https://sagarkalauni.github.io/k-mean-clustering/) |
| **Confusion Matrix** | Precision, Recall, Specificity & $F_1$-Score | [Launch](https://sagarkalauni.github.io/confusion-matrix/) |
| **Confidence vs. Prediction Intervals** | Mean Response vs. Individual Uncertainty | [Launch](https://sagarkalauni.github.io/confidence-and-prediction-interval/) |
| **Bootstrapping** | Non-Parametric Resampling with Replacement | [Launch](https://sagarkalauni.github.io/bootstrap/) |
| **Q-Q Plot** | Gaussian Normality & Tail Diagnostics | [Launch](https://sagarkalauni.github.io/qq-plot/) |
| **Train-Test Split & CV** | Holdout Partitioning & $K$-Fold Cross-Validation | [Launch](https://sagarkalauni.github.io/split/) |
| **One-Hot Encoding** | Categorical Expansion & Dummy Variable Trap | [Launch](https://sagarkalauni.github.io/one-hot-encoding/) |

---

<div align="center">
  <sub>Developed with ❤️ for Data Science students by <a href="https://github.com/SagarKalauni">Sagar Kalauni</a> · <a href="https://sagarkalauni.github.io">Portfolio</a></sub>
</div>
