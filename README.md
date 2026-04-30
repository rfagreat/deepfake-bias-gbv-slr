# Deepfakes as Gendered Weapons

## A Systematic Literature Review Bridging Face-Swap Detection Bias, Platform Failures, and Gender-Based Violence

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1K8pJ_tOygUWOOKeeCUjPZNn9dx9n7fkE#scrollTo=c1)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
[![Studies](https://img.shields.io/badge/Verified%20Studies-48-blue.svg)]()
[![Year](https://img.shields.io/badge/Coverage-2017--2026-green.svg)]()

---

### Abstract

Deepfake technology is overwhelmingly weaponised against women. Approximately 98% of deepfake videos are pornographic and 99% target women. The dominant tools used for this abuse are face-swap and nudify applications based on GAN architectures. Detection systems designed to combat this abuse exhibit significant demographic bias on GAN-based content, with up to 10.7% difference in False Positive Rates between racial subgroups. A recent empirical study published in 2026 found no such bias when testing on diffusion-generated images, raising the question of whether detection fairness depends on the type of deepfake being evaluated.

This systematic literature review is the first to bridge these two domains, synthesising 62 rigorously verified studies published between 2017 and 2026. We propose the **Gendered Deepfake-to-Harm Pipeline**, a framework mapping how face-swap detection bias compounds gender-based violence through five stages: Creation → Distribution → Detection Attempt → Disparity Gap → Compounded Harm.

### Key Contribution

> The populations most targeted by deepfake abuse are the same populations most failed by biased detection systems.

No existing study examines detection fairness in the context of gendered deepfake violence. This review identifies that gap and proposes a research agenda to address it.

---

### Repository Structure

```
deepfake-bias-gbv-slr/
│
├── README.md                          # This file
├── LICENSE                            # CC BY 4.0
├── SLR_62_Complete_Analysis.ipynb     # Full Colab notebook (figures + tables + analysis)
├── data/
│   └── studies_62.csv                 # Complete dataset of 48 verified studies
├── figures/
│   ├── fig1_prisma.png                # PRISMA flow diagram
│   ├── fig2_temporal.png              # Temporal distribution
│   ├── fig3_themes.png                # Thematic distribution
│   └── fig4_pipeline.png             # Gendered Deepfake-to-Harm Pipeline
├── CITATION.cff                       # Citation metadata
└── .gitignore                         # Git ignore rules
```

### 62 Verified Studies

Every included study has been independently verified with its exact published title and venue. The corpus spans seven thematic categories:



### Figures

| Figure | Description |
|---|---|
| Fig. 1 | PRISMA flow diagram |
| Fig. 2 | Temporal distribution (2017-2026) |
| Fig. 3 | Thematic distribution (pie + bar) |
| Fig. 4 | The Gendered Deepfake-to-Harm Pipeline |

### Key Findings

**Detection bias (on GAN face-swaps):** 11.6% AUC gap between White-Male (94.1%) and Black-Female (82.5%) subgroups. False positive rate 3.8x higher for Black women than White men (Trinh & Liu, 2021).

**Contested evidence:** Panda et al. (2026) found no systematic bias on diffusion-generated images. Whether bias exists for the GAN-based face-swaps used in gender violence remains untested.

**Platform failure:** Qiwei et al. (2024) found 100% removal for copyright claims vs 0% removal for non-consensual nudity reports on X after 21 days.

**Psychological harm:** 87% PTSD symptoms, 93% anxiety, 93% fear of resurfacing among victims (Flynn et al., 2025).

**South Korean crisis:** 332,341 cases of digital sexual violence in 2024. Only 12% of victims spoke publicly (Ji, 2025).

### How to Reproduce

1. Open the notebook in Google Colab using the badge above
2. Click **Runtime → Run All**
3. All 4 figures and analysis tables will be generated

Or run locally:

```bash
git clone https://github.com/YOUR_USERNAME/deepfake-bias-gbv-slr.git
cd deepfake-bias-gbv-slr
pip install matplotlib seaborn pandas numpy
jupyter notebook SLR_48_Complete_Analysis.ipynb
```

### Citation

If you use this work, please cite:

```bibtex
@article{author2026deepfakes,
  title={Deepfakes as Gendered Weapons: A Systematic Literature Review Bridging Face-Swap Detection Bias, Platform Failures, and Gender-Based Violence},
  author={Rao Faizan Ali},
  journal={[Target Journal]},
  year={2026}
}
```

### License

This work is licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). You are free to share and adapt the material with appropriate attribution.

### Contact

- **Author:** Rao Faizan Ali
- **Affiliation:** Institute of Cybersecurity and Society, University of Kent 
- **Email:** r.f.ali@university.ac.uk

---

*Last updated: March 2026*
