
# Traffic Sign Detection

This project implements a comprehensive Traffic Sign Detection system using advanced computer vision and deep learning techniques. The application identifies and classifies traffic signs in images and video streams, contributing to safer driving environments and aiding the development of driver assistance systems and autonomous vehicles.


---

## About the Project

The Traffic Sign Detection system is designed to process visual data and detect various traffic signs efficiently. The project aims to serve as a stepping stone for integrating traffic sign detection into real-time autonomous systems.

## Features

- **Accurate Detection**: Detects multiple traffic sign classes with high precision.
- **Real-Time Capabilities**: Process video feeds for real-time detection.
- **Scalable**: Extendable to more classes or custom datasets.
- **Cross-Platform**: Works on various platforms with minimal configuration.

## Technologies Used

- **Programming Language**: Python
- **Deep Learning Frameworks**: TensorFlow, Keras
- **Image Processing Library**: OpenCV
- **Visualization Tools**: Matplotlib, Seaborn
- **Dataset Source**: [LISA Traffic Sign Dataset](https://git-disl.github.io/GTDLBench/datasets/lisa_traffic_sign_dataset/)

## Dataset

if you are interested to use the  : [Dataset](https://www.kaggle.com/datasets/meowmeowmeowmeowmeow/gtsrb-german-traffic-sign), which contains annotated images of traffic signs observed. The dataset is diverse, containing variations in lighting, weather conditions, and perspectives.

---

## Model Architecture

The detection model leverages a Convolutional Neural Network (CNN) architecture. Key layers include:

1. **Convolutional Layers**: Extract spatial features from images.
2. **Pooling Layers**: Reduce feature dimensions for computational efficiency.
3. **Fully Connected Layers**: Classify traffic signs based on extracted features.
4. **Softmax Output Layer**: Provides probabilities for each class.

---

## Installation

To set up the project locally, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/NASO7Y/traffic-sign-detection.git
   ```
2. **Navigate to the project directory:**
   ```bash
   cd traffic-sign-detection
   ```

4. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

---

## Usage

### Step 1: Prepare Input Data
- Images: Place in the `input_images` directory.
- Videos: Place in the `input_videos` directory.

### Step 2: Run the Detection Script
Execute the script with the following command:
```bash
python detect_traffic_signs.py --input path_to_input --output path_to_output
```
Replace `path_to_input` with the input file or directory path and `path_to_output` with the desired output directory.

### Step 3: View Results
- Processed outputs (annotated images/videos) will be saved in the specified output folder.

---

## Results

The model demonstrates:

- **Training Accuracy**: 98%
- **Test Accuracy**: 95%
- **Detection Speed**: Processes up to 10 frames per second on a standard GPU.



---

## Contributing

Contributions are highly encouraged! Follow these steps to contribute:

1. Fork the repository.
2. Create a new branch for your feature.
3. Commit your changes and submit a pull request.
   
---

## Acknowledgments

- [LISA Traffic Sign Dataset](https://git-disl.github.io/GTDLBench/datasets/lisa_traffic_sign_dataset/) for the dataset.
- [TensorFlow](https://www.tensorflow.org/) and [Keras](https://keras.io/) for deep learning support.
- [OpenCV](https://opencv.org/) for image processing tools.

---
## Contact

GitHub: naso7y

Email: ahmed.noshy2004@gmail.com

LinkedIn: [LinkedIn](https://www.linkedin.com/in/nos7y/)

Thank you for exploring this project. Feel free to reach out for questions or feedback!
