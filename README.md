# Augmented Reality Cube with ARuco Codes

Welcome to the Augmented Reality Cube with ARuco Codes project! This repository contains code for creating an augmented reality cube using ARuco markers. The project utilizes computer vision techniques to detect ARuco markers in a camera feed and overlays a virtual cube onto the detected markers, creating an immersive augmented reality experience.

## Features

- Detection of ARuco markers in pictures.
- Accurate pose estimation of detected markers.
- Rendering of a virtual cube overlaid onto detected markers.
- Integration with camera calibration matrix for precise marker pose estimation.

## Prerequisites

Before running the application, ensure you have the following installed:

- Python (version 4.6.0.66)
- OpenCV 
- Numpy

Along with this, 
  
## Setup

This code works on python version 4.6.0.66. To use it please run below mentioned command on terminal.

```pip
  pip install opencv-contrib-python==4.6.0.66
```

## Directory Structure

- `src/`: Contains source code for the AR cube application.
- `data/`: Includes sample ARuco codes and camera calibration matrix.
- `docs/`: Documentation related to the project.
- `LICENSE`: License information for the project.
- `README.md`: This file.

## Limitations
- This is not real time. Although can be made into one.
- Camera calibration matrix is manually added therefore the code will run only for the specific camera in the said picture. Could be altered in a way where calibration matrix is found automatically. Refer the repositry mentioned here to find the calibration matrix:

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
