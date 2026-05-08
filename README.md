# ARMA SDC 2026 — Hydraulic Fracture / Natural Fracture Interaction

A three-dimensional numerical investigation of hydraulic fracture (HF) interaction with planar natural fractures (NF) in unconventional reservoirs. Submission to the **ARMA 2026 Student Design Competition** by Team Orange.

**Institution:** Heriot-Watt University, Aktobe Campus, Kazakhstan  
**Programme:** BEng Petroleum Engineering, Year 1

## Authors

- **Aissugur Kurganbekov**
- **Alikhan Gibadullayev**

## Summary

This work explores how three governing parameters control the outcome of hydraulic fracture interaction with natural discontinuities:

1. **Minimum horizontal stress (σ₃)** — sets differential horizontal stress and the driving force for crossing
2. **Natural fracture cohesion** — sets resistance to NF shear reactivation
3. **HF–NF intersection angle** — sets the resolved shear-to-normal stress ratio at the intersection

Three lattice-DEM simulations were completed in **XSite v4.0** (Itasca Consulting Group, 2025) on a 400 × 300 × 150 m reservoir block with a horizontal wellbore and a single planar natural fracture. The remaining four parametric cases were predicted analytically using the criteria of Renshaw and Pollard (1995) and Gu and Weng (2010), calibrated against the simulated cases.

## Key findings

- **Intersection angle** is the strongest control of the HF–NF interaction mode
- **σ₃ (differential stress)** is the second strongest control
- **NF cohesion** is a second-order modulator that reinforces but does not override the regime selected by stress and angle
- Diagnostic indicators (peak fluid pressure, fluid-node count, microcrack distribution) reliably distinguish crossing from diversion regimes

## Application

Findings are framed for hydraulic-fracturing design in fractured tight reservoirs of the **Pre-Caspian Basin, western Kazakhstan**, where overpressured carbonate and tight-clastic intervals carry pre-existing natural fracture networks of varying orientation.

## Tools and methods

- **XSite v4.0** — lattice-based Distinct Element Method (DEM) simulator (Itasca Consulting Group)
- **Analytical criteria:**
  - Renshaw, C. E. and Pollard, D. D. (1995). *Int. J. Rock Mech. Min. Sci.*, 32(3), 237–249
  - Gu, H. and Weng, X. (2010). *44th US Rock Mechanics Symposium*, ARMA 10-198

## Report

The full technical report is available here: [ARMA_SDC_2026_Report_TeamOrange.pdf](ARMA_SDC_2026_Report_TeamOrange.pdf)

## Citation

If referencing this work, please cite:

> Kurganbekov, A. and Gibadullayev, A. (2026). *3D Lattice-DEM Investigation of Hydraulic Fracture–Natural Fracture Interaction*. ARMA Student Design Competition 2026, Team Orange. Heriot-Watt University, Aktobe Campus.

## License

Academic and educational use. The technical report is the intellectual property of the authors.
