# Face Attendance

Kincannon Wilson Final Project for CS 771

---

### Description

This repo shows the final version of the project 
"Distributed Web-Based Facial Recognition for Student 
Attendance." This project is based on the project 
completed for the annual UW-Madison hackathon 
CheeseHacks, which my team won. My team contributed 
a great deal of work to the frontend functionality, so please check 
out the original repo [here](https://github.com/CannonWilson/CheeseHacks).

My paper's abstract does a fair job of summarizing the
project:

This project involves the creation of a web-based application 
capable of recognizing the faces of students as they walk in 
front of a camera in order to record their attendance. Images 
from a video stream on an instructor’s device are sent over 
HTTP to a server that 1. performs face detection using an MTCNN, 
2. detects spoofs with a liveness detection network based on ResNet-18, 
and 3. if a live face has been detected, generates an embedding of 
the image using Inception ResNet V1. The embedding is compared to 
known embeddings using cosine similarity to identify the student 
in the photo. 

For more info, please read the rest of the paper or 
look at the powerpoint, both of which are included 
in this repo.

---

### Installation

In order to run the project, please clone the repo and 
install all the dependencies. You can do this by 
navigating into the frontend folder and running 

  `npm install`
  
From there, navigate into the backend folder and 
install the required python dependencies (there
are many). Finally, run 

  `python server.py`
  
to run the project. Then navigate to localhost to
explore the project.

---

### Notes

The project as it stands now is very disorganized 
for my standards. I hope to come back to this
project in the future to improve the documentation 
and organization

Unfortunately, this version does not include the
code to use MongoDB for recording attendance, 
creating new classes, etc. After writing a few 
hundred lines of code to accomplish these 
tasks, I accidentally deleted the wrong folder
and lost this work. Lesson learned.

