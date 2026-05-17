# 🎓 Git & GitHub Version Control Workflow Lab

<p align="center">
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git" />
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
</p>

## 📌 Project Overview
This repository serves as a practical, hands-on laboratory designed to validate and showcase my core competencies in modern version control tracking and distributed workflows. As part of my career acceleration path in technology and data, this workspace documents the structural simulation of real-world development lifecycle operations.

The core objective is to master clean repository architecture, deployment patterns, and synchronization pipelines from local environments to production-ready remote structures.

---

## ⚡ Core Skills Validated
Through this lab, I have successfully put into practice the following architectural patterns:
* **Repository Architecture:** Initializing metadata environments, mapping local system work trees (`git init`), and binding upstream remote hubs (`git remote add origin`).
* **Branching Strategy:** Isolating features via secondary pointers to safe work environments without affecting the primary production branch (`main`).
* **State Verification & Inspection:** Tracking internal file mutations, staging areas, and deleted node tracking via condensed reporting matrices (`git status -s`).
* **Context Preservation (Stashing):** Temporarily shelve uncommitted codebases to switch active branches without loss of internal logic vectors.
* **Integration Patterns:** Resolving downstream dependencies by fast-forwarding and merging experimental tracks (`git merge`) back into mainline deployment vectors.

---

## 🛠️ The Tech Stack & Lab Logic

### 🚀 Feature Matrix Lifecycle
> 💡 *This visual breakdown maps how features are isolated in development branches before hitting the production main-line.*

```text
  [ main ]  🏁 Baseline Setup ➔ (calculadora.py initialized)
     │
     └───➔ [ branch: feature-subtraction ] 🧪 Isolated Sandbox
                 │
                 └───➔ 🛠️ Code Modification (Appended logic)
                             │
                             ✔ Verified & Tested
                                   │
  [ main ]  🔄 git merge 🤹 Combined Vector ➔ 🚀 Production Ready
