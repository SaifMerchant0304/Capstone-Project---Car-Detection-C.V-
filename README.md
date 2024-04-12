## Capstone-Project---Car-Detection 

**Project Overview: DL-Based Car Identification Model**

- **Domain:** Automotive Surveillance
- **Context:** Utilizing computer vision for automated supervision and triggering appropriate actions based on detected events from images.
- **Dataset Description:** 
  - Contains 16,185 images of 196 classes of cars.
  - Split into 8,144 training images and 8,041 testing images.
  - Each class represents Make, Model, Year (e.g., 2012 Tesla Model S).
  - Data includes training and testing images along with annotations consisting of bounding box regions.
- **Reference:** 
  - "3D Object Representations for Fine-Grained Categorisation" by Krause et al. at ICCV 2013.
  - Original dataset link: [Stanford Car Dataset](https://www.kaggle.com/jutrera/stanford-car-dataset-by-classes-folder)

**Project Objectives: Designing a DL-Based Car Identification Model**

- **Project Tasks:**

**Milestone 1:**
- **Input:** Context and Dataset
- **Process:**
  - **Step 1:** Import the data.
  - **Step 2:** Map training and testing images to their classes.
  - **Step 3:** Map training and testing images to their annotations.
  - **Step 4:** Display images with bounding boxes.
  - **Step 5:** Design, train, and test basic CNN models to classify the car.
  - **Step 6:** Interim report.
- **Submission:** Interim report, Jupyter Notebook with all Milestone-1 steps.

**Milestone 2:**
- **Input:** Preprocessed output from Milestone-1
- **Process:**
  - **Step 1:** Fine-tune the trained basic CNN models for car classification.
  - **Step 2:** Design, train, and test RCNN & its hybrids for object detection.
  - **Step 3:** Pickle the model for future prediction.
  - **Step 4:** Final Report.
- **Submission:** Final report, Jupyter Notebook with all Milestone-1 and Milestone-2 steps.

**Milestone 3:**
- **Process:**
  - **Step 1:** Design a clickable UI-based interface for browsing images, inputting images, and outputting class and bounding box/mask. 
