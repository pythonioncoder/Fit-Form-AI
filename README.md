# Fit Form AI
Fit Form AI is an AI-powered posture correction feedback app for exercise, yoga, and other posture applications. Utilizing Google AI Edge solutions and the OpenCV library, Fit Form AI takes in a live camera feed, detects key body parts, and outputs posture-correcting feedback.

[![Download](https://img.shields.io/badge/download-latest-brightgreen?style=flat-square)]([https://github.com/jordanbaird/Ice/releases/latest](https://colab.research.google.com/github/pythonioncoder/Fit-Form-AI/blob/main/Prototype_2_Electric_Boogalooo.ipynb))
![Platform](https://img.shields.io/badge/Platform-Browser-blue)

## Overview
You might've seen videos online of bodybuilders tearing a muscle in the middle of a workout. These injuries are painful to watch but have a surprisingly simple solution: better form. When bodybuilders have a low range of motion, their muscle only gets stronger in that range, leading to tears when it's pushed outside of that limited range. Fit Form AI aims to combat this by detecting key body parts and providing feedback to the user so they never develop chronically bad form. Through this process, it's also able to fix any posture problem, whether it be exercise, yoga, or simply good sitting posture. The Jupyter Notebook takes a live video feed from the user's camera, giving each frame to a pose landmark detection model from Google AI Edge's MediaPipe Solutions. The model returns the XYZ coordinates of major joints, which are cross-checked with the relevant CSV file for the exercise chosen. If any joint angle is outside the allowable range specified in the CSV file, the program will print out the appropriate feedback so the user can adjust their form. Because of the flexibility of the CSV files, literally any use case involving joint angles is allowed.



![image](https://github.com/pythonioncoder/Fit-Form-AI/assets/70725762/54e844c3-cea1-4497-b51e-6406b651f8a8)
*Output from MediaPipe*

>[!NOTE]
>Fit Form AI is currently in active development. iOS and Android apps are not implemented yet. Check below for the latest updates.

## Installation
Create a copy of the Fit Form AI Resources folder in your Google Drive. Link can be found in the repo or here: https://drive.google.com/drive/folders/1RFTh9ed50zVZaIyutPCo6-VTEQanqE4_?usp=drive_link.

## Usage
Simply open the .ipynb in Google Colab and run!
