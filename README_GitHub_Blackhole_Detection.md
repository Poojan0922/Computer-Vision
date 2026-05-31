# Black Hole Detection in Galaxy Centers using Computer Vision

## Project Overview
This project analyzes multi-wavelength astronomical observations of the galaxy **Messier 99 (M99 / NGC 4254)** to investigate evidence of a central black hole using image processing, exploratory data analysis (EDA), and astronomical FITS data.

The notebook works with observations from multiple instruments:

- Near Infrared observations
- Hubble Space Telescope (Optical)
- XMM-Newton (X-ray)

## Repository Structure

```text
blackhole-detection/
│
├── notebooks/
│   └── Blackhole_Detection.ipynb
│
├── data/
│   ├── README.md
│   └── (FITS files not tracked in Git)
│
├── images/
│   └── generated_figures/
│
├── requirements.txt
├── README.md
└── .gitignore
```

## Dataset

The original notebook references Google Drive paths and FITS files that are not included in the repository.

Place the required data inside:

```text
data/
├── M99/
│   ├── NEAR_INFRARED/
│   ├── OPTICAL/
│   └── XMM/
```

Then update file paths in the notebook accordingly.

## Installation

```bash
git clone <your-repository-url>
cd blackhole-detection

pip install -r requirements.txt
```

## Suggested Requirements

```text
numpy
pandas
matplotlib
seaborn
astropy
specutils
scikit-image
scipy
``

## Running the Project

Start Jupyter:

```bash
jupyter notebook
```

Open:

```text
notebooks/Blackhole_Detection.ipynb
```

## Analysis Workflow

1. Literature survey of M99.
2. Load astronomical FITS data.
3. Exploratory data analysis.
4. Visualize multi-wavelength observations.
5. Extract features from galaxy-center imagery.
6. Investigate signatures associated with black-hole activity.
7. Summarize findings.

## Results

Include representative figures inside the `images/` folder and reference them here.

## Future Improvements

- Automated black-hole candidate detection.
- Deep learning based feature extraction.
- Cross-validation using additional galaxies.
- Improved astrophysical interpretation of observations.

## Author

Replace with your name and affiliation.
