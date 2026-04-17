# Fitness Exercise Dataset
## Contents
This dataset includes three exercise categories:

- Push-up
- Sit-up
- Squat

The repository contains:

- source videos for each exercise
- training set
- validation set
- test set
- YOLO-style annotations

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
```

## Format
The dataset follows a YOLO-style structure:

- `images/` contains image files
- `labels/` contains the corresponding annotation files

Example configuration:

```yaml
train: ./train/images
val: ./valid/images
test: ./test/images

names:
  0: push-up
  1: sit-up
  2: squat
```

## Source
Part of this dataset was obtained from **Roboflow** and further organized for research purposes.

Please check the original license terms of any third-party source data before reuse or redistribution.

## Download
The dataset package is available in the GitHub Releases section:

[GitHub Releases](https://github.com/KozenKi/pose-detection-/releases)

## Data Availability
The dataset used in this study is publicly available in this GitHub repository and can be downloaded from the Releases section.

## License
This dataset is provided for academic research use only unless otherwise specified.
