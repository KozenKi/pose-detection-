# Fitness Exercise Dataset

## Overview
This repository contains a fitness exercise dataset for human action recognition and posture analysis in home fitness scenarios. The dataset is designed for computer vision research, especially for exercise detection, pose-based analysis, and intelligent fitness coaching systems.

The dataset includes three main exercise categories:

- Push-up
- Sit-up
- Squat

In addition to the training, validation, and test sets, the repository also includes source video folders for each exercise category.

## Directory Structure
```text
fitness/
├── push_up_video/
├── sit_up_video/
├── squat_video/
├── train/
│   ├── images/
│   ├── labels/
│   └── labels.cache
├── valid/
│   ├── images/
│   └── labels/
└── test/
    ├── images/
    └── labels/
Dataset Content

This dataset contains exercise-related image samples and corresponding annotation files for model training and evaluation.

Exercise Classes
Push-up
Sit-up
Squat
Included Data

Source exercise videos:

push_up_video/
sit_up_video/
squat_video/

Image datasets for model development:

train/
valid/
test/

Annotation files:

Stored in the labels/ folders
Annotation Format

The dataset is organized in a YOLO-style directory structure, where:

images/ contains image files
labels/ contains the corresponding annotation files

If you use this dataset, please make sure that your training pipeline matches the annotation format used in this repository.

Data Source

Part of this dataset was obtained from Roboflow, an open-access dataset platform, and was further organized for research purposes in fitness action analysis.

Please respect the original license terms and conditions of the source data when using or redistributing this dataset.

Intended Use

This dataset is intended for academic research and educational purposes, including:

Human action recognition
Exercise classification
Pose-based motion analysis
Repetition counting
AI-based home fitness systems
Usage

After downloading the dataset, unzip it and use the train, valid, and test folders in your machine learning pipeline.

An example dataset configuration for YOLO-based projects is shown below:

train: ./train/images
val: ./valid/images
test: ./test/images

names:
  0: push-up
  1: sit-up
  2: squat

Please adjust the class order if your label definition is different.

Notes
The file labels.cache is a cache file generated during training and may not be necessary for redistribution.
The video folders are provided as supplementary source material.
The main dataset for training and evaluation is located in the train, valid, and test directories.
Release

The dataset is available in the GitHub Releases section of this repository.

Release page: GitHub Releases

You can download the dataset package from the release page.

Data Availability

The dataset used in this study is publicly available in this GitHub repository.

For convenient download, the dataset package is provided in the Releases section of the repository:

GitHub Releases

License

This dataset is provided for academic research use only unless otherwise specified.

Users are responsible for checking the license and reuse conditions of any third-party source data.
