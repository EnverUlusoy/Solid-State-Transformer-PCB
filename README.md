# Solid-State Transformer — PCB 3D Viewer

An interactive web page for viewing the PCB design of a digitally controlled, two-stage Solid-State Transformer (SST) prototype in 3D.

🔗 **Live demo:** https://kullaniciadin.github.io/pcb-portfolio/

## About the Project

A 1 kW two-stage SST prototype consisting of:
- **Input stage:** Boost PFC rectifier
- **Isolation stage:** Isolated phase-shifted full-bridge (PSFB) DC/DC converter
- **Control:** STM32-based digital control with four cascaded PI control loops
- **DC link / output voltage:** 360V → 48V

This work was accepted for oral presentation at **icSmartGrid 2026** (14th International Conference on Smart Grid, Suceava, Romania).

## Result Metrics

| Metric | Value |
|---|---|
| Power Factor | 0.9954 |
| THD | 3.68% |
| Efficiency | ~94% |

## Tools Used

- **KiCad** — PCB design and STEP export
- **OpenCASCADE / OCP** — mesh generation from the STEP file
- **glTF-Transform** — model optimization (Draco compression)
- **`<model-viewer>`** (Google) — interactive 3D viewing in the browser
- **GitHub Pages** — hosting

## Running Locally

Clone the repo and open `index.html` in any browser (or serve it with a simple local server: `python3 -m http.server`).

---
Gazi University, Electrical-Electronics Engineering — Senior Design Project
