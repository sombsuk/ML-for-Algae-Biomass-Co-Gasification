# ML for Algae-Biomass Co-Gasification

[![DOI](https://img.shields.io/badge/DOI-10.1016%2Fj.clet.2025.101038-blue)](https://doi.org/10.1016/j.clet.2025.101038)
[![Journal](https://img.shields.io/badge/Journal-Cleaner%20Engineering%20%26%20Technology-orange)](https://www.sciencedirect.com/journal/cleaner-engineering-and-technology)
[![License](https://img.shields.io/badge/License-CC%20BY--NC--ND%204.0-lightgrey)](https://creativecommons.org/licenses/by-nc-nd/4.0/)
[![Open Access](https://img.shields.io/badge/Open-Access-green)](https://doi.org/10.1016/j.clet.2025.101038)

## About

This repository contains the dataset and supporting materials for the integrated **machine learning (ML) and thermodynamic modeling** framework developed to optimize **hydrogen (H₂) production via algae–biomass co-gasification**. The framework combines Aspen Plus–based equilibrium modeling with data-driven prediction and metaheuristic optimization to identify operating conditions that maximize H₂ yield while improving overall process efficiency.

## Associated Publication

> **Tuntiwongwat, T., Yukawa, T., Srinophakun, T. R., Manatura, K., Sukpancharoen, S., & Mirjalili, S.** (2025). Machine learning and thermodynamic modeling for optimizing hydrogen production via algae-biomass co-gasification. *Cleaner Engineering and Technology*, *28*, 101038. https://doi.org/10.1016/j.clet.2025.101038

**Open Access** under Creative Commons license — freely available at [ScienceDirect](https://doi.org/10.1016/j.clet.2025.101038).

## Highlights

- Integrated **ML + thermodynamic equilibrium modeling** for algae–biomass co-gasification.
- Predictive models for hydrogen-rich syngas yield from mixed feedstock characteristics.
- Multi-objective optimization to identify eco-efficient gasification operating conditions.
- International collaboration spanning **Thailand, Japan, Australia, Czech Republic, and Hungary**.

## Repository Structure

```
ML-for-Algae-Biomass-Co-Gasification/
├── dataset.xlsx     # Curated dataset for ML training and validation
└── README.md        # This file
```

The `dataset.xlsx` file contains the consolidated input–output data used for training and evaluating the machine learning models reported in the publication, including feedstock characteristics (ultimate and proximate analyses), operating parameters (temperature, equivalence ratio, steam-to-biomass ratio, blending ratio, etc.), and the corresponding gasification performance indicators (H₂ yield, syngas composition, and related metrics).

## Usage

### Download

```bash
git clone https://github.com/sombsuk/ML-for-Algae-Biomass-Co-Gasification.git
cd ML-for-Algae-Biomass-Co-Gasification
```

Or download `dataset.xlsx` directly from the GitHub web interface.

### Loading the Dataset (Python example)

```python
import pandas as pd

# Load the dataset
df = pd.read_excel("dataset.xlsx")

# Quick inspection
print(df.shape)
print(df.head())
print(df.describe())
```

For full methodological details — including data pre-processing, model architectures, hyperparameter tuning, and validation — please refer to the [associated publication](https://doi.org/10.1016/j.clet.2025.101038).

### Citation

If you use this dataset in your research, please cite the associated publication:

**BibTeX:**
```bibtex
@article{Tuntiwongwat2025algae,
  title   = {Machine learning and thermodynamic modeling for optimizing hydrogen production via algae-biomass co-gasification},
  author  = {Tuntiwongwat, Thanadol and Yukawa, Takashi and Srinophakun, Thongchai Rohitatisha and Manatura, Kanit and Sukpancharoen, Somboon and Mirjalili, Seyedali},
  journal = {Cleaner Engineering and Technology},
  volume  = {28},
  pages   = {101038},
  year    = {2025},
  doi     = {10.1016/j.clet.2025.101038},
  url     = {https://doi.org/10.1016/j.clet.2025.101038}
}
```

## Authors and Affiliations

| # | Author | Affiliation |
|---|--------|-------------|
| a | Thanadol Tuntiwongwat | Department of Mechanical Engineering, Khon Kaen University, Thailand |
| b | Takashi Yukawa | Department of Management and Information Systems Science, Nagaoka University of Technology, Japan |
| c | Thongchai Rohitatisha Srinophakun | Department of Chemical Engineering, Kasetsart University, Thailand |
| d | Kanit Manatura | Department of Mechatronics Engineering, Rajamangala University of Technology Isan, Thailand |
| e | **Somboon Sukpancharoen** *(corresponding)* | Department of Agricultural Engineering, Khon Kaen University, Thailand |
| f, g, h | Seyedali Mirjalili | Torrens University Australia · VSB-Technical University of Ostrava, Czech Republic · Obuda University, Hungary |

## License

This repository is released under the **Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International (CC BY-NC-ND 4.0)** license, consistent with the open-access publication. This means you may:

- ✅ **Share** — copy and redistribute the material in any medium or format
- ✅ **Attribute** — give appropriate credit to the authors and cite the publication

But you may **not**:

- ❌ **NonCommercial** — use the material for commercial purposes without permission
- ❌ **NoDerivatives** — distribute modified versions of the material

For full license terms, see [CC BY-NC-ND 4.0](https://creativecommons.org/licenses/by-nc-nd/4.0/).

## Contact

For questions, collaborations, or technical inquiries regarding the dataset:

**Assoc. Prof. Somboon Sukpancharoen, Ph.D.**
Department of Agricultural Engineering, Faculty of Engineering
Khon Kaen University, Khon Kaen 40002, Thailand
📧 sombsuk@kku.ac.th
