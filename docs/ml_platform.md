# JupyterLab

To support machine learning code development, our users can deploy one or more private JupyterLab applications.

To encourage fair sharing these applications are time limited. We also ask users to request only the resources that they need.

## Selecting GPU memory and instances

The AF cluster has four NVIDIA A100 GPUs. Each GPU can be partitioned into seven GPU instances. This means the AF cluster can have up to 28 GPU instances running in parallel. 

A user can request 0 to 7 GPU instances as a resource for the notebook. A user can request 40,836 MB of memory for an entire A100 GPU, or 4864 MB of memory for a MIG instance.

## Selecting a Docker image

Users can choose between two images: One with full anaconda (ivukotic/ml_platform:conda) and one with NVidia GPU and ROOT support (ivukotic/ml_platform:latest). The later has most of the ML packages (Tensorflow, Keras, ScikitLearn,...) preinstalled, and a small tutorial with example codes in /ML_platform_tests/tutorial.
For software additions and upgrades please contact ivukotic@uchicago.edu.
