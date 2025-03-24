# Computer Vision - Edge Detection & Segmentation with Deep Learning

## Overview
This project explores various edge detection and image segmentation techniques, comparing manual kernel approaches with modern deep learning methods. It includes implementations of classical edge detection operators, segmentation methods, and advanced deep learning models for face detection.

## Project Goals
- Implement and compare manual kernel-based edge detection methods.
- Apply various image segmentation techniques.
- Utilize advanced deep learning models for accurate face detection and segmentation.

## Techniques Included

### Edge Detection (Manual Kernels)
- **Sobel Operator**
- **Prewitt Operator**
- **Scharr Operator**
- **Laplacian Operator**
- **Canny Edge Detection (using Scharr Kernel)**

### Image Segmentation
- **HSV Color Space with Thresholding**
- **SVM & HOG (Histogram of Oriented Gradients)**
- **K-Means Clustering**

### Deep Learning Methods
- **Face Detection with MTCNN**
- **Face Detection using OpenCV's CVLIB**

## How to Run
To execute this project locally:

1. Clone the repository:
   ```bash
   git clone https://github.com/azizzoaib786/computer-vision-edge-detection.git
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the notebook:
   - Open `computer-vision-edge-detection.ipynb` in Jupyter Notebook or JupyterLab.
   - Replace the placeholder path in the notebook with your folder path:
     ```python
     negatives_patches = r'<change_with_your_path>'
     ```
   - Execute all cells (`Run All`).

## Requirements
- Python (3.7 or higher recommended)
- OpenCV
- numpy
- matplotlib
- scikit-learn
- scikit-image
- MTCNN
- CVLIB
- TensorFlow or PyTorch
- Jupyter Notebook/JupyterLab

## Contributions
Contributions are welcome! Feel free to fork, enhance, and submit a pull request.

## Contact
- Email: [azizzoaib786@gmail.com](mailto:azizzoaib786@gmail.com)

## License
This project is licensed under the MIT License.