# Sign Language Detection Model
Real-time detection model that identifies 5 common Sign Language phrases: 'Hello', 'Yes', 'No', 'I love you', 'Thank you' through live camera.

## Table of Contents
[Technologies](#Technologies)  
[Setup](#Setup)  

<a name="Technologies"/>

## Technologies
- [Tensorflow Object Detection API](https://tensorflow-object-detection-api-tutorial.readthedocs.io/en/latest/install.html)
- [LabelImg](https://github.com/HumanSignal/labelImg)

<a name="Setup"/>

## Setup

To run this project, clone the repository locally.

Open Jupyter Notebook and run the code cells in:
```
 Image Data Collection.ipynb
```

That should automatically prompt your webcam to collect images for the dataset.

Use [LabelImg](https://github.com/HumanSignal/labelImg) to manually label and gather data from our images based on the 5 phrases: 'Hello', 'Yes', 'No', 'I love you', 'Thank you'.

Once the dataset is labeled and organized correctly, run the code cells in:

```
Tutorial.ipynb
```
This should clone the [Tensorflow Object Detection API](https://tensorflow-object-detection-api-tutorial.readthedocs.io/en/latest/install.html), which will be used to train our model

Copy the code output after ***Step 6*** into the project directory, and that should train the model.

Follow the rest of the steps, and the live camera will pop up to detect our 5 ASL phrases!
