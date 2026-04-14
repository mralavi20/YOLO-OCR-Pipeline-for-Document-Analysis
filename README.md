# Cascaded YOLO Pipeline for Document and Category Detection

This repository provides the **code, notebooks, and trained models** used for the first two stages of our paper’s pipeline for document analysis in natural images.

## Stages and models

### Stage 1 — Document detection / localization (instance segmentation)
We trained and evaluated:
- **YOLOv5-Seg**
- **YOLOv8-Seg**
- **YOLOv11-Seg**

### Stage 2 — Category detection (layout / semantic block detection)
We trained and evaluated:
- **YOLOv5-Det**
- **YOLOv8-Det**
- **YOLOv11-Det**
- **YOLOv12-Det**

## Repository structure

- `document detection/`  
  Training and evaluation for document instance segmentation (document masks for cropping/localization).

- `category detection/`  
  Training and evaluation for category/region detection inside the localized document.

## Outputs

Notebooks typically produce:
- model checkpoints
- evaluation metrics (mAP, precision, recall)
- qualitative overlays and prediction visualizations

## Reference

**Paper:** *A Cascaded YOLO-OCR Pipeline for Document Analysis in Natural Images*  
