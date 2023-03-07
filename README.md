---
driveId: 1XQ12g2MQkH_L42V7uOFmUR7GT4xoLS80/preview
---

# MedicalAR

## Repository Details:
- Unity version: 2021.3.12f1
- AR Foundation version: 4.2.6
- Render pipeline: 3D

## Project details:
- The software [3D slicer](https://www.slicer.org/) is used to generate 3D models using data from MRI/CT scans.
- The project uses the 'image detection' feature of AR Foundation to instantiate the model.

## How to set up the Project?
- Download this repository and open it in Unity.
- Download the [prefabs](https://drive.google.com/file/d/1dyyffUNvXz2GYMVw4ookfqkEeoKlNZUV/view?usp=sharing) and import it into Unity.

## How to use the Project?
- Import the 3D model into the Project window.
- In the Hereachy window, select AR Session Origin. 
- Drag and drop the prefab into the "Tracked Image Prefab" field of the AR Tracked Image Manager component   
- Save the scene and build the application.
- The application has a slider which can be used to position the cutting plane.

## Final Result 

{% include googleDrivePlayer.html id=page.driveId %}
