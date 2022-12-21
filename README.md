# Face Attendance

Kincannon Wilson Final Project for CS 771

---

This repo shows the final version of the project 
"Distributed Web-Based Facial Recognition for Student 
Attendance." 

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

Unfortunately, this version does not include the
code to use MongoDB for recording attendance, 
creating new classes, etc. After writing a few 
hundred lines of code to accomplish these 
tasks, I accidentally deleted the wrong folder
and lost this work. Lesson learned.

