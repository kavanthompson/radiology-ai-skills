# Radiology AI Skills

**Curated high-value AI agent skills for radiology residents and physicians.**

Maintained by **Dr. Kavan R. Thompson, D.O.** (PGY-3 Diagnostic Radiology, HCA Florida / USF Morsani)

This repository collects and organizes the most useful agent skills for:
- Structured radiology reporting & TemplateGuards
- ABR Core Exam mastery & study systems
- ResidentShield-style ambient teaching
- Clinical AI assistants and image analysis
- Research / academic productivity

## Included Skills (Ready for Claude Code, Cursor, Grok)

### 1. book-to-skill
Converts any technical book or PDF (Core Radiology, Requisites, ABR guides, papers) into a structured, reusable agent skill.  
**Use when**: Building living knowledge bases from textbooks for ABR Core Mastery.

Source: https://github.com/virgiliojr94/book-to-skill

### 2. medgemma-radiology (from med-guide)
Analyzes X-ray, CT, MRI, and DICOM images with clear explanations.  
**Use when**: Image interpretation support, teaching cases, or ResidentShield micro-learning.

Source: https://github.com/burakcanpolat/med-guide

### 3. medgemma-assistant (from med-guide)
Lab results, drug interactions, symptom evaluation, clinical assistant functions.

## How to Use with Claude Code / Cursor
```bash
# Clone this repo
git clone https://github.com/kavanthompson/radiology-ai-skills.git
cd radiology-ai-skills

# For Claude Code
cp -r curated/* ~/.claude/skills/

# Or clone the full original packages for more complete functionality
```

## How to Use with Grok
The skills follow the standard SKILL.md format. You can reference this repo or copy the curated folders into your Grok skills directory.

## Recommended Additional Repos (Star & Explore)
- https://github.com/Aperivue/medsci-skills — Built by a radiology resident (22 research automation skills)
- https://github.com/Open-Medica/open-medical-skills — Physician-reviewed medical AI skill marketplace
- https://github.com/2023Anita/clinical-ai-agent-skills — Evidence-first clinical agent rules
- https://github.com/mk-runner/Awesome-Radiology-Report-Generation — Best curated list for report generation research

## Related Projects by the Maintainer
- [TemplateGuards](https://github.com/kavanthompson/TemplateGuards) – PACS template / structured reporting tool
- [ABR-Core-Mastery](https://github.com/kavanthompson/ABR-Core-Mastery) – Comprehensive Core Exam study system

---
*Initialized 2026-08-19. Skills are being actively curated for maximum clinical and educational utility.*