# GenWildSplat Diagnostic Notebook

This repository contains a cleaned notebook for a compact diagnostic study of GenWildSplat, a feed-forward method for sparse-view 3D reconstruction from unconstrained images.

The notebook focuses on inference-time behavior using the public GenWildSplat implementation and pretrained checkpoint. It includes environment setup, reproduction sanity checks, diagnostic evaluation on selected Mip-NeRF 360 scenes, and an occlusion-mask sensitivity analysis comparing blank masks with YOLOv8-generated masks.

## Notebook

- `genwildsplat_diagnostic.ipynb` — cleaned notebook with section headings and outputs

## Study Overview

The notebook evaluates GenWildSplat on nine Mip-NeRF 360 scenes:

- garden
- stump
- flowers
- treehill
- bicycle
- kitchen
- counter
- bonsai
- room

The main diagnostic questions are:

1. How does reconstruction quality vary across different scene types?
2. How sensitive are the results to the semantic occlusion-mask prior?

## Kaggle Version

The notebook was developed and run in a Kaggle GPU environment.

Kaggle notebook: ADD LINK HERE

## Notes

This is an inference-time diagnostic notebook. It does not include model retraining and does not claim to reproduce the full benchmark suite from the original paper.

Original GenWildSplat repository: https://github.com/Vinayak-VG/GenWildSplat
