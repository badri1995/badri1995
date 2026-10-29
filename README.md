# Badrinath Padmanabhan

I work on medical computer vision at AIIMS New Delhi, with a focus on image-based microsuturing assessment and uncertainty in model predictions. Previously, I worked at IIT Delhi on satellite-based socioeconomic measurement and groundwater modelling, and remotely with Cardiff University on early histopathology–MRI correspondence prototypes.

My main research interest is **reliable medical computer vision with limited data and distribution shift**.

## Start with my medical vision work

### [Microsuturing image assessment](https://github.com/badri1995/microsuturing-assessment)

Assessing technical indicators of completed microsutures using DINOv2 representations, evidential regression and score-group classification. The repository includes the model, losses, annotation reader, grouped cross-validation and an offline synthetic demo. The emphasis is on inspecting uncertainty and avoiding related-image leakage, not treating model scores as clinical safety decisions.

**Entry points:** [`demo.py`](https://github.com/badri1995/microsuturing-assessment/blob/main/demo.py) for a data-free wiring check, then [`train_kfold_cv.py`](https://github.com/badri1995/microsuturing-assessment/blob/main/train_kfold_cv.py) for authorised data.

### [Prostate imaging research](https://github.com/badri1995/prostate-imaging-research)

Original paired MRI/histopathology correspondence and PANDA ROI notebooks, alongside a clearly identified September 2026 assisted restart. The restart checks slide/mask labels and calibration, extracts a physical patch and exports MSER candidates as SVG. It is an early histology-to-MRI research direction, not a completed PI-CAI detector or diffusion simulation.

**Entry points:** [project map](https://github.com/badri1995/prostate-imaging-research/blob/main/WORKFLOW.md), [restart notebook](https://github.com/badri1995/prostate-imaging-research/blob/main/notebooks/PICAI_Histology_Restart.ipynb) and [synthetic tests](https://github.com/badri1995/prostate-imaging-research/blob/main/test_histology.py).

## Earlier work: geospatial machine learning at IIT Delhi

| Project                                                                          | Research question                                                                      | Code to start with                                                                                                                                                                                                                                                                                                                                                                                           |
| -------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| [Relative Wealth Index](https://github.com/badri1995/relative-wealth-index)      | How can satellite-related indicators help estimate relative socioeconomic development? | [`workflow.py`](https://github.com/badri1995/relative-wealth-index/blob/main/workflow.py): selected-feature regression with explicit data splits and a synthetic demo. Original target-construction notebooks are retained.                                                                                                                                                                                  |
| [CGWB groundwater modelling](https://github.com/badri1995/groundwater-modelling) | How do hydrological and geospatial covariates relate to changes in groundwater depth?  | [17-notebook workflow](https://github.com/badri1995/groundwater-modelling/blob/main/WORKFLOW.md): observation cleaning, aquifer and terrain integration, ABY/SOGE features, deep and shallow five-year modelling, regression comparisons and transfer experiments. [`prepare_wells.py`](https://github.com/badri1995/groundwater-modelling/blob/main/prepare_wells.py) remains a small runnable entry point. |

[ADI_complete](https://github.com/badri1995/ADI_complete) preserves the earlier satellite-indicator workflow. It provides background to the socioeconomic research, rather than another independent flagship project.

## About the releases

These repositories separate existing research source from newer portability improvements. They include setup instructions, synthetic demos or tests, and an account of what the public code does and does not include. Synthetic checks are software checks, not scientific results. Private datasets, images, annotations and trained weights are not distributed; study results have not been reproduced in these releases.

Python · PyTorch · scikit-learn · GeoPandas · Computer vision · Uncertainty estimation · Geospatial ML

I am interested in PhD and research opportunities in medical computer vision and trustworthy machine learning.

[LinkedIn](https://www.linkedin.com/in/badrinath-padmanabhan-73573310a/)
