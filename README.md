# idl-project
Code files for 11785 Introduction to deep learning project


The file for downloading the dataset is given here:
[Dataset Downloading and preparation](https://github.com/RDjarbeng/idl-project/blob/main/downloading-dataset.ipynb)

Take note to use the faceforensics++ dataset requires permissions from the authors of the paper.

# FaceSwap Dataset Downloading and preparation

This code is used to prepare a dataset for FaceSwap, including downloading and organizing videos and images.

## Code Overview
The code creates a directory called "dataset" and sets the necessary permissions.
It downloads FaceSwap videos and masks from the EU2 server.
The code creates directories for training, testing, and validation data.
It moves the downloaded videos to the respective directories based on their category (original or altered).
The code also moves the masks to the corresponding directories.
It creates a directory for FaceSwap images and splits them into train, test, and validation sets.
Finally, the code extracts images from the dataset, crops them, and saves them in the FaceSwap images directory.
## Instructions
Before running the code, ensure that the required dependencies are installed.
Make sure to set the appropriate permissions for the dataset directory.
Adjust the number of videos and images to be downloaded, if needed.
Modify the server location if necessary.
## External Files
The code relies on the "Faceforencic_download_script.py" script for downloading videos.
The "extract_images.py" script is used to extract and crop images from the dataset.
