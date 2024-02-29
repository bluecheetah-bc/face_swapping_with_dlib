# face_swapping_with_dlib
Facial Landmark Detection with Dlib and Face Swapping 

<img alt="BC" src="https://i.stack.imgur.com/07iZz.jpg" width='500'  align='center'/>

<!-- ABOUT THE PROJECT -->
## About The Project
<b>Face swapping is a computer vision task. It is used when we want to change two images' faces. In this project, we used dlib detector for the purpose of detecting facial landmarks, and then we swapped their faces using these landmarks. </b>

The steps of the project are as follows:

- <b>1)Installation of Dlib and Dependencies:</b>
  
  +Firstly, we installed the Dlib library and related dependencies such as OpenCV. This step was accomplished using specific pip commands in the terminal or command prompt.

- <b>2)Face Detection and Facial Landmark Detection:</b>

  +We loaded the image we were working with before starting the operations.

  +Using Dlib, we detected faces in the image using a model that we employed for this purpose.

  +We determined landmark points for each detected face, representing important parts of the face like the corners of the eyes, tip of the nose, corners of the mouth, etc.

- <b>3)Face Swapping:</b>

  +We compared landmark points between two faces to identify similarities and differences.
  
  +We applied a transformation algorithm (such as affine transformation) to make one face fit onto the other.
  
  +We placed the transformed face onto the corresponding region of the original image.

### Built With

* ![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
* ![OpenCV](https://img.shields.io/badge/opencv-%23white.svg?style=for-the-badge&logo=opencv&logoColor=white)
* ![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
* ![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)
