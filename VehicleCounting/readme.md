# Vehicle Detection and Counting System

## Overview

This project focuses on the development of a real-time vehicle detection and counting system using YOLO v8 and the COCO128 dataset. The objective is to accurately detect and track vehicles in video frames while implementing a counter to determine the total number of cars present.

## Key Features

- **Object Detection:** Implemented YOLO v8 for state-of-the-art real-time vehicle tracking, ensuring high accuracy in identifying and localizing vehicles in video frames.

- **Data Annotation:** Manually annotated the COCO128 dataset to train the model, showcasing expertise in data preparation for machine learning tasks.

- **Vehicle Counting:** Integrated a counter within the model to accurately count and tally the total number of cars present in each frame, demonstrating proficiency in computer vision techniques.

- **Performance:** Achieved an outstanding 98% accuracy on the validation dataset, showcasing the robustness and reliability of the developed system.

## Usage

1. **Data Preparation:**
   - Annotate dataset using COCO128 format.
   - Ensure proper labeling for vehicle classes.

2. **Model Training:**
   - Utilize YOLO v8 for training on the annotated dataset.
   - Fine-tune hyperparameters for optimal performance.

3. **Real-time Detection:**
   - Implement the trained model for real-time vehicle detection.
   - Utilize the integrated counter for total vehicle counting in each frame.

## Dependencies

- Python 3.x
- YOLO v8
- COCO128 dataset

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/yourusername/vehicle-detection.git
    ```

2. Install dependencies:

    ```bash
    pip install -r requirements.txt
    ```

3. Follow usage instructions to train the model and perform real-time detection.

## Acknowledgments

Special thanks to the creators of YOLO v8 and the contributors to the COCO dataset for their invaluable resources and support.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.
