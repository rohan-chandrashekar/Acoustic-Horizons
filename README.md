# Acoustic Horizons

**Disclaimer:**  
This project is currently under consideration for a patent. As a result, the full code has not been made available to the public. Only parts of the implementation and documentation are included in this repository for demonstration purposes.

## Overview

This project aims to develop a bone conduction headset equipped with dual ESP32 cameras to assist visually impaired individuals in navigating their surroundings. The headset leverages advanced computer vision techniques, including object detection and scene analysis, to provide real-time feedback to the user.

### Key Features

- **Bone Conduction Technology:** The headset uses bone conduction to transmit audio feedback directly to the user's inner ear, allowing them to remain aware of their surroundings while receiving guidance.
- **ESP32 Cameras:** The device is mounted with two ESP32 cameras for capturing the environment from different angles, enhancing the field of view and depth perception.
- **YOLO-Based Object Detection:** The system is trained on the YOLO (You Only Look Once) dataset, enabling it to identify and classify objects in real time with high accuracy.
- **Scene Detection and Analysis:** Beyond object detection, the system can analyze entire scenes, providing the user with contextual information about their environment.

## Project Structure

- **`src/`**: Contains Python scripts and modules for processing the camera input, running object detection, and generating audio feedback.
- **`models/`**: Includes pre-trained YOLO models used for object detection.
- **`data/`**: Placeholder for datasets used in training and testing. (Data files are not included in this repository.)
- **`hardware/`**: Documentation and schematics related to the ESP32 camera setup and bone conduction headset assembly.
- **`notebooks/`**: Jupyter notebooks used for model training, validation, and experimentation.
