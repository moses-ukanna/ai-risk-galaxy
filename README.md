# AI Risk Galaxy -- Interactive Constellation Map

An interactive visualisation that maps AI system risks as a glowing constellation. Built for cybersecurity professionals assessing AI-enabled insider threat detection systems against the EU AI Act and UK GDPR.

## What It Does

Transforms risk scoring data into a spatial, interactive galaxy where each risk area (Privacy, Accuracy, Bias, Accountability, Transparency, Human Factors, Security, Legal) appears as a glowing node connected by luminous chains. Click any node to expand it and explore individual risks, regulatory obligations, and suggested mitigations.

**Scoring Formula:** `Weighted Score = Likelihood × Impact × Regulatory Weight`

| Regulation | Weight | Rationale |
|---|---|---|
| EU AI Act | 1.5x | Fines up to €35M or 7% global turnover |
| UK GDPR | 1.3x | Fines up to £17.5M or 4% turnover |
| HRA/ECHR | 1.2x | Fundamental rights implications |
| UK Employment Law | 1.1x | Tribunal claims, unfair dismissal |
| RIPA/IPA | 1.1x | Lawful interception requirements |

## Features

- Animated starfield background with parallax scrolling
- Colour-coded severity: Critical (red), High (amber), Medium (yellow), Low (green)
- Expandable nodes showing individual risks with chain connections
- Regulatory obligation mapping per risk area
- Suggested mitigation summaries
- Fully responsive (mobile + desktop)
- Zero dependencies — Python standard library only

## How to Run

```bash
python risk_galaxy.py
```

Opens automatically in your default browser. Also works in:

- **Google Colab** — paste and run, renders inline
- **Jupyter Notebook** — paste and run, renders inline
- **Any terminal** — saves temp HTML and opens browser

## Requirements

- Python 3.6+
- No external packages needed

## Context

Built as an automation artefact for a cybersecurity portfolio analysing an AI-enabled insider threat detection system. Supports governance communication by making complex risk landscapes accessible to non-technical stakeholders, aligning with EU AI Act Article 13 transparency requirements.

## License

MIT
