# Interpretable Medical Imaging

Tools and experiments for evaluating **interpretability and localization reliability**
in chest X-ray deep learning models.

## Problem
Deep learning models for chest X-ray classification often achieve strong
aggregate performance while relying on spurious or non-clinical features.
This creates risk for deployment in clinical or high-stakes settings.

## Approach
This project evaluates model interpretability by combining:
- CAM-based localization methods
- Quantitative spatial metrics for anatomical relevance
- Comparative analysis across model architectures and class setups

The goal is to measure **how reliably** a model attends to clinically meaningful regions,
not just whether it predicts the correct label.

## Key Insight
High accuracy does not imply trustworthy reasoning.
Explicit interpretability metrics reveal failure modes that are invisible to
standard performance evaluation.

## Example Output
![Model localization example](figures/bio_rel.jpg)

## Repository Structure


## Status
Actively being cleaned and prepared for public release.

## Contact
Cory-James  Pugne-Andenoro  - https://www.linkedin.com/in/cory-james-pugne-andenoro-673637194/
PhD Candidate, Quantitative & Systems Biology (graduating May 2026)

