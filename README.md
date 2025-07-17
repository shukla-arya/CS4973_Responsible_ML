# CS4973_Responsible_ML
Determines how the performance of a machine learning (ML) model can demonstrate underdiagnosis for chest radiomics in protected classes. Motivated by the inaccurate labeling of images, social determinants of health (SDOHs), and lack of diversity in the target population.

## Features
* Dataset of frontal chest images is publicly available from the National Institute of Health (NIH).
* Uses ML technqiues to categorically classify images based on disease status of the patient.
* Protected classes include patient age and gender, with hopes of later determining the involvement of race.
* Powerpoint presentation to summarize the data acquisition, methodology, and results.

## Tech Stack
* **Language:** Python  
* **Libraries:** `pandas`, `numpy`, `os`, `torch`, `sklearn`, `aequitas`
* **Visualization:** `matplotlib`, `seaborn`
  
## Requirements

```
pip install aequitas
```

