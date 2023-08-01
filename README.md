# MedicalAR

## Repository Details:
- Unity version: 2021.3.26f1
- AR Foundation version: 4.2.8
- Render pipeline: 3D

## Project details:
- The software [3D slicer](https://www.slicer.org/) is used to generate 3D models using data from MRI/CT scans.
- Foe generating the Brain and Tumore model, [this](https://drive.google.com/drive/folders/1o8q-yIiTF92CyM0O_cOSr9Y3z1AmkMZ-?usp=drive_link) dataset was used.
- The project uses the 'image detection' feature of AR Foundation to instantiate the model.

## How to set up the Project?
- Download this repository and open it in Unity.
- Download the [UnityPackage](https://drive.google.com/file/d/1dyyffUNvXz2GYMVw4ookfqkEeoKlNZUV/view?usp=sharing) and import it into Unity.

## How to use the Project?
- In the Hereachy window, select AR Session Origin. 
- Drag and drop the "Head" prefab into the "Tracked Image Prefab" field of the AR Tracked Image Manager component   
- Save the scene and build the application.
- The application has a slider which can be used to position the cutting plane.

## Final Result 

[Video](https://drive.google.com/file/d/1XQ12g2MQkH_L42V7uOFmUR7GT4xoLS80/view?usp=share_link)
