# An Empirical Constraint on Structure-Dynamics Coupling in Disk Galaxies

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.CONCEPTDOI.svg)](https://doi.org/10.5281/zenodo.CONCEPTDOI)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

Zenodo DOI: https://doi.org/10.5281/zenodo.18603520 

**Author:** [Author Name]  
**Reproducibility package 
**Category:** Galaxies and Cosmology

---

## Abstract

We identify an **empirical separation constraint** between global structural properties of disk galaxies and local RAR residuals. Using the SPARC database (*N* = 116), we test whether mass-independent compactness predicts residuals about the Radial Acceleration Relation (RAR) in a protocol-independent manner.

**Key Result:** Under kinematically tuned mass models, compactness correlates with RAR residuals (*r* = 0.49, slope = 0.34). Under fixed mass-to-light ratios, this correlation amplitude is reduced by **≥85-90%**, placing a stringent upper bound on any direct coupling.

> **The trend is erased, not smudged.**

---

## The Constraint

| Parameter | Value |
|-----------|-------|
| **Upper bound on coupling** | ≤10-15% of tuned signal |
| **Slope collapse** | 0.34 → 0.04 (88% reduction) |
| **Expected from noise** | ~20% attenuation |
| **Observed** | ~88% suppression |

This constraint applies to:
- Residuals of the instantaneous acceleration field
- Protocol-independent inference
- Late-type, rotationally supported galaxies

---

## Repository Structure

```
.
├── README.md                 # This file
├── FINAL_CHECKLIST.md        # Submission compliance checklist
├── LICENSE                   # CC BY 4.0
├── CITATION.cff              # Citation metadata
├── zenodo.json               # Zenodo archive metadata
├── .gitignore
│
├── manuscript/
│   ├── manuscript.pdf        # Main manuscript
│   └── cover_letter.txt      # ApJ submission letter
│
├── figures/
│   ├── Figure1_PCA_Manifold.pdf
│   ├── Figure2_Identifiability.pdf
│   ├── Figure3_WISE_Validation.pdf
│   └── FigureA1_Population_Context.pdf
│
└── data/
    ├── data_fingerprints.json
    └── P_FIG2_VALIDATION.csv
```

---

## Key Figures

### Figure 2: The Ghost Line Test

The core result. Panel B shows the tuned correlation (*r* = 0.49, slope = 0.34). Panel C shows the control where the correlation collapses (*r* = 0.12, slope = 0.04).

**The dashed "ghost line"** represents the slope expected if the signal were physical but obscured by noise. Its absence in the data indicates **suppression rather than dilution**.

### Figure 3: WISE Cross-Validation

Spearman ρ = 0.98 confirms that SPARC and WISE see the same structural hierarchy. The +0.10 dex offset is expected from bandpass physics (Meidt et al. 2014).

> "For covariance analyses, ranking stability is the decisive criterion."

---

## Data Fingerprints (SHA-256)

All values are locked for reproducibility:

| File | SHA-256 (first 16 chars) |
|------|--------------------------|
| `SPARC_Canonical123.csv` | `3657c3e58c08bba5` |
| `P_FIG2_VALIDATION.csv` | `360826ee0092d66c` |
| `WISE_matched_lambda.csv` | `e4c617940c2db9bb` |

---

## Locked Statistics

| Parameter | Fingerprint Value | Manuscript |
|-----------|-------------------|------------|
| N (analysis) | 116 | 116 |
| PC1 variance | 65.914% | 65.9% |
| PC2 variance | 15.453% | 15.5% |
| Cumulative | 81.367% | 81% |
| Tuned *r* | 0.4917 | 0.49 |
| Tuned slope | 0.3354 | 0.34 |
| Control *r* | 0.1185 | 0.12 |
| Control slope | ~0.04 | 0.04 |
| WISE ρ | 0.9831 | 0.98 |
| WISE offset | +0.1029 dex | +0.10 dex |
| MAD | 0.1207 dex | 0.12 dex |

---

## The Defense Matrix

| Attack | Defense | Evidence |
|--------|---------|----------|
| "Noise washed out signal" | Ghost line + slope collapse | 88% > 20% expected |
| "Bad methodology" | Requisite isolation control | Bell & de Jong 2001 cited |
| "Bad data" | Ranking stability | ρ = 0.98 |
| "Weird sample" | xGASS population overlay | Appendix A |
| "Lack of power" | Injection test | Appendix B |
| "Denying gravity" | Scoped to residuals | §6.1 clarification |

---

## Citation

If you use this research, please cite:

```bibtex
@article{author2026constraint,
  author = {{Author}},
  title = {An Empirical Constraint on Structure-Dynamics Coupling in Disk Galaxies},
  journal = {The Astrophysical Journal Letters},
  year = {2026},
  volume = {},
  pages = {},
  doi = {}
}
```

See `CITATION.cff` for machine-readable citation metadata.

---

## References

- Bell, E. F., & de Jong, R. S. 2001, ApJ, 550, 212
- Catinella, B., et al. 2018, MNRAS, 476, 875
- Lelli, F., McGaugh, S. S., & Schombert, J. M. 2016, AJ, 152, 157
- Lelli, F., McGaugh, S. S., Schombert, J. M., & Pawlowski, M. S. 2017, ApJ, 836, 152
- McGaugh, S. S., Lelli, F., & Schombert, J. M. 2016, PhRvL, 117, 201101
- Meidt, S. E., et al. 2014, ApJ, 788, 144

---

## License

This work is licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).

---

## Acknowledgments

This research made use of:
- The SPARC database (Lelli et al. 2016)
- The xGASS representative sample (Catinella et al. 2018)
- WISE photometry (Wright et al. 2010)
