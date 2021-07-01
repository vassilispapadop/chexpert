# chexpert
 CheXpert is a large dataset of chest X-rays and competition for automated chest x-ray interpretation


# Pre-process
### preprocess_metadata.py
* Remove rows without specified value in column Age
* Keep only x-rays with frontal view (AP)
* Treat uncertainty(-1), 50%-50% rule
* Sub-sample full dataset for computational reasons(use only 0.2 of entire set, >32K)
