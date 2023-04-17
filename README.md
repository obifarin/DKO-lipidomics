# DKO-lipidomics
 
Code base for the study: **"Machine Learning Reveals Lipidome Remodeling Dynamics in a Mouse Model of Ovarian Cancer."**

[Link to Preprint](https://www.biorxiv.org/content/10.1101/2023.01.04.520434v1)

## Requirements

- __[Anaconda](https://www.anaconda.com/)__
- __[Python >= 3.8.8](https://www.python.org/downloads/)__
- __[Jupyter](https://jupyter.org/install)__


### 1. git repository

Clone local copy of git repository

git clone https://github.com/obifarin/DKO-lipidomics

(or use a git GUI client of your choice)

### 2. Environment setup and access jupyter notebooks
Setup python environment (`dko-gatech.yml`) in the terminal. 

(or use anaconda GUI.)


### 3. Notebook contents

<table>
  <tr>
    <th>Name</th>
    <th>Description</th>
  </tr>
  <tr>
    <td>1_global_lipidomic_changes.ipynb</td>
    <td>Global significant changes: univariate statistical testing and unsupervised learning.</td>
  </tr>
  <tr>
    <td>2_lipidomic_trajectory_clusters.ipynb</td>
    <td>Lipidome alterations in response to ovarian cancer progression.</td>
  </tr>
   <tr>
    <td>3_machine_learning_DKO_classification.ipynb</td>
    <td>Time-resolved machine learning discriminates tumor stages of HGSC in DKO mice.</td>
  </tr>
    <tr>
    <td>4_survival_analysis_prognostics.ipynb</td>
    <td>Prognostic circulating lipids in DKO mice.</td>
  </tr>
    <tr>
    <td>5_ML_DKO_permutation_test.ipynb</td>
    <td>Permutation tests for ML model validation.</td>
  </tr>
</table>
