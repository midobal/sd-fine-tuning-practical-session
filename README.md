# Stable Diffusion Fine-tuning with DreamBooth
This repo containts a notebook that presents a practical session for fine-tuning [Stable Diffusion](https://stablediffusionweb.com/) so it learns to generate yourself. It was created for the lab sessions of the *Tools and Applications of Artificial Intelligence* module of the [IARFID](https://www.upv.es/titulaciones/MUIARFID/) master from [Universitat Politècnica de València](https://www.upv.es/en). It is based on the notebook by [TheLastBen](https://github.com/TheLastBen/fast-stable-diffusion).

You can open the notebook by clicking on [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/midobal/sd-fine-tuning-practical-session/blob/master/Stable_Diffusion_DreamBooth_fine_tuning.ipynb).

## Overview
The goal of this lab session is to fine-tune [Stable Diffusion](https://stablediffusionweb.com/) using [DreamBooth](https://dreambooth.github.io/), to create a model which is able to generate yourself.

### Dataset
For this practical session we need a collection of photos of ourselves. It is recommended to use between 15 to 20 pictures with the following characteristics:

* 2 to 3 full-body pictures.
* 3 to 5 pictures in which only half of our body appears.
* 8 to 12 portrait pictures.

It is important to have variability in the images: different backgrounds, light conditions, clothes we are wearing, etc.

## Colab resources

* [Overview of Colaboratory](/notebooks/basic_features_overview.ipynb).
* [Guide to Markdown](/notebooks/markdown_guide.ipynb).
* [Importing libraries and installing dependencies](/notebooks/snippets/importing_libraries.ipynb).
* [Saving and loading notebooks in GitHub](https://colab.research.google.com/github/googlecolab/colabtools/blob/main/notebooks/colab-github-demo.ipynb).

## References

* Rombach, R., Blattmann, A., Lorenz, D., Esser, P., & Ommer, B. (2022). [High-Resolution Image Synthesis with Latent Diffusion Models](https://arxiv.org/abs/2112.10752). In Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition, 10684–10695.
* Ruiz, N., Li, Y., Jampani, V., Pritch, Y., Rubinstein, M., & Aberman, K. (2022). [DreamBooth: Fine Tuning Text-to-image Diffusion Models for Subject-Driven Generation](https://arxiv.org/abs/2208.12242). arXiv preprint arxiv:2208. 2242.
