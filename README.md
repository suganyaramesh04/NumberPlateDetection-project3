# Number Plate Detection Using Python & OpenCV

This project presents a comprehensive implementation of a number plate detection system using Python and OpenCV, aimed at identifying and extracting vehicle license plates from static images. It utilizes classical computer vision techniques to process input images and accurately detect the regions containing number plates. The workflow includes steps such as grayscale conversion, noise reduction using bilateral filtering, edge detection with the Canny algorithm, and contour detection to identify potential plate candidates. By filtering and approximating shapes based on size, aspect ratio, and rectangular structure, the system effectively isolates the number plate from the rest of the image.

The project is implemented in a Jupyter Notebook and is designed for easy understanding and experimentation. It provides visual outputs at each stage of processing, allowing users to observe how the system progresses from a raw image to a detected license plate. This method does not require any deep learning or large datasets, making it lightweight and suitable for devices with limited computational resources. Furthermore, the system can be extended for real-time use with video feeds, and integrated with an OCR (Optical Character Recognition) engine to read and recognize license numbers.

The number plate detection approach showcased in this project is highly relevant for applications in intelligent transportation systems, including traffic monitoring, toll collection, vehicle tracking, and access control. This project is particularly useful for students, researchers, and developers looking to understand or prototype simple ANPR (Automatic Number Plate Recognition) systems using traditional image processing techniques.

---

## 📦 Requirements

- Python 3.x
- OpenCV (`opencv-python`)
- NumPy
- Matplotlib (optional, for image display)
