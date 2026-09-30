````markdown
# Furniture Object Detection using YOLOv8

A computer vision project that uses YOLOv8 to detect and localize furniture objects in images. The model is trained on a custom dataset containing three classes: Chair, Sofa, and Table.

## Project Overview

This project demonstrates the development of a custom object detection model using YOLOv8. The workflow includes dataset preparation, model training, validation, and object detection on images.

The model was implemented using the Ultralytics YOLO framework and trained using Google Colab.

## Objectives

- Detect furniture objects in images.
- Train a custom YOLOv8 object detection model.
- Identify multiple object classes using bounding boxes.
- Evaluate the model using standard object detection metrics.
- Perform object detection on unseen images.

## Classes

The model detects the following three classes:

| Class ID | Class Name |
|----------|------------|
| 0 | Chair |
| 1 | Sofa |
| 2 | Table |

## Dataset

The custom dataset contains:

- 146 images
- 145 annotated object instances
- 3 object classes

The dataset was prepared with annotations suitable for YOLO-based object detection.

## Technologies Used

- Python
- YOLOv8
- Ultralytics
- PyTorch
- Google Colab

## Model Training

The YOLOv8 model was trained using the custom furniture dataset.

The training workflow included:

1. Dataset preparation and annotation
2. Dataset configuration
3. YOLOv8 model initialization
4. Model training
5. Model validation
6. Object detection on test images

## Evaluation Results

The trained model achieved the following results on the evaluation dataset:

| Metric | Result |
|--------|--------|
| Precision | 97.3% |
| Recall | 97.2% |
| mAP@50 | 98.7% |
| mAP@50-95 | 86.4% |

These results show that the model was able to detect the target furniture classes with high precision and recall.

## Project Structure

```text
yolov8-furniture-object-detection/
│
├── README.md
│
├── notebook/
│   └── YOLO_Object_Detection.ipynb
│
├── data/
│   └── data.yaml
│
├── results/
│   └── detection-results/
│
└── requirements.txt
````

## Installation

Clone the repository:

```bash
git clone https://github.com/Gaganbt03/yolov8-furniture-object-detection.git
cd yolov8-furniture-object-detection
```

Install the required Python packages:

```bash
pip install ultralytics torch torchvision opencv-python matplotlib
```

## How to Run

1. Clone the repository.
2. Install the required dependencies.
3. Open the project notebook using Google Colab or Jupyter Notebook.
4. Configure the dataset path.
5. Run the training cells.
6. Validate the trained model.
7. Run inference on test images.

The model generates bounding boxes, class labels, and confidence scores for detected furniture objects.

## Applications

The object detection approach used in this project can be applied to:

* Furniture recognition
* Automated inventory systems
* Smart retail applications
* Visual search systems
* Computer vision-based monitoring

## Future Improvements

* Increase the size and diversity of the dataset.
* Add additional furniture categories.
* Improve detection performance on complex backgrounds.
* Perform real-time object detection on video.
* Deploy the model as a web or desktop application.

## Author

**Gagan B T**

BE – Computer Science and Engineering
Atria Institute of Technology, Bengaluru

GitHub: https://github.com/Gaganbt03

````
