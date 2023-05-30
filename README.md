# DISA: DIfferentiable Similarity Approximation for Universal Multimodal Registration

This repository contains the training code for the MICCAI sumbission #3033


## Running
The Docker contaniner for executing the training can be created wirth the following command: `docker build . -t disa`.
Afterwards the model can be trained by running:
`docker run -it --rm --gpus all --volume "$(pwd)/Data":/data --volume "$(pwd)/Output":/output --shm-size=32gb disa`
