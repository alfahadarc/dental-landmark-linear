# Linear Dental Study

This folder contains the notebooks, data, and generated outputs for the linear dental landmark study.

Source data and splits are in `Data/`. Main workflows include age alignment, autoregressive models, sex-adaptive models, plotting, and report generation.

Publication
Autoregressive model evaluation paper: "Evaluation of Autoregressive Models for Predicting Two-Dimensional Mandibular Landmark Displacement During Pubertal Growth"
DOI: https://doi.org/10.1111/ocr.70150

Main notebooks:
- `align_all_age.ipynb`: creates gonion points and aligns samples by age bin.
- `autoreg_v1.ipynb` and `autoreg_x_y_v1.ipynb`: autoregressive models for x/y prediction.
- `sex_adaptive_model.ipynb`: sex-adaptive autoregressive model.
- `per_sid_mae.ipynb`, `plot_gen.ipynb`, `report_gen.ipynb`: evaluation, plots, and reports.