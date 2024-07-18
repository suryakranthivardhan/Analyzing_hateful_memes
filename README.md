# Hateful Meme Analysis Project

This project focuses on analyzing hateful memes through various computer vision and natural language processing tasks. The project is divided into four main tasks: object detection, caption impact assessment, classification, and toxicity prediction. The code for each task is implemented in google colab. 

## Project Structure

1. **Object Detection** (`object_detection.ipynb`): Detect objects in the images and print the frequency of each detected object.To view the task [click here](https://github.com/suryakranthivardhan/Analyzing_hateful_memes/blob/main/object_detection.ipynb)
2. **Caption Impact Assessment** (`Caption_impact.ipynb`): Assess the effect of overlaid captions on the accuracy and effectiveness of object detection.To view the task [click here](https://github.com/suryakranthivardhan/Analyzing_hateful_memes/blob/main/Caption_impact.ipynb)
3. **Classification** (`classification.ipynb`): Classify memes into five sentiment labels: positive, very positive, neutral, negative, and very negative.
4. **Bonus Task - Toxicity Prediction** (`bonus_task.ipynb`): Predict whether a meme is toxic or non-toxic by performing NLTK sentiment analysis on the labeled memes dataset.

## Dataset

The dataset for this project can be downloaded from the following link:
[Dataset Download Link](https://drive.google.com/drive/folders/1BHiATwEb2gjKY0ZQD0rVhLzsrTygl3op?usp=drive_link)

## Getting Started

To get started with this project in google colab, follow the steps below:

1. **Mount Google Drive**: First, mount your Google Drive to Google Colab to access the dataset.
   ```python
   from google.colab import drive
   drive.mount('/content/drive')
2. **Unzip the dataset**:We need to unzip the dataset to read in colab.
      ```python
   !unzip /content/drive/MyDrive/dataset.zip #enter the path of dataset
