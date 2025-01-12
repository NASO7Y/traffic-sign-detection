
# Traffic Sign Detection

This project implements a comprehensive Traffic Sign Detection system using advanced computer vision and deep learning techniques. The application identifies and classifies traffic signs in images and video streams, contributing to safer driving environments and aiding the development of driver assistance systems and autonomous vehicles.

---

## Table of Contents

- [About the Project](#about-the-project)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Dataset](#dataset)
- [Model Architecture](#model-architecture)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Future Enhancements](#future-enhancements)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)

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

This project utilizes the [LISA Traffic Sign Dataset](https://git-disl.github.io/GTDLBench/datasets/lisa_traffic_sign_dataset/), which contains annotated images of traffic signs observed in North America. The dataset is diverse, containing variations in lighting, weather conditions, and perspectives.

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
3. **Create a virtual environment:**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
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

## Future Enhancements

- **Support for Additional Datasets**: Include European or Asian traffic sign datasets.
- **Integration with YOLO or Faster R-CNN**: Enhance real-time detection capabilities.
- **Mobile Deployment**: Develop a lightweight version for mobile applications.

---

## Contributing

Contributions are highly encouraged! Follow these steps to contribute:

1. Fork the repository.
2. Create a feature branch (`git checkout -b feature-branch-name`).
3. Commit changes (`git commit -m "Add new feature"`).
4. Push to the branch (`git push origin feature-branch-name`).
5. Open a pull request.

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## Acknowledgments

- [LISA Traffic Sign Dataset](https://git-disl.github.io/GTDLBench/datasets/lisa_traffic_sign_dataset/) for the dataset.
- [TensorFlow](https://www.tensorflow.org/) and [Keras](https://keras.io/) for deep learning support.
- [OpenCV](https://opencv.org/) for image processing tools.

---

Thank you for exploring this project. Feel free to reach out for questions or feedback!
