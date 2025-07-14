CDW Waste Segmentation with U-Net

This project focuses on class-wise segmentation of construction and demolition waste using a deep learning model. The dataset includes real images of waste materials along with annotation files in JSON format. The goal is to train a U-Net model that can predict a segmentation mask and classify different waste types at the pixel level.

Only the original_images_annotations folder was used in this project. It contains JPG images and their matching JSON annotation files.

Files included:

- IDS-FinalProject.ipynb – the main Jupyter Notebook with full code

- Files/original_images_annotations – the image and annotation dataset used for training and testing

To run the notebook:

Place the original_images_annotations folder in the same directory as the notebook

Open CDW_Segmentation_Project.ipynb in Jupyter Notebook

Run the cells step by step to see the full pipeline: data loading, preprocessing, model training, and evaluation

----------------------------------------------------------
To install the required Python libraries, use this command:
pip install tensorflow opencv-python matplotlib numpy
----------------------------------------------------------

This project demonstrates the use of computer vision and deep learning for waste detection and segmentation in complex environments using U-Net architecture.