# MSRMF - Multi-Site Robotic Release Management Framework

**Reference implementation of a gated release-governance framework for distributed robotic and industrial automation systems.**

The MSRMF (Multi-Site Robotic Release Management Framework) is a decision-support methodology designed to improve release governance for engineering changes deployed across multiple operational sites.

This repository contains the reference implementation used during pilot evaluations and research activities.

---

## Overview

Managing engineering changes across distributed automation environments presents unique challenges.

Unlike traditional software-only deployments, changes in robotic systems may affect physical equipment, operational continuity, safety, and multiple production sites simultaneously.

The MSRMF addresses this problem through a structured release-governance process based on sequential decision gates:

1. **Gate 1 - Triage**
2. **Gate 2 - Validation**
3. **Gate 3 - Authorization**
4. **Deployment**
5. **Monitoring**
6. **Results & KPIs**

The framework emphasizes documented engineering decisions, controlled rollout strategies, rollback readiness, and release traceability.

---

## Features

- Engineering change triage
- Automatic priority scoring
- Structured release validation
- Rollback readiness checklist
- Multi-site deployment management
- KPI dashboard
- Release Health Index (RHI)
- Risk assessment engine
- Scenario simulation ("What-if")
- Knowledge base
- Pilot evaluation tracking
- Research & publications registry

---

## Purpose

This tool is intended as a **research prototype** and reference implementation.

Its objectives are to:

- demonstrate the MSRMF methodology;
- support pilot evaluations;
- collect structured feedback from engineering teams;
- provide a reproducible implementation for academic research.

It is **not** intended to replace engineering judgment or existing enterprise release-management platforms.

---

## Intended Users

The framework may be useful for organizations operating:

- warehouse automation systems
- autonomous mobile robots (AMRs)
- industrial robotics
- manufacturing automation
- distributed industrial software
- engineering release management teams

---

## Technology

Current implementation:

- HTML5
- CSS3
- Vanilla JavaScript
- [EmailJS](https://www.emailjs.com/) (client-side email delivery, optional)

Infrastructure:

- Hosted on GitHub Pages
- Deployed via GitHub Actions (CI/CD)

All computation is client-side. Data remains in the user's browser unless explicitly exported (JSON download) or shared (email send via EmailJS, which requires explicit user consent before transmission).

---

## Current Status

Current maturity:

**Pilot Prototype**

The implementation is being evaluated through academic research and independent pilot studies.

Future work includes:

- additional field validation
- usability improvements
- quantitative model refinement
- expanded KPI models
- optional enterprise integrations

---

## Publications

Related publications include:

- *A Phased Validation and Rollout Framework for Multi-Site Autonomous Warehouse Robotic Systems*
- Additional peer-reviewed papers currently under publication.

Publication details will be updated as they become publicly available.

---

## Research

This project originated from applied engineering practice and is currently being developed as part of ongoing research into release governance for distributed robotic systems.

Feedback from researchers, practitioners, and industrial organizations is welcome.

---

## License

This repository is provided for research and evaluation purposes.

Please contact the author before commercial use.

---

## Contact

**Livia Silveira Bezerra de Menezes**

Mechanical & Industrial Engineer

Project Manager - Industrial Automation

OIQ Licensed Engineer

GitHub Issues may be used for questions, suggestions, and bug reports:
https://github.com/LiviaSBM/msrmf-console/issues
