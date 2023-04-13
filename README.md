# Grocery Store Sales Time Series Model Prediction

## Installation

To setup and run this project you need to have [`Python3`](https://www.python.org/) installed on your system. Then you can clone this repo. At the repo's root, use the code from below which applies:

- Windows:

        python -m venv venv; venv\Scripts\activate; python -m pip install -q --upgrade pip; python -m pip install -qr requirements.txt  

- Linux & MacOs:

        python3 -m venv venv; source venv/bin/activate; python -m pip install -q --upgrade pip; python -m pip install -qr requirements.txt  

    **NB:** For MacOs users, please install `Xcode` if you have an issue.

You can then run the app (still at the repository root) with:

      streamlit run streamlit_project/basic_demo/app.py

Ideally, it should open your browser with the app in a new tab, if it doesn't, type this address in your browser:

      http://localhost:8501

## Brief Introduction

This project is about streamlit library to build data web apps. 
The machine learning model is embedded into an interacted interface that allow our notebook to interact with the backend code.
The main aim is to have have nice personalised interface that makes it easier for clients to interact with an Machine Learning Model,irrespective of their understanding
in machine learning

## Methodology

 -Export machine learning,encoder and scaler from the notebook
- Import the machine learning, encoder and scaler into the app script
- Develop the interface
- Write backend code to process inputs dictionary
- Pass values through the interface
- Apply the necessary processing
- Submit the processed values to the ML model to make the predictions
- Process the predictions and display them on the interface

## Screenshots

![Initial Interface](https://user-images.githubusercontent.com/119458164/231795449-e341ddba-b515-4547-a0a5-2169143136a0.PNG)
![Dataset](https://user-images.githubusercontent.com/119458164/231795659-7fdd3e67-e805-4046-ba1c-44ca06913606.PNG)
![User Input](https://user-images.githubusercontent.com/119458164/231795816-e4a8a101-842d-4dd0-aad8-a09366313284.PNG)
![Model Prediction](https://user-images.githubusercontent.com/119458164/231795917-006a7b99-15c8-44eb-9c6f-cc02b1b8b35c.PNG)
![Model appreciation](https://user-images.githubusercontent.com/119458164/231796032-38904151-1d7d-4273-8cbc-152348af6f83.PNG)




