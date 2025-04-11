# Task 04: Hand Gesture Recognition

## Description
This project implements a **Convolutional Neural Network (CNN)** to recognize and classify **hand gestures** from images. This can be used for gesture-based control systems and human-computer interaction.

## Dataset
- **Dataset Name**: LeapGestRecog
- **Source**: [Kaggle](https://www.kaggle.com/gti-upm/leapgestrecog)
- The dataset contains images of various hand gestures captured using the Leap Motion Controller.

## Requirements
- Python 3.x
- Libraries:
  - tensorflow
  - numpy
  - pandas
  - matplotlib
  - sklearn

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/hand-gesture-recognition.git
   cd hand-gesture-recognition
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Download the dataset from [Kaggle](https://www.kaggle.com/gti-upm/leapgestrecog) and organize it in the `data/` directory.
4. Run the script:
   ```bash
   python gesture_recognition.py
   ```
5. View the results, including gesture classification accuracy.

## Output
- Classification of hand gestures into predefined categories.
- Accuracy and performance metrics of the model.

## License
This project is licensed under the MIT License.
