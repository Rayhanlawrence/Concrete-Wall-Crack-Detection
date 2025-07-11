
# Crack Detection Web Application

This is a Flask-based web application for detecting cracks in images using a Convolutional Neural Network (CNN) model. Users can upload images, and the app will analyze them to determine whether cracks are present.

## Features

- Upload images in PNG, JPG, or JPEG format (up to 5 MB).
- Automatic image preprocessing and crack detection using a trained CNN model.
- Clear indication of detection results with confidence scores.
- Multiple web pages including home, image testing, about, contact, and example results.
- Simple and user-friendly interface.

## Installation

1. Clone this repository:
   ```
   git clone <repository-url>
   ```
2. Navigate to the project directory:
   ```
   cd <project-directory>
   ```
3. Create and activate a virtual environment (optional but recommended):
   ```
   python -m venv venv
   source venv/bin/activate  # On Windows use: venv\Scripts\activate
   ```
4. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```

## Usage

1. Run the Flask application:
   ```
   python app.py
   ```
2. Open your web browser and go to:
   ```
   http://127.0.0.1:5000/
   ```
3. Use the "Test Image" page to upload an image and get crack detection results.

## File Structure

```
.
├── app.py                      # Main Flask application
├── model/
│   └── crack_detection_model.h5  # Pre-trained CNN model
├── static/
│   ├── styles.css              # CSS styles
│   └── uploads/                # Uploaded images storage
├── templates/                  # HTML templates for web pages
│   ├── base.html
│   ├── index.html
│   ├── uji_gambar.html
│   ├── tentang.html
│   ├── kontak.html
│   └── hasil_contoh.html
├── requirements.txt            # Python dependencies
└── README.md                  # This file
```

## Technologies Used

- Python 3
- Flask
- TensorFlow / Keras
- Pillow (PIL)
- HTML/CSS

=======
# Dataset
https://www.kaggle.com/datasets/arunrk7/surface-crack-detection

#Demo Result
A brief demonstration of the Concrete Wall Crack Detection interface built with Flask:

https://github.com/user-attachments/assets/fa5fd624-23f3-47f6-a510-694260ae526a


