# Awesome Human Trust Calibration

A curated research repository on **Human Trust Calibration in Human–Agent Collaboration for Autonomous Research**. The repository connects an AI-assisted research paper and citation-integrity audit with independently verified scholarly literature, datasets, tools, implementations, and learning resources.

The central question is:

> **How can humans learn to trust autonomous research agents neither too much nor too little, so that human reliance matches the agent's demonstrated capability, uncertainty, and task risk?**

## Contents

- [Overview](#overview)
- [AI-Assisted Research Paper](#ai-assisted-research-paper)
- [Citation Integrity Audit](#citation-integrity-audit)
- [Survey and Review Papers](#survey-and-review-papers)
- [Foundational Papers](#foundational-papers)
- [Trust Calibration and Human-AI Collaboration](#trust-calibration-and-human-ai-collaboration)
- [Recent Research](#recent-research)
- [Autonomous Research and AI Agents](#autonomous-research-and-ai-agents)
- [Datasets](#datasets)
- [Tools and Libraries](#tools-and-libraries)
- [GitHub Implementations](#github-implementations)
- [Tutorials and Learning Resources](#tutorials-and-learning-resources)
- [Verification and Curation Policy](#verification-and-curation-policy)
- [Repository Structure](#repository-structure)
- [License](#license)

## Overview

Human trust calibration is the process of making a person's reliance on an automated or AI system appropriately match the system's actual capabilities and limitations. The goal is not to maximize trust. Instead, a well-calibrated human should rely on an AI system when it is likely to be correct and question or override it when it is likely to fail.

This issue becomes more important as AI systems move from simple assistance toward **human-agent collaboration** and **autonomous research**. A research agent may search literature, summarize evidence, generate hypotheses, write and execute code, analyze results, and coordinate several stages of a research workflow. These capabilities can improve research efficiency, but errors can also propagate across multiple steps. A fluent but incorrect literature summary, an unsupported claim, a fabricated citation, or an incorrect analysis can affect later decisions.

This repository therefore connects three research areas: **trust and reliance in automation**, **human-AI collaboration and trust calibration**, and **autonomous/agentic scientific research**. Important research directions include appropriate reliance, mental models of AI capability, uncertainty communication, provenance, adaptive oversight, explanation design, multi-agent systems, and evaluation of long-term human-agent collaboration.

The repository is intended as a reusable starting point for students and researchers studying when humans should trust, question, verify, or take control from AI research agents.

## AI-Assisted Research Paper

**Title:** Human Trust Calibration in Human–Agent Collaboration for Autonomous Research

The original AI-assisted paper was generated as part of Lab 1 and contains the research background, current approaches, challenges, research gaps, and proposed research agenda.

[View the AI-Assisted Research Paper](paper/AI_Assisted_Research_Paper.pdf)

> Upload your original Lab 1 paper PDF into the `paper/` folder using the exact filename `AI_Assisted_Research_Paper.pdf`.

## Citation Integrity Audit

The repository preserves the connection between the AI-generated paper and the citation audit performed in Lab 1.

The original paper contained **28 references**. A systematic sample of **10 references** was audited rather than selecting only suspicious-looking citations. The audit reported:

- 4 references: **Verified**
- 4 references: **Wrong metadata**
- 0 references: **Frankenstein**
- 0 references: **Fabricated**
- 2 references: **Identifier mismatch**
- **Authenticity Score: 77.5/100**
- **Pre-verification prediction accuracy: 80%**

The audit's most important lesson was that professional-looking AI citations should not be accepted without independent verification. The audit also identified a claim-citation problem: some bibliography entries were not actually cited in the main text.

[View Citation Integrity Audit](citation-audit/Citation_Integrity_Audit.pdf)

> Upload your completed Lab 1 audit PDF into `citation-audit/` using the exact filename `Citation_Integrity_Audit.pdf`.

## Survey and Review Papers

See [references/references.md](references/references.md) for the complete verified collection.

- Lee & See (2004) — *Trust in Automation: Designing for Appropriate Reliance* — foundational review of appropriate reliance.
- Hancock et al. (2011) — *A Meta-Analysis of Factors Affecting Trust in Human-Robot Interaction* — quantitative review of trust factors.
- Hoff & Bashir (2015) — *Trust in Automation: Integrating Empirical Evidence on Factors That Influence Trust* — three-layer trust model.
- Brzowski & Nathan-Roberts (2019) — *Trust Measurement in Human–Automation Interaction: A Systematic Review* — reviews measurement approaches.
- Visser et al. (2025) — *Trust, Distrust, and Appropriate Reliance in (X)AI* — conceptual clarification and empirical survey.
- Wang et al. (2024) — *A Survey on Large Language Model Based Autonomous Agents* — overview of autonomous-agent architectures.

## Foundational Papers

- Muir (1994) — theoretical foundation of trust and intervention in automation.
- Parasuraman & Riley (1997) — use, misuse, disuse, and abuse of automation.
- Jian et al. (2000) — empirical trust scale for automated systems.
- Bansal et al. (2019) — mental models and human-AI team performance.
- Amershi et al. (2019) — 18 guidelines for human-AI interaction.

## Trust Calibration and Human-AI Collaboration

- Wang, Pynadath & Hill (2016) — automatically generated explanations and trust calibration in human-robot teams.
- Okamura & Yamada (2020) — adaptive trust-calibration cues in human-AI collaboration.
- Benda et al. (2021) — appropriate reliance in AI decision support.
- Wagner & Robinette (2021) — limits of transparency for trust calibration.
- Naiseh et al. (2023) — explanation classes and trust calibration.
- Holland, Perry & Neyedli (2024) — trust, reliance, and dependence under changing automation reliability.
- Klingbeil, Grützner & Schreck (2024) — experimental evidence of AI over-reliance.
- Dogru & Krämer (2025) — expertise, trust, and self-confidence in appropriate reliance.
- Pearson et al. (2026) — recent evidence on human reliance on AI in decision making.

## Recent Research

Recent work is especially important because agentic AI and autonomous scientific systems are developing rapidly. This repository deliberately distinguishes established foundational work from recent papers and preprints.

Selected recent resources include:

- Visser et al. (2025) — trust, distrust, and appropriate reliance.
- Dogru & Krämer (2025) — appropriate reliance on AI decision support.
- Pearson et al. (2026) — human reliance on AI decision support.
- Farquhar et al. (2024) — semantic entropy for hallucination detection.
- Lu et al. (2024) — The AI Scientist.
- Gottweis et al. (2025) — AI co-scientist.

## Autonomous Research and AI Agents

Autonomous research creates a special trust-calibration problem because an agent can perform multiple dependent steps:

`Research goal → Literature search → Evidence synthesis → Hypothesis → Experiment → Analysis → Scientific claim`

A failure early in this chain can propagate into later stages. Relevant resources include:

- Wang et al. (2024) — survey of autonomous LLM agents.
- Lu et al. (2024) — The AI Scientist.
- Gottweis et al. (2025) — Towards an AI co-scientist.
- Farquhar et al. (2024) — hallucination and uncertainty detection.

## Datasets

At least three datasets are provided in [datasets/datasets.md](datasets/datasets.md). They focus on trust calibration, human-AI collaboration, and AI trust/reliance.

## Tools and Libraries

At least five tools/resources are curated in [tools/tools.md](tools/tools.md), including agent frameworks and scholarly metadata services useful for building or verifying autonomous research systems.

## GitHub Implementations

At least five existing implementations are evaluated in [implementations/github-repositories.md](implementations/github-repositories.md). Selection considers documentation, source-code availability, activity, examples, reproducibility, license, and relevance rather than star count alone.

## Tutorials and Learning Resources

Learning resources are collected in [tutorials/learning-resources.md](tutorials/learning-resources.md), including human-AI interaction guidance, agent-framework documentation, and scholarly search/metadata resources.

## Verification and Curation Policy

This repository follows these principles:

1. AI-generated references are treated as **candidate resources**, not as evidence of publication.
2. Scholarly papers are checked against publisher pages, DOI records, PubMed, ACM, IEEE, PLOS, Nature, arXiv, or other authoritative scholarly records where applicable.
3. The title, authors, year, venue, and DOI/identifier are checked before inclusion.
4. DOI links are preferred because they provide persistent identification.
5. Preprints are clearly identified as preprints and are not presented as peer-reviewed journal articles.
6. Copyrighted PDFs belonging to other authors are **not uploaded**. The repository links to the DOI, publisher, arXiv, PubMed, or official open-access source instead.
7. The repository contains only the student's own assignment PDFs in the `paper/` and `citation-audit/` folders.
8. Descriptions are written to explain why each resource is relevant rather than merely pasting URLs.

## Repository Structure

```text
awesome-human-trust-calibration/
├── README.md
├── paper/
│   └── AI_Assisted_Research_Paper.pdf
├── citation-audit/
│   └── Citation_Integrity_Audit.pdf
├── references/
│   └── references.md
├── datasets/
│   └── datasets.md
├── tools/
│   └── tools.md
├── implementations/
│   └── github-repositories.md
├── tutorials/
│   └── learning-resources.md
└── LICENSE
```

## License

The repository's original documentation and curation notes are released under the MIT License. External papers, datasets, software, trademarks, and other third-party materials remain subject to their own licenses and copyright terms.
