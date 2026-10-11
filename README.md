# Enhancing Corneal Endothelial Cell Image Segmentation via Generative Data Augmentation and Transfer Learning

This repository contains supplementary material accompanying the associated article in *IEEE Journal of Biomedical and Health Informatics*.

**Article DOI:** [10.1109/JBHI.2026.3728886](https://doi.org/10.1109/JBHI.2026.3728886)

## Supplementary Material

[View or download the Computational Cost Discussion (PDF)](JBHI_Supplementary_Material_Computational_Cost_Discussion.pdf)

The supplementary document preserves the complete Computational Cost Discussion without abridgment. It describes the estimated computational requirements of the proposed framework, including:

- Stable Diffusion 1.5 LoRA training with different training-set sizes.
- Object detection using YOLOv8n, YOLO11n, YOLO12n, and RT-DETR-l.
- Synthetic mask-image pair generation using Stable Diffusion and ControlNet.
- Segmentation training using U-Net, TransUNet, and SwinUNet.
- Model-only segmentation inference times and deployment considerations.

## Interpretation of Computational Costs

The reported computational costs are estimates under the experimental conditions described in the associated article. Actual execution times may vary with hardware, software configuration, training settings, and dataset size.

The inference estimates refer to model-only processing at a resolution of 224 × 224, with a batch size of one and a warmed-up GPU. They exclude additional preprocessing operations and should not be interpreted as end-to-end workflow timings.

## Repository Scope

This repository currently provides supplementary documentation only. Implementation code, datasets, and trained model weights are not included.

## Citation

If you use or refer to this supplementary material, please cite the associated article:

*Enhancing Corneal Endothelial Cell Image Segmentation via Generative Data Augmentation and Transfer Learning.*  
*IEEE Journal of Biomedical and Health Informatics.*  
DOI: [10.1109/JBHI.2026.3728886](https://doi.org/10.1109/JBHI.2026.3728886)
