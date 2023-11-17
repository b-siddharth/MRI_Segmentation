Image Segmentation with U-Net
This repository contains code for a U-Net-based image segmentation project. The main components of the project are implemented in three files: main.ipynb, unet.py, and utils.py. Below is an overview of each file's contents:
Files
1. main.ipynb
The main Jupyter Notebook file, main.ipynb, contains the core implementation of the image segmentation project. Key functionalities include:
Importing necessary libraries for image processing and machine learning (e.g., TensorFlow, OpenCV).
Loading and preprocessing image and mask data for segmentation.
Implementing a U-Net architecture for image segmentation.
Defining data generators for training and validation sets.
Training the U-Net model with specified parameters.
Evaluating the model on a test set and visualizing the results.
2. unet.py
The unet.py file contains the implementation of the U-Net architecture. This file is imported in the main notebook for utilizing the U-Net model. The U-Net architecture is a popular choice for image segmentation tasks.
3. utils.py
The utils.py file includes utility functions used in the project. Some of the functions include:
plot_from_img_path: Plots a grid of images and their corresponding masks from given lists of image and mask paths.
Various metrics functions for model evaluation, such as dice_coefficients, iou, and jaccard_distance.
Other utility functions for data manipulation and visualization.
Usage
To run the code in this repository, follow these steps:
Install the required libraries: pip install -r requirements.txt (if you have a requirements file).
Open and run the main.ipynb notebook.
Dependencies
List of main dependencies and their versions:
Python (>=3.6)
TensorFlow (>=2.0)
NumPy (>=1.16)
OpenCV (>=4.0)
Matplotlib (>=3.0)
scikit-image (>=0.15)
Acknowledgments
Give credit to any resources, tutorials, or third-party code that you used in your project.
License
Specify the license under which your project is distributed.
Issues
If you encounter any issues or have suggestions for improvement, please open an issue on the GitHub repository.
