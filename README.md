# Sea Trash Detection

## Overview
This project focuses on detecting trash in the sea using deep learning. The model is trained on image datasets to identify and classify different types of marine debris.

## Features
- Uses deep learning for image-based trash detection
- Trained on a dataset containing marine waste
- Implements data preprocessing and augmentation
- Provides model training, evaluation, and prediction functionalities

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/sea-trash-detection.git
   cd sea-trash-detection
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Dataset
The model is trained on a dataset of images containing marine trash and other objects. Ensure your dataset follows this structure:
```
/trash_inst_material
  /train/images
  /val/images
```
### Class Labels
The dataset consists of the following categories:
- **rov**
- **plant**
- **animal_fish**
- **animal_starfish**
- **animal_shells**
- **animal_crab**
- **animal_eel**
- **animal_etc**
- **trash_etc**
- **trash_fabric**
- **trash_fishing_gear**
- **trash_metal**
- **trash_paper**
- **trash_plastic**
- **trash_rubber**
- **trash_wood**

## Labeling using Roboflow
The dataset annotation was performed using Roboflow. Follow these steps to label your own dataset:
1. **Create a Roboflow Account**: Sign up at [Roboflow](https://roboflow.com/).
2. **Upload Images**: Create a new project and upload your dataset images.
3. **Annotate Images**: Use the annotation tool to label objects manually or use Roboflow's auto-labeling features.
4. **Generate Dataset**: Once labeling is complete, export the dataset in your preferred format (e.g., YOLO, COCO, Pascal VOC).
5. **Download and Use**: Download the labeled dataset and integrate it into your project for training.

## Usage
Run the Jupyter Notebook to train and evaluate the model:
```bash
jupyter notebook Sea_trash_detection.ipynb
```

## Model
The model is based on a convolutional neural network (CNN) for image classification. It goes through:
- Data preprocessing
- Model training with augmentation
- Evaluation on test data

## Results
The trained model outputs predictions highlighting detected trash objects in images.

## License
This project is open-source and licensed under [MIT License](LICENSE).

