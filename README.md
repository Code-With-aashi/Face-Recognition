# Face-Recognition
Simple library to recognize faces from given images.
## Face Recognition pipeline
### Below the pipeline for face recognition:

* Face Detection: the MTCNN algorithm is used to do face detection
* Face Alignement Align face by eyes line
* Face Encoding Extract encoding from face using FaceNet
*Face Classification Classify face via eculidean distrances between face encodings

### How to install

pip install git+https://github.com/paoloripamonti/face-recognition

### How to train custom model
from face_recognition import FaceRecognition

fr = FaceRecognition()
