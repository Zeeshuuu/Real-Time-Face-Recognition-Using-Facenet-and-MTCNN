# Real-Time-Face-Recognition-Using-Facenet-and-MTCNN
This project is a real-time face recognition system built using PyTorch, FaceNet, and MTCNN. It allows you to upload images of known people, generate their embeddings, and then recognize faces live using a webcam or video stream.

 ## What This Project Does

- Detects faces using MTCNN

- Generates high-quality 512-dim embeddings using FaceNet (InceptionResnetV1)

- Saves all known-face embeddings into a single .npz file

- Performs real-time face recognition

- Matches live faces with stored embeddings using cosine similarity

- Displays name + confidence score on video

## Key Features

- Face enrollment system
- Supports multiple images per person
- Robust preprocessing for inconsistent image formats
- Works in Google Colab, Jupyter, or local Python
- Accurate & fast recognition in real-time
- Clean modular code structure
