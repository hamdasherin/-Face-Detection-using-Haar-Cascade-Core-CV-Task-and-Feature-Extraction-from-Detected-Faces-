 Face Detection and Feature Extraction using Haar Cascade

This task implements a classical computer vision pipeline using OpenCV. Human faces are detected in images using a Haar Cascade classifier. Each detected face is cropped, resized, and converted into a numerical feature representation using flattened pixel values or Histogram of Oriented Gradients (HOG).

The implementation is carried out in Google Colab, allowing easy execution and visualization without local setup. This task demonstrates the fundamentals of face detection and feature extraction using classical computer vision techniques.

 Tools Used
- Python
- OpenCV
- NumPy
- Haar Cascade XML
- Google Colab

 How to Run
- Open the notebook in Google Colab
- Upload the Haar Cascade XML file and input image
- Run all cells to detect faces and extract features

 Output
- Image with bounding boxes around detected faces
- Console output showing number of faces detected
- Feature vectors stored in a NumPy array
