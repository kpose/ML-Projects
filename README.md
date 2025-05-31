# ML Projects

This repository contains a collection of machine learning projects, showcasing model training, evaluation, and deployment workflows using various tools and frameworks.

## Contents

- `linear-regression/`: Implementation of a simple linear regression model for predictive analysis using scikit-learn and NumPy.

## Prerequisites

- Python 3.7+
- A [Kaggle](https://www.kaggle.com/) account

---

## Installation

1. **Clone the repository** and install dependencies:

```
git clone https://github.com/kpose/ML-Projects.git
cd ML-Projects
pip install -r requirements.txt
```

Set up Kaggle API access:

Go to https://www.kaggle.com/account
Scroll to the API section and click "Create New API Token"

This downloads a kaggle.json file
Place the API key in the correct directory:


```
mkdir -p ~/.kaggle
mv /path/to/kaggle.json ~/.kaggle/
chmod 600 ~/.kaggle/kaggle.json
```