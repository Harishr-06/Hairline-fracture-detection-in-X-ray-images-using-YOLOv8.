Automated Detection of Subtle Hairline Fractures in X-ray Images Using Deep Learning

This project presents a deep learning-based system for the automated detection of subtle hairline fractures in musculoskeletal X-ray images. Hairline fractures are often difficult to identify because of their thin appearance, low contrast, and minimal displacement. The proposed system uses the YOLOv8 object detection model to accurately identify fracture regions and assist radiologists by providing reliable predictions with confidence scores and localized bounding boxes.

Overview

The objective of this project is to develop an intelligent fracture detection system that improves early diagnosis and reduces the possibility of missed fractures during manual examination. The model combines image preprocessing techniques with deep learning to enhance fracture visibility and improve detection performance.

Features

• Automated detection of hairline fractures from X-ray images
• YOLOv8-based deep learning model for object detection
• Image preprocessing and enhancement
• Bounding box localization of fracture regions
• Confidence score prediction
• Data augmentation for improved model generalization
• Performance evaluation using standard detection metrics

Dataset

The model is trained using annotated musculoskeletal X-ray images containing both fractured and non-fractured samples. The dataset is divided into training, validation, and testing subsets. Data augmentation techniques such as image rotation, flipping, scaling, cropping, and contrast enhancement are applied to improve model performance and reduce overfitting.

Workflow

1. Collect X-ray images.
2. Perform image preprocessing and enhancement.
3. Apply data augmentation.
4. Train the YOLOv8 model.
5. Detect fracture regions.
6. Generate bounding boxes and confidence scores.
7. Evaluate model performance.

Technologies Used

Programming Language:
Python

Framework:
Ultralytics YOLOv8

Libraries:
OpenCV
NumPy
Pandas
Matplotlib
Scikit-learn
PyTorch
Torchvision
Pillow

Development Environment:
Jupyter Notebook

Installation

Clone the repository:

```bash
git clone https://github.com/Harishr-06/Hairline-Fracture-Detection.git
```

Navigate to the project directory:

```bash
cd Hairline-Fracture-Detection
```

Install the required packages:

```bash
pip install -r requirements.txt
```

Usage

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open and run:

```
fracture(2).ipynb
```

Results

The trained YOLOv8 model demonstrated effective fracture detection performance.

Performance Metrics:

Precision: 82.56%

Recall: 70.40%

Bounding Box mAP@0.5: 77.54%

Segmentation mAP@0.5: 74.79%

Bounding Box mAP@0.5:0.95: Approximately 42%

Segmentation mAP@0.5:0.95: 32.66%

The model successfully detects most visible fracture regions while maintaining high precision. Detection of extremely faint hairline fractures remains an area for future improvement. :contentReference[oaicite:0]{index=0}

Project Structure

```
Hairline-Fracture-Detection
│
├── fracture(2).ipynb
├── README.md
├── requirements.txt
├── dataset
│   ├── train
│   ├── valid
│   └── test
├── runs
├── results
├── images
└── LICENSE
```

Future Work

Future improvements include expanding the dataset with more diverse clinical images, improving sensitivity for extremely subtle fractures, incorporating attention-based architectures and transformer models, optimizing the system for real-time deployment, and integrating explainable AI techniques such as Grad-CAM to improve model interpretability. :contentReference[oaicite:1]{index=1}

Author

Harish R

B.Tech Computer Science and Engineering (Artificial Intelligence and Data Science)

VELS Institute of Science, Technology & Advanced Studies (VISTAS)

