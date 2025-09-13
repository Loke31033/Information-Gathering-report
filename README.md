# Inlighntech — Information Gathering Report

**Target:** `inlighntech.com`  
**Author:** Lokeshwar V
**Date:** 2025-09-13

## Summary
This repository contains passive and authorized active reconnaissance outputs for `inlighntech.com`. It includes the final report, screenshots, and raw command outputs.

## Contents
- `REPORT.md` — full report in markdown (convertible to PDF)
- `Inlighntech_Report.pdf` — final PDF (if present)
- `screenshots/` — evidence images
- `outputs/` — raw command outputs (whois, dig, amass, etc.)
- `scripts/` — any scripts used to collect results

## How to build the PDF locally
Requires `pandoc` and a TeX engine (e.g., texlive, xelatex).

```bash
pandoc REPORT.md -o Inlighntech_Report.pdf --pdf-engine=xelatex
