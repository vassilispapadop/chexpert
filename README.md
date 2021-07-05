# CheXpert Radiography
 CheXpert is a large dataset of chest X-rays and competition for automated chest x-ray interpretation


# Pre-process
``` python 
python preprocess_metadata.py
```
train_processed_0_4.csv
CheXpert-v1.0-processed_0_4.zip


* Remove rows without specified value in column Age
* Keep only x-rays with frontal view (AP)
* Treat uncertainty(-1), 50%-50% rule
* Sub-sample full dataset for computational reasons(use only 0.4 of entire set, >60K)


# Launch jupyter
```python
jupyter notebook CheXpert-nb-small.ipynb
```


