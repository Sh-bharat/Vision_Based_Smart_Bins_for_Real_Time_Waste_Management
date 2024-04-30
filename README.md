# Vision_Based_Smart_Bins_for_Real_Time_Waste_Management

## Overview
This repository contains code and resources for a dustbin detection and classification system using YOLOv8. The system comprises a single YOLOv8 model trained for both dustbin detection and status classification. The model is capable of detecting the presence of dustbins in real-time surveillance footage and classifying their status (full or not full) based on images captured from different angles.

## Key Features
- Detection of dustbins from real-time surveillance footage.
- Classification of dustbin status (full or not full) for efficient waste management.
- Alert system: Sends alerts when a dustbin is detected as full, prompting timely action for emptying.

## Training Data
The model is trained using a diverse dataset of dustbin images, including:
- Images captured from various angles to simulate CCTV camera viewpoints.
- Images with different lighting conditions (bright, low light, and dark).
- Images of dustbins filled to different levels to train the classification model.

## Requirements
- Python 3.x
- TensorFlow
- OpenCV
- YOLOv8 (implementation details and pre-trained weights included)

## Usage
1. Clone this repository to your local machine.
2. Install the required dependencies.
3. Run the detection and classification scripts.
4. Customize the alert system as needed for your environment.

## Results

* Detection Model![results](https://github.com/Sh-bharat/Vision_Based_Smart_Bins_for_Real_Time_Waste_Management/assets/133742551/8067aaff-2740-4c41-81ad-ff47300333cc)
Outputs![val_batch0_labels](https://github.com/Sh-bharat/Vision_Based_Smart_Bins_for_Real_Time_Waste_Management/assets/133742551/12ebf2ed-ee7f-4bf0-ac5c-7aca508835d4)

* Classification Model![results](https://github.com/Sh-bharat/Vision_Based_Smart_Bins_for_Real_Time_Waste_Management/assets/133742551/8c3f69c0-b898-434f-8679-f985c1a60f58)
Outputs![Output](https://github.com/Sh-bharat/Vision_Based_Smart_Bins_for_Real_Time_Waste_Management/assets/133742551/ac3f1f92-7170-4d09-b988-c2f70b565cf5)




## Contributing
Contributions are welcome! If you have any suggestions, bug fixes, or improvements, feel free to open an issue or submit a pull request.

## Acknowledgments
Special thanks to the contributors of the YOLOv8 implementation used in this project.
