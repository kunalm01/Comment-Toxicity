# Comment-Toxicity

## Introduction
This is a project that demonstrates the use of LSTM (Long Short-Term Memory) model for clickbait detection. The model is trained on a dataset of comments and their corresponding labels that indicate whether they are toxic or not.

## Installation
The following libraries are required to run this project:

  tensorflow  
  pandas  
  matplotlib  
  sklearn  
  numpy  
  gradio  
  jinja2  

You can install them using pip with the following command: pip install tensorflow pandas matplotlib sklearn numpy gradio jinja2

## Usage
1. Download or clone the project from GitHub.
2. Open a terminal or command prompt and navigate to the project directory.
3. Run the following command to train the model: python clickbait_detection.py
4. After training the model, you can use Gradio to interact with the model and score comments. To launch the Gradio interface, run the following command:           python gradio_interface.py
5. Enter a comment in the text box and click "Submit" to see the scores for each label.

## Credits
This project is created by Kunal Madan. The dataset used in this project is from https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge.
