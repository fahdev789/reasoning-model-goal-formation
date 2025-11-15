# How Does a Reasoning Model Perform Its Goal Formation?

This repository contains the LaTeX source for the paper:

**“How Does a Reasoning Model Perform Its Goal Formation:  
Impact of Input Prompt and System Message on Final Output”**

Author: **Fahad Ali**  
Affiliation: Independent Researcher

---

## Overview

This work investigates how large language models internally form “goals” during reasoning and how variations in prompt clarity influence that goal formation. Using multiple prompt variations of a single legal case (Taylor Swift v. Evermore Park, 2021), the study examines how the model reorganizes its internal reasoning structure when the provided information is complete, partial, or ambiguous.

The analysis focuses on two meta-level components extracted from reasoning traces:

- **Meta-planning** — how the model identifies the task or implicit goal  
- **Meta-reasoning** — how the model constructs the steps to achieve that goal

The results show that the model follows stable internal patterns under clear prompts and shifts to alternative reasoning regimes when ambiguity increases.

---

## Files

- `main.tex` — arXiv-ready LaTeX source  
- `refs.bib` — bibliography file  
- `FahadAli_ScaleAI_Research_Goal_Formation_and_Prompt_Sensitivity.pdf`  

---

## Research Question

**What internal reasoning and goal-formation patterns remain stable across different contexts, and how do ambiguous prompts alter these patterns?**

---

## Citation (BibTeX)

```bibtex
@misc{ali2025goalformation,
  title={How Does a Reasoning Model Perform Its Goal Formation: Impact of Input Prompt and System Message on Final Output},
  author={Fahad Ali},
  year={2025},
  note={Independent Researcher},
}
