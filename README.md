
# Plant Disease Detection Using CNN with ResNet

## Overview
This project leverages the power of Convolutional Neural Networks (CNN) and the ResNet architecture to accurately identify and diagnose up to 40 different plant diseases, focusing on wheat and various other crops. Integrated within a user-friendly mobile application developed with Flutter, this tool aims to assist farmers, agricultural professionals, and hobbyists in early disease detection and management through simple camera snapshots.

## Features
- **Disease Detection**: Utilizes a CNN with ResNet model to identify 40 different plant diseases with high accuracy.
- **Mobile Application**: Built using Flutter, ensuring cross-platform functionality on both iOS and Android devices.
- **Real-Time Analysis**: Offers instant disease diagnosis by analyzing images captured through the mobile app's camera.
- **User Guide**: Provides detailed information on disease symptoms, prevention, and treatment options.
- **Data Privacy**: Ensures user data and images are processed securely, with no personal information stored or shared.

## Getting Started

### Prerequisites
- Flutter (latest version)
- Dart (latest version)
- Python 3.6 or higher
- TensorFlow 2.x

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/plant-disease-detection-cnn-resnet.git
   ```
2. Install Python dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Navigate to the Flutter app directory and run:
   ```bash
   flutter pub get
   ```
4. Build the app for your target platform (iOS/Android):
   ```bash
   flutter build apk
   # or for iOS
   flutter build ios
   ```

## Usage
1. Open the mobile app on your device.
2. Grant camera permissions when prompted.
3. Capture an image of the affected plant leaf.
4. View the diagnosis results, along with disease information and recommended actions.

## Model Training
The CNN model with ResNet architecture was trained on a comprehensive dataset of leaf images, representing a wide range of diseases across wheat and other crops. For details on the training process, dataset, and model architecture, refer to the `training/` directory.

## Contributing
Contributions to the project are welcome! Please refer to CONTRIBUTING.md for guidelines on how to make a contribution.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments
- Thanks to the agricultural community for providing the dataset.
- Special thanks to all contributors for their invaluable input and feedback.
