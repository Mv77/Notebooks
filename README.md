# Centralized Repo of Public Jupyter Notebooks

This repo was created as a place to put notebooks used for teaching, presentations, and other purposes where public availability of the notebook is convenient 

## Running with MyBinder 

The notebooks should be launchable by [![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/llorracc/Notebooks/master)

## Local installation

### Option 1: With Jupyter

0. [Install jupyter](https://jupyter.org/install).
1. [Clone](https://help.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository) `DemARK` to the local folder of your choice
2. In the new folder, run `pip install -r binder/requirements.txt` to install dependencies
3. Enable notebook extensions.

   **On Linux/macOS:**

   Run `binder/postBuild` in your terminal (at a shell in the binder directory, `./postBuild`)

   **On Windows:**

   Run `binder/postBuild.bat`

4. Run `jupyter notebook` from the `DemARK` root folder. You will be prompted to open a page in your web browser. From there, you will be able to run the notebooks.
5. Run the notebook by clicking the `▶▶` button or choosing `Kernel → Restart & Run All`

### Option 2: With Docker and repo2docker

0. [Install Docker](https://www.docker.com/community-edition)
1. [Install `repo2docker`](https://github.com/jupyter/repo2docker#installation), using the "install from source" instructions
2. Run `jupyter repo2docker https://github.com/econ-ark/DemARK`
3. Follow the link in your terminal to the running instance of jupyter
4. Run the notebook by clicking the `▶▶` button or choosing `Kernel → Restart & Run All`


## Issues

Open an issue in this repository!
