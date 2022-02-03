# Applications

To support machine learning codes development, our users can deploy one or more private JupyterLab applications.

To encourage fair sharing these applications are time limited. We also ask users to requests only resources that they need.

Users can choose between two images: One with full anaconda (ivukotic/ml_platform:conda) and one with NVidia GPU and ROOT support (ivukotic/ml_platform:latest). The later has most of the ML packages (Tensorflow, Keras, ScikitLearn,...) preinstalled, and a small tutorial with example codes in /workspace/tutorial.
For software additions and upgrades please contact ivukotic@uchicago.edu.

## Tutorials

Basic usage of the platform can be exerienced by running the set of tutorials that come preinstalled with both __latest__ and __conda__ image.

### Running in conda

To run tutorial in conda environment, one first has to initialize conda. Simply open a jupyter lab terminal, and execute: __conda init__. Close that terminal and open a new one. This will drop you in __(base)__ conda environment. You may now switch to a HEP relevant environment by executing: conda activate __codas-hep__.
