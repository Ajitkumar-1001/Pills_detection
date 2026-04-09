<h1 align="center">Pills Detection</h1>

<p align="center">
A computer vision project focused on detecting and localizing pills in images using a bounding-box detection pipeline.
</p>

## Project Scope

This repository is currently scoped as a pill detection project, not a full pill identification system.

With the current dataset, the model can be trained to:

- detect whether pills are present in an image
- localize pills with bounding boxes
- count pill instances in an image

With the current dataset alone, the model cannot reliably:

- identify the exact medication name
- classify pill type or brand
- read imprint text or perform fine-grained recognition

## Dataset

The current project can use the Kaggle dataset:

- [Pills Detection Dataset](https://www.kaggle.com/datasets/alexanderyyy/pills-detection-dataset/data)

Dataset notes:

- annotated in YOLO format
- single-class setup: `pill`
- suitable for object detection workflows
- appropriate for models such as YOLO, Faster R-CNN, RetinaNet, or Lightning-based custom detectors

## Important Limitation

Because the dataset is labeled as a single detection class, this project should be described as pill detection/localization rather than pill identification.

If the goal later becomes medication recognition, the project will need additional labeled data for:

- pill class labels
- imprint text
- color and shape attributes
- multi-stage detection plus classification or retrieval

## Licensing Note

The Kaggle dataset page lists the dataset license as `CC BY-NC-SA 4.0`. That means it is appropriate for research, academic, and non-commercial use, but it should not be used directly for commercial deployment without resolving licensing constraints.

<u><h2 align="center">Contributors</h2></u>

<p align="center">
<strong>Ajitkumar</strong> — MS in Data Science <br/>
<strong>Aditi Tata</strong> — MS in Biomedical Engineering
</p>
