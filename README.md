# SMS Spam Detector

## Project Overview
This project involves refactoring code from an existing SMS text classification solution into a function that constructs a linear Support Vector Classification (SVC) model. Once the model is created and trained, it is deployed into a Gradio application that allows users to input text messages and receive feedback indicating whether the text is classified as spam or not.

## Features
- **SMS Classification Function**: Builds and trains a linear SVC model on SMS data.
- **SMS Prediction Function**: Predicts whether a new text message is spam or not.
- **Gradio Interface Application**: Provides a user-friendly web interface for real-time SMS spam detection.

## Installation
### Ensure you have Python installed on your system. You can install the project dependencies using pip:
pip install -r requirements.txt
pip install pandas scikit-learn gradio
### Cloned the repository to your local machine. Follow these steps to set up the project:
1. **Clone the repository**:
   git clone https://github.com/Tasnyde/sms_spam_detector
2. **Navigate to the project directory:r**:
   cd sms_spam_detector
3. **Install required Python packages**:
   pip install -r requirements.txt 
4. Install additional dependencies:
   pip install pandas scikit-learn gradio


## Functionality
1. **`sms_classification(sms_text_df)`**: This function builds and trains a text classification pipeline using the provided DataFrame. It sets up a TF-IDF vectorizer and a LinearSVC model, splits the data, and returns the trained model.
2. **`sms_prediction(text)`**: This function predicts whether a new text message is spam or not based on the trained model.

## Usage
To run the SMS Spam Detector:
1. Launch the Jupyter Notebook:
2. Follow the instructions within the notebook to load your data, train the model, and start the Gradio app. The specific commands and steps to execute these operations are detailed in the notebook.
## Testing
Test the application using sample text messages provided in the challenge instructions, such as:
"You are a lucky winner of $5000!"
"You won 2 free tickets to the Super Bowl."
## Contributing
This project benefits from the contributions of:
- edX Boot Camps LLC - Educational partner providing guidance and resources
## Authors
- **edX Boot Camps** - *Initial work*
- **Todd Snyder** - *Final work*
## License
This project is not licensed and is available for educational and non-commercial use only.


 
