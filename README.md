# 🚀 CI/CD Practice with GitHub Actions (DevOps Hands-on)

![CI](https://img.shields.io/github/actions/workflow/status/jainilgupta02/ci-cd-2/main.yml?branch=main)
![Python](https://img.shields.io/badge/python-3.9%2B-blue)
![License](https://img.shields.io/badge/license-MIT-green)
![Status](https://img.shields.io/badge/status-active-success)

This repository demonstrates a **complete CI/CD pipeline** using **GitHub Actions, YAML, and Python**.  
It is built as part of my **DevOps & Cloud Computing course (PW Skills)** and strengthened with **industry-style best practices**.

---

## 📌 Project Overview

The goal of this project is to simulate a **real-world DevOps pipeline**:

✔ Build  
✔ Test  
✔ Package  
✔ Deploy (simulated)  
✔ Upload artifacts  

Every push to `main` automatically triggers the pipeline.

---

## 📂 Project Structure
```text
ci-cd-2/
│
├── app/
│ └── calculator.py # Application logic
│
├── test/
│ └── test_calculator.py # Pytest unit tests
│
├── .github/
│ └── workflows/
│ └── main.yml # CI/CD pipeline
│
├── requirements.txt
├── README.md
├── LICENSE
└── .gitignore
```

---

## 🧮 Calculator Features

The application is a **full basic calculator**:

| Operation | Function |
|------------|----------|
| Addition | `add(a, b)` |
| Subtraction | `subtract(a, b)` |
| Multiplication | `multiply(a, b)` |
| Division | `divide(a, b)` |

---

## 🧪 Unit Testing (pytest)

Tests are written using `pytest` and run automatically in CI.

Run locally:
```bash
pip install -r requirements.txt
pytest
