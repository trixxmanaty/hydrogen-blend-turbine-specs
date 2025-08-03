# Hydrogen-Blend Turbine Specs

> **Open dataset of industrial gas-turbine models capable of firing up to 100 % hydrogen, RNG or biogas.**

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Last Update](https://img.shields.io/github/last-commit/your-github-handle/hydrogen-blend-turbine-specs?color=brightgreen)](../../commits/main)

---

## About

This repository contains machine-readable specifications for current and legacy gas-turbine frames that have documented hydrogen blend capabilities.  
Data points include model name, OEM, nominal power output (MW), max H₂ blend %, NO<sub>x</sub> emissions (ppm), efficiency, inlet temperature, and retrofit kit availability.

The dataset underpins comparative tools and payback calculators published at **[GreenGasTurbines.com](https://www.greengasturbines.com/)** 

* 650 MW of hydrogen-ready capacity tracked  
* > 70 turbine variants across 8 OEMs  
* Released under MIT for academic & commercial use

---

## File Structure

| File | Format | Description |
|------|--------|-------------|
| `turbine-specs.csv` | CSV | Flat table, one row per model |
| `turbine-specs.json` | JSON | Same data, array of objects |
| `schema.json` | JSON-Schema | Field definitions & types |
| `examples/` | | Jupyter notebook & curl examples |
| `LICENSE` | | MIT |

### Quick peek

```csv
model,oem,power_mw,max_h2_pct,efficiency_pct,mono_nox_ppm,retrofit_ready
Frame 5 NL,GE Vernova,30,100,38,15,yes
LM2500+G4,GE Vernova,34,50,39,25,yes
SGT-800 50 Hz,Siemens Energy,54,75,41,9,no
...
