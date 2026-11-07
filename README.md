# Week 8 — Intro to Data Course

This repository contains the materials for **Week 8** of *Intro to Data Course*.  
- Slides: see [`slides/`](./slides/) folder  
- Notebooks: see [`notebooks/`](./notebooks/) folder 
---

## 📑 Session Outline

This session explores two key aspects of building effective classification models: **model evaluation** and **ensemble learning**.

We begin by looking at how to evaluate and compare classification models fairly, focusing on:
- Train, validation, and test splits, and avoiding data leakage.
- The confusion matrix and key evaluation metrics: accuracy, precision, recall, and F1-score.
- K-fold cross-validation and Scikit-learn Pipelines.

The second half introduces **ensemble learning** and how combining multiple models can improve predictive performance. We explore three main approaches:
- **Bagging:** Bootstrap aggregating and Random Forests.
- **Boosting:** AdaBoost and Gradient Boosting.
- **Stacking and Voting:** Combining different models to make predictions.

The session includes two notebooks for gaining hands-on experience in evaluation and ensemble models.

---
## 🚀 Environment Setup

Before starting, please **fork this repository** and create a fresh Python virtual environment.  
All required libraries are listed in `requirements.txt`.

> ⚠️ If you encounter errors during `pip install`, try removing the version pinning for the failing package(s) in `requirements.txt`.  
> On Apple M1/M2 systems you may also need to install additional system packages (the “M1 shizzle”).

---

### macOS / Linux (bash/zsh)

```bash
# Select Python version (if using pyenv)
pyenv local 3.11.3

# Create and activate virtual environment
python -m venv .venv
source .venv/bin/activate

# Upgrade pip and install dependencies
pip install --upgrade pip
pip install -r requirements.txt
```

### Windows (PowerShell)
```bash
# Select Python version (if using pyenv)
pyenv local 3.11.3

# Create and activate virtual environment
python -m venv .venv
.venv\Scripts\Activate.ps1

# Upgrade pip and install dependencies
python -m pip install --upgrade pip
pip install -r requirements.txt
```

### Windows (Git Bash)
```bash
# Select Python version (if using pyenv)
pyenv local 3.11.3

# Create and activate virtual environment
python -m venv .venv
source .venv/Scripts/activate

# Upgrade pip and install dependencies
python -m pip install --upgrade pip
pip install -r requirements.txt
```

You’re now ready to run the session notebooks!

Deactivate the environment when you’re done:
```bash
deactivate
```
