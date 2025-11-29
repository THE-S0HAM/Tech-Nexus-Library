# Tech-Nexus

![Status](https://img.shields.io/badge/Status-Active-success) ![License](https://img.shields.io/badge/License-MIT-blue) ![PRs](https://img.shields.io/badge/PRs-Welcome-brightgreen)

The central convergence point for technical articles, roadmaps, and deep-dives into DevOps, Cloud Architecture, AI/ML, Cybersecurity, and emerging tech trends.

This repository is organized as a knowledge hub where each top-level folder groups focused content and guides. Use this page as the home dashboard to find domains, templates, and contribution guidance.

**Quick Links**

- **Contributing guide:** `CONTRIBUTING.md`
- **Article template:** `TEMPLATES/article_template.md`
- **Repository script:** `scripts/create_structure.sh` (kept locally; ignored by git)
- **.gitignore:** `.gitignore`

**Table of Contents**

- [DevOps & SRE](#devops--sre)
- [Cloud Architecture](#cloud-architecture)
- [Artificial Intelligence & ML](#artificial-intelligence--ml)
- [Cybersecurity](#cybersecurity)
- [Web Development](#web-development)
- [Trends & Analysis](#trends--analysis)
- [How to contribute](#how-to-contribute)
- [Host on GitHub Pages](#host-on-github-pages)

---

## DevOps & SRE

Path: `01-DevOps-Engineering/`

Focus: CI/CD, Kubernetes, Docker, Terraform, Observability, and SRE best practices.

- Browse the folder: `01-DevOps-Engineering/`
- Quick subfolders created: `Docker/`, `Kubernetes/`, `Terraform/`, `CI-CD/`, `Observability/`, `SRE/`

## Cloud Architecture

Path: `02-Cloud-Architecture/`

Focus: Multi-cloud architecture, AWS/Azure/GCP guides, Serverless, Cost optimization, and Cloud security.

- Browse the folder: `02-Cloud-Architecture/`
- Quick subfolders created: `AWS/`, `Azure/`, `GCP/`, `Serverless/`, `Cost-Optimization/`, `Cloud-Security/`

## Artificial Intelligence & ML

Path: `03-Artificial-Intelligence/`

Focus: GenAI, MLOps, Data Engineering, Computer Vision, NLP, Model deployment and practical patterns.

- Browse the folder: `03-Artificial-Intelligence/`
- Quick subfolders created: `GenAI/`, `MLOps/`, `Data-Engineering/`, `Computer-Vision/`, `NLP/`, `Model-Deployment/`

## Cybersecurity

Path: `04-Cybersecurity/`

Focus: DevSecOps, Network security, Application security, Compliance, Incident response and threat modeling.

- Browse the folder: `04-Cybersecurity/`
- Quick subfolders created: `DevSecOps/`, `Network-Security/`, `Application-Security/`, `Compliance/`, `Incident-Response/`, `Threat-Modeling/`

## Web Development

Path: `05-Web-Development/`

Focus: Frontend, backend, performance, accessibility, developer tools and web security best practices.

- Browse the folder: `05-Web-Development/`
- Quick subfolders created: `Frontend/`, `Backend/`, `DevTools/`, `Performance/`, `Accessibility/`, `Web-Security/`

## Trends & Analysis

Path: `99-Trends-and-Analysis/`

Focus: Web3, Edge computing, Quantum, industry reports and future-looking research.

- Browse the folder: `99-Trends-and-Analysis/`
- Quick subfolders created: `Web3/`, `Edge-Computing/`, `Quantum/`, `Industry-Reports/`

---

## How to contribute

1. Fork the repository and create a branch: `git checkout -b topic/your-article-name`
2. Use the article template at `TEMPLATES/article_template.md` for new content
3. Add your `.md` file under the appropriate folder (for example: `01-DevOps-Engineering/Kubernetes/your-article.md`)
4. Commit, push, and open a Pull Request

Frontmatter example (required):

```yaml
---
title: "The Future of Kubernetes"
category: "DevOps"
tags: [k8s, containerization, orchestration]
last_updated: 2025-11-29
---
```

See `CONTRIBUTING.md` for full contribution guidelines.

## Host on GitHub Pages

This repository's `README.md` can serve as the site homepage for GitHub Pages. To publish:

1. Go to your repository on GitHub → `Settings` → `Pages`.
2. Under **Source**, choose `Branch: main` and `Folder: / (root)` and click **Save**.

Alternatively, you can create a `docs/` folder and select `Branch: main` and `Folder: /docs` to serve a more customized site. If you want a different theme or static site generator, add a `docs/` site or a `gh-pages` workflow.

## Scripts and automation

- `scripts/create_structure.sh` — helper script to create this folder layout locally. The script is ignored in git to allow maintainers to keep a personal copy executable.

Run locally (from repo root):

```bash
bash scripts/create_structure.sh
```

---

If you'd like, I can also generate an index page for each top-level folder that lists its articles automatically. Would you like me to add auto-index generation and a GitHub Actions workflow to publish the site?

