# CERA-Demo

This repository contains script for a working demo of the models found in the [Pole-Validation](https://github.com/kellyhpark/Pole-Validation) repository. By running the app.py file, a streamlit application of the demo will become accessible. This demonstration site has been created to display the rudimentary capabilities of the DETR Object Detection Model, and the two NLP models involved in the conception of the CERA platform.

## Setup

### Conda Environment
After cloning the repo, navigate to root folder and run:
```
pip install -r requirements.txt
```

### CERA Model Demo
Run the CERA Model Demo page by running the following after setup is complete:
```
streamlit run app.py
```

## Project Structure

```
├── models/
│   ├── detr/
│   |   ├── raw/
│   |   ├── results/
│   |   ├── svm_model.pkl
|   |── app.py
|   |── requirements.txt
|   |── README.md
```
