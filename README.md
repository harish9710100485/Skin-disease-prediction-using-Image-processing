# Skin Disease Prediction using Image Processing

## Overview

Skin diseases are a common health issue, and early detection is crucial for effective treatment. This project utilizes image processing techniques and machine learning to predict skin diseases based on images. By analyzing skin lesions and patterns, the system aims to provide an accurate and fast diagnosis to assist healthcare professionals and patients.

## Features

- **Automated Skin Disease Detection**: Predicts skin conditions from images using machine learning.
- **Image Preprocessing**: Enhances and segments images for better analysis.
- **Deep Learning Model**: Uses Convolutional Neural Networks (CNNs) for high accuracy.
- **User-friendly Interface**: Simple UI for uploading and analyzing skin images.
- **Real-time Predictions**: Provides immediate feedback on uploaded images.

## Technologies Used

- Python
- OpenCV
- TensorFlow/Keras
- Flask (for web interface)
- NumPy & Pandas
- Matplotlib (for visualization)

## Installation & Usage

1. Clone the repository:
```sh
git clone https://github.com/username/skin-disease-prediction.git
```

2. Navigate to the project directory:
```sh
cd skin-disease-prediction
```

3. Install dependencies:
```sh
pip install -r requirements.txt
```

4. Run the application:
```sh
python app.py
```

5. Open your browser and go to:
```sh
http://127.0.0.1:5000/
```

6. Upload an image and get predictions.

## Dataset

The model is trained using publicly available skin disease image datasets, ensuring diverse and accurate predictions.

## Screenshots

![Upload Image Page](./assets/upload_page.png)
*Figure 1: Upload Image Page*

![Prediction Result](./assets/prediction_result.png)
*Figure 2: Prediction Result*

## Future Enhancements

- Improve model accuracy with a larger dataset
- Mobile application integration
- Multi-class classification for more skin conditions
