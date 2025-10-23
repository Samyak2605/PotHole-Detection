# Road Damage Detection Applications

This project is road damage detection applications that designed to enhance road safety and infrastructure maintenance by swiftly identifying and categorizing various forms of road damage, such as potholes and cracks.

## Performing Detection Using Image
![Detection using image](resource/RDD_Image_Example.gif)

## Performing Detection Using Video
![Detection using video](resource/RDD_Video_Example.gif)

The project is powered by YOLOv8 deep learning model that trained on Crowdsensing-based Road Damage Detection Challenge 2022 dataset.

There is four types of damage that this model can detects such as:
- Longitudinal Crack
- Transverse Crack
- Alligator Crack
- Potholes

## Running on Local Server

## Evaluation Result

This is the training result of the YOLOv8s model that trained on the filtered Japan and India dataset with RTX2060 GPU. You can perform the evaluation on your dataset with **2_EvaluationTesting.ipynb** notebook, just convert your dataset into ultralytics format.

<p align="center">
    <img src='resource/PR_curve.png' width='80%'>
    <img src='resource/confusion_matrix.png' width='80%'>
    <img src='resource/val_batch2_pred.jpg' width='100%'>
</p>

