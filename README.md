# Football Detection in Video using YOLOv8 and Deep SORT

This project demonstrates the use of YOLOv8 and Deep SORT for detecting and tracking a football in video footage. The custom data used for this project was annotated using Roboflow.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Usage](#usage)
- [Roboflow](#roboflow)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction

In this project, we employ the YOLOv8 model for detecting a football in video frames and the Deep SORT algorithm for tracking the detected football across the frames. This combination ensures robust and real-time object detection and tracking.

## Features

- **YOLOv8**: An advanced object detection model that is efficient and accurate.
- **Deep SORT**: An algorithm for multi-object tracking that combines Kalman filtering and Hungarian algorithm for data association.
- **Custom Data**: The dataset used for training the model was annotated using Roboflow.

## Usage

- **Clone the Repository**:
  ```bash
  git clone https://github.com/cizodevahm/football-detection.git
  ```
  - Run the ```Football__YOLOv8_Detection_Tracking_CustomData (2).ipynb``` file for training on custom data.
  - Change the model name if you want to experiment like yolov8m, yolov8s.

## Roboflow

[Roboflow](https://roboflow.com) is a platform that simplifies the process of collecting, annotating, and preparing image data for machine learning projects. With Roboflow, you can:

- Annotate Images: Easily annotate images using a user-friendly interface.
- Augment Data: Apply various augmentation techniques to enhance the dataset.
- Export Data: Export the annotated data in formats compatible with popular machine learning frameworks.

## Results

- Here are some sample results from our project:
![Alt text](FOOT.gif)

## Contributing

- Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

## License

- This project is licensed under the GPL-3.0 license. See the [LICENSE](LICENSE) file for more details.

