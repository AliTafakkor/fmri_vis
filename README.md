# fmri_vis

Author: Ali

Modality: fMRI

---

This project uses fMRI data organized in BIDS format.


## Setup
1. Create the environment with conda:
    ```
    conda env create -f environment.yml
    ```
2. Activate the environment
    ```
    conda activate fmri_vis
    ```
3. Downloading sample dataset
    ```
    wget -P data/raw https://zenodo.org/records/5790821/files/ds-sample.tar.gz
    ```