# License Plate Detection

This repository contains the code and resources for a project focused on detecting license plates using the YOLOv3 model. The project includes scripts for training, detecting license plates in images and videos, and the necessary dependencies.

## Repository Structure

- `detect.py`: Python script for detecting license plates using the trained YOLOv3 model.
- `train.py`: Python script for training the YOLOv3 model on the license plate dataset.
- `realvideo (1).mp4`: Sample video file for tested model for the license plate detection.
- `requirements (1).txt`: File containing the required dependencies for the project.

## Getting Started

To get started with this project, clone the repository and install the necessary dependencies. The following instructions will help you set up your environment and run the scripts.

### Prerequisites

- Python 3.7 or higher
- TensorFlow
- OpenCV
- NumPy
- Pandas

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/jhanvi-29/License-Plate-Detection.git
   cd License-Plate-Detection
2. python train.py
3. python detect.py --video path/to/your/video.mp4
   
