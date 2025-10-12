# egn5215-final-project-traffic-predictor
Exploration, analysis and modeling of traffic patterns, accidents, etc based on available US traffic data

## The dataset

[US Accidents (2016 - 2023)](https://www.kaggle.com/datasets/sobhanmoosavi/us-accidents)

## Getting started
1. Download & Install conda package manager: https://www.anaconda.com/download
     - NOTE: If in HiPerGator remote environment, simply run `ml conda` to load the conda module in your remote session, as the module is installed by default
2. Run `conda env create -f environment.yml` in directory with `environment.yml` file
3. Run `conda activate egn5215` (unless you used the `-n` flag in command above to give the env a custom name)
4. Run notebook


## Reproducibility (TODO: Using HiPerGator `PyTorch-2.8.0` kernel)
The `PyTorch-2.8.0` kernel comes with built-in NVIDIA GPU support in the form of the `pytorch` library. As of now, the notebook/project does not require GPU acceleration, so this is a future enhancement

### Exporting your env variables
1. Export kernel’s Python path
    - e.g. `/apps/pytorch/2.8.0/bin/python -m pip freeze > requirements.txt`


### Importing kernel values
1. Run `pip install -r requirements.txt` to import exact pip environment

