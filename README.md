# Reproducibility Analysis in Vestibular Network Neuroimaging

A neuroimaging methods project evaluating how ROI definitions, preprocessing, model selection, and statistical decisions influence conclusions in vestibular-network brain imaging research.

This repository completes the vestibular and spatial neuroplasticity track by focusing on robustness, transparency, and the reliability of findings across alternative analytical pipelines.

## Project Aim

To test whether commonly reported vestibular-network findings remain stable under defensible methodological variation, and to establish a reproducibility-focused framework for future open neuroscience research.

## Dataset Used

- Domain: Vestibular and Spatial Neuroplasticity  
- Focus: Reproducibility of vestibular-network findings  
- Reference Context: Open neuroimaging workflows inspired by AOMIC / ID1000 style datasets  
- Population: Healthy adult participants  
- Design: Multi-pipeline methodological sensitivity framework  
- Modalities Referenced: Resting-state fMRI, network-level analyses

## Analytical Scope

This repository focuses on a proof-of-concept framework using:

- ROI and pipeline decision landscape mapping
- ROI definition sensitivity analysis
- Connectivity estimator and model comparison
- Statistical threshold robustness testing
- Integrated reproducibility summary reporting

## Why a Reproducibility Pipeline Was Used

Single analytical pipelines can create false certainty. A reproducibility pipeline was used to test whether observed vestibular-network conclusions persist across alternative but defensible methodological choices.

This preserves the central scientific question: are reported vestibular effects robust or pipeline-dependent?

Future repositories may extend this framework using preregistration, multi-lab replication, and raw-data reprocessing at scale.

## Methods

The repository used a lightweight and scalable workflow:

- Map methodological decision points
- Compare ROI definitions and effect estimates
- Test model and estimator sensitivity
- Evaluate significance under correction strategies
- Summarize robustness across analytical dimensions

## Main Findings

- Effect direction was more stable than exact effect magnitude
- Model choice influenced predictive robustness substantially
- ROI definitions changed regional effect estimates
- Statistical correction methods altered significance calls
- Transparent multi-pipeline reporting improves interpretability

## Repository Workflow

### Notebook 1 - ROI Pipeline Landscape

Mapped common ROI, preprocessing, and modelling decisions affecting reproducibility.

### Notebook 2 - ROI Definition Sensitivity

Tested how alternative ROI definitions changed regional effects.

### Notebook 3 - Model Choice Comparison

Compared connectivity estimators and predictive models.

### Notebook 4 - Statistical Threshold Robustness

Assessed how correction methods altered significance conclusions.

### Notebook 5 - Reproducibility Summary Report

Integrated findings into a final vestibular robustness framework.

## Limitations

- Proof-of-concept methodological simulation framework
- Network-level rather than voxel-wise replication testing
- Illustrative sensitivity values rather than full raw reprocessing
- Focused on resting-state style analyses

## Future Directions

- Full raw-data multi-pipeline reprocessing
- Pre-registered confirmatory analyses
- Cross-dataset vestibular replication studies
- Multi-site harmonization benchmarking
- Automated reproducibility dashboards

## Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Statsmodels
- Google Colab

## Maintained By

Aditya Sundaray
