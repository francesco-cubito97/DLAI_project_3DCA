# DLAI_project_3D_NCA
3D neural cellular automaton able to reproduce simple voxels patterns starting from one single cell and learning the underling set of rules.
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/francesco-cubito97/DLAI_project_3D_NCA/blob/main/Final_DLAI_project_Growing3D_NCA.ipynb)
Follows the model architecture:
![Model architecture](./Model_Architecture.png)

## External resources
- <code>binvox_rw.py</code> was taken from [here]( https://github.com/dimatura/binvox-rw-py). 
- The project taken inspiration from [this](https://distill.pub/2020/growing-ca/) link

## Results
Follows the results obtained with the trained models:

![Cow model gif](./cow_model_fpf_n_100.gif)

![Fox model gif](./fox_model_fpf_n_100.gif)

## Evaluation results
Follow the plota of losses with fixed and not-fixed perception filter with both objects:

![Plot loss cow](./plot_loss_cow.png) ![Plot loss fox](./plot_loss_fox.png)
