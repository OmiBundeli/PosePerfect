# PosePerfect - AI Exercise Form Analysis System

PosePerfect is an AI-powered system that analyzes exercise form in real-time using computer vision and machine learning. It provides instant feedback on proper technique for squats, deadlifts, and overhead presses.

## Features

- 🏋️ Real-time exercise form analysis
- 📊 Detailed feedback on technique errors
- 🤖 Multiple ML models for different exercises
- 📈 Performance history tracking
- 📱 Web-based interface (live camera or video upload)

## Technologies

- **Computer Vision**: MediaPipe Pose Estimation
- **Machine Learning**: Random Forest, SVM, Gradient Boosting
- **Backend**: Flask, MongoDB
- **Frontend**: HTML5, CSS3, JavaScript

## Getting Started

### Prerequisites

- Python 3.8+
- MongoDB (for history tracking)
- Webcam (for live analysis)

### Installation

1. Clone the repository:
'''bash'''
git clone https://github.com/yourusername/PosePerfect.git
cd PosePerfect

2. Install dependencies:
   pip install -r requirements.txt

3. Set up MongoDB:
  Install and run MongoDB locally
  Create a database named pose_app

## Usage
Run the Flask application:

python app/Flask.ipynb

Access the web interface at http://localhost:5000

 ### Choose an exercise and analysis mode:
  Live camera
  Video upload
  Image analysis

## Dataset Information
The system was trained on a proprietary dataset of exercise videos. If you're interested in the dataset for research purposes, please email me at [omibundeli13@gmail.com].

### The dataset includes:
  Correct and incorrect form samples
  Multiple angles and body types

## Project Structure
PosePerfect/
├── dataset/                  # Your local dataset (not uploaded)
├── saved_models/             # Trained models
├── Feature.ipynb             # Feature extraction code
├── Train_Model.ipynb         # Model training code
├── Flask.ipynb               # Flask application(includes html and css)
├── README.md                 # Project documentation
└── requirements.txt          # Python dependencies

## Contributing
Contributions are welcome! Please fork the repository and create a pull request with your improvements.

## Important Notes
- Dataset is not included
- Uploaded already trained models so that you can direct run the flask script(pre-trained models)
