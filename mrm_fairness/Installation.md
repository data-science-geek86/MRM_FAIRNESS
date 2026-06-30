# 📦 Installation Guide: Bias Audit & Fairness Engine

This guide provides step-by-step instructions for installing the **Bias Audit & Fairness Assessment Engine** and its necessary dependencies. 
Follow these instructions to set up your environment for production usage or local development.

---

## 📋 Prerequisites

Before installing, ensure you have the following requirements met:
* **Python**: Version `3.8` or higher is recommended.
* **pip**: Python package installer (updated to the latest version).

The core dependencies that will be installed automatically include:
* `numpy` 
* `pandas` 
* `plotly` 
* `scikit-learn`

---

## 🚀 1. Standard Installation via PyPI

For most users, the standard and stable version can be installed directly from PyPI using `pip`. Run the following command in your terminal or command prompt:

```bash
pip install mrm_fairness_auditor
```

## 🛠️ 2. Installation from GitHub (Development Version)
If you wish to work with the latest features, contribute to development, or run the engine locally from source, you can install directly from the version control repository.

### Install Directly via pip and Git
You can point pip directly to the remote repository without downloading it manually:

``` bash

pip install git+https://github.com/data-science-geek86/MRM_FAIRNESS.git#subdirectory=mrm_fairness

```
