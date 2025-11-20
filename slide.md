---
marp: true
theme: default
paginate: true
footer: "Contact: 21f3000473@ds.study.iitm.ac.in"
---

<!--
_customTheme: |
  :root {
    --primary: #0b67a3;
    --accent: #ff7a59;
    --muted: #6b7280;
  }
  section {
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Arial;
  }
  h1 {
    color: var(--primary);
  }
  .tip-box {
    padding: 12px;
    border-radius: 10px;
    background: rgba(0,0,0,0.06);
  }
-->

# Product Documentation — SDK v1.2

Author: Paresh  
Email: **21f3000473@ds.study.iitm.ac.in**

---

<!--
background: url('assets/test-bg.png')
background-size: cover
background-position: center
class: lead
-->

# Overview

This slide uses a background image stored entirely inside WSL.  
(Place your image in `~/marp-slides/assets/`)

---

## Goals

- One-file documentation maintained in Git  
- Built using Marp CLI inside WSL  
- Exportable to PDF, HTML and PPTX  
- Easy to version, review and maintain  

---

## How to build inside WSL

```bash
npm i -g @marp-team/marp-cli

# Preview
marp --preview slides.md

# Export PDF
marp slides.md -o slides.pdf
