
# Face-recognition-GUI
=======
# Face Recognition GUI Application

## Overview
This project is a Face Recognition GUI Application that provides functionalities for face detection, dataset creation, classifier training, and gender prediction. It is built using Python and leverages machine learning models for face recognition and gender prediction.

## Features
- **Face Detection**: Detect faces in images using Haar Cascade.
- **Dataset Creation**: Create a dataset of faces for training.
- **Classifier Training**: Train a face recognition classifier.
- **Gender Prediction**: Predict gender using pre-trained models.
- **Graphical User Interface**: User-friendly GUI for easy interaction.

## Project Structure
```
Face-Recognition-GUI-Application-main
├── app-gui.py                # Main GUI application
├── create_classifier.py      # Script to create classifier
├── create_dataset.py         # Script to create dataset
├── Detector.py               # Face detection logic
├── gender_prediction.py      # Gender prediction logic
├── requirements.txt          # Python dependencies
├── data/
│   ├── DownloadModels.txt    # Instructions to download models
│   ├── haarcascade_frontalface_default.xml  # Haar Cascade model
│   ├── classifiers/          # Trained classifiers
│   │   ├── chandu_classifier.xml
│   │   └── readme.txt
├── nameslist.txt             # List of names for dataset
├── homepagepic.png           # Homepage image for GUI
├── icon.ico                  # Icon for the application
├── LICENSE                   # License file
```

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Face-Recognition-GUI-Application.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Face-Recognition-GUI-Application-main
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. Run the GUI application:
   ```bash
   python app-gui.py
   ```
2. Follow the instructions in the GUI to:
   - Create a dataset.
   - Train a classifier.
   - Perform face detection.
   - Predict gender.

## Requirements
- Python 3.11 or higher
- Required Python packages (listed in `requirements.txt`)

## License
This project is licensed under the MIT License. See the `LICENSE` file for details.

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request.

## Acknowledgments
- OpenCV for face detection.
- Pre-trained models for gender prediction.

## Contact
For any inquiries, please contact [your email address].
>>>>>>> 0419d33 (Initial commit: Face Recognition GUI Application)
