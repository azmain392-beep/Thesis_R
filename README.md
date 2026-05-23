# Thesis_R

COMSOL-calibrated Python workflow for a two-mode OAM ring-core fiber thesis.

## Main workflow
1. Read COMSOL Excel exports
2. Build a clean master table
3. Fit neff surrogates
4. Generate perturbed geometries
5. Build communication channel
6. Run BER and yield analysis
7. Save figures and reports

## Folder guide
- data/raw: original COMSOL exports
- data/processed: cleaned tables
- src: Python source code
- outputs/figures: plots
- outputs/reports: generated reports

## Environment
Create a virtual environment and install:
pip install -r requirements.txt