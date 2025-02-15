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
The model is trained on a dataset of images containing marine trash. Ensure your dataset follows this structure:
```
/data
  /train
    /plastic
    /metal
    /wood
    /other
  /test
    /plastic
    /metal
    /wood
    /other
```

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

