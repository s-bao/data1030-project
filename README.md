# DATA 1030 Final Project: Classifying Dementia Using the Open Access Series of Imaging Studies (OASIS) Longitudinal Dataset
### Problem Statement: 
In this project, I aim to classify individuals as either "Demented" or "Nondemented" using demographic, cognitive, and MRI data. This involves building an ML classification task that can predict whether a subject has dementia based on features such as age, cognitive test scores (e.g. MMSE, CDR), and brain volume measurements (e.g. eTIV, nWBV). This classification task is crucial because early detection of dementia is vital for timely intervention and management, potentially improving patients' quality of life. A definitive diagnosis of Alzheimer's disease can only be made after an autopsy of the brain, so, typically, doctors make clinical diagnoses based off a comprehensive assessment of the patient's condition, considering many of the factors described in this dataset. Therefore, by leveraging predictive models, we can assist clinicians in identifying high-risk individuals and support decision-making in diagnosing Alzheimer's disease.

## Dataset: 
The dataset that I use is the [**MRI and Alzheimer's dataset**](https://www.kaggle.com/datasets/jboysen/mri-and-alzheimers/data) from Kaggle. I specifically use the OASIS longitudinal dataset that contains information on 150 subjects ages 60 to 96. This dataset is longitudinal because it has information on at least 2 visits for each subjects, where visits are separated by at least 1 year. For each visit, all cognitive and MRI measurements are updated.

## Dependencies: 
Run `conda env create -f requirements.yml` then `conda activate final_env` from the main project directory to set up the Conda environment with all necessary dependencies.

  - python=3.12.4
  - matplotlib=3.9.2
  - pandas=2.2.2
  - scikit-learn=1.5.1
  - numpy=1.26.4
  - shap=0.46.0
  - jupyter_client=8.6.2
  - jupyter_core=5.7.2
  - jupyterlab=4.2.5
  - jupyterlab_server=2.27.3
  - jupytext
  - rise
