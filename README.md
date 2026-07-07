# GenWildSplat Diagnostic Study

This repository contains a compact diagnostic study of GenWildSplat, a feed-forward method for sparse-view 3D reconstruction from unconstrained images.

The goal of this project is not to reproduce the full benchmark suite from the original paper, but to study inference-time behavior on a small diagnostic set and to evaluate the sensitivity of the pipeline to occlusion masks.

## Contents

- `report.pdf` — short technical report
- `main.tex` — LaTeX source for the report
- `figures/` — figures used in the report
- `metrics.csv` — diagnostic metrics
- `notebooks/` — cleaned notebook used for the experiments

## Summary

The study evaluates GenWildSplat on nine Mip-NeRF 360 scenes:

- garden
- stump
- flowers
- treehill
- bicycle
- kitchen
- counter
- bonsai
- room

The experiments compare blank masks against YOLOv8-generated masks to measure occlusion-mask sensitivity.

## Notebook

The notebook was developed and run in a Kaggle GPU environment.

Kaggle notebook: ADD LINK HERE

## Notes

This is an inference-time diagnostic study using the public GenWildSplat implementation and pretrained checkpoint. It does not include retraining and does not claim to reproduce the full benchmark suite from the original paper.

Original GenWildSplat repository: https://github.com/Vinayak-VG/GenWildSplat
