# FLUX Text-to-Image Inference

This repository contains notebooks for running inference with the FLUX text-to-image model.

## Contents

- [Colab Notebook](https://colab.research.google.com/drive/1lkPxDhOenQPfgoPDum6WLeq0qLyO3Gby) - Run FLUX inference in Google Colab
- [Local Notebook](https://github.com/AkulDatta/FLUX-Inference-fp8/blob/main/FluxInference.ipynb) - Run FLUX inference locally (Requires a 16GB+ GPU)

## Usage

The notebooks allow you to generate images from text prompts using the FLUX model. They include code for:

- Setting up the environment
- Loading the FLUX model
- Generating images from text inputs
- Displaying and saving the generated images

You can run the Colab notebook directly in your browser, or download the local notebook to run on your own machine (GPU required).

## Requirements

- Python 3.7+
- PyTorch
- Transformers
- diffusers
- ComfyUI
- totoro

See the notebooks for full dependency lists and setup instructions.

## Acknowledgements

These notebooks are based on the notebooks in the [camenduru/flux-jupyter](https://github.com/camenduru/flux-jupyter) repository. Check out their original notebooks!

The FLUX model used in these notebooks was developed by [Black Forest Labs](https://blackforestlabs.ai/).
