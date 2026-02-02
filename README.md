This project demonstrates camera calibration and real-world 2D object measurement using a smartphone camera and OpenCV.
The workflow consists of:

1. Camera calibration using a Charuco board
2. Lens distortion correction
3. Estimating real-world object dimensions using perspective projection equations
4. Experimental validation with a physical object at a known distance

Software: Python 3.10+ (tested on Python 3.13), OpenCV with contrib modules, NumPy

How to Run:
1. Download everything
2. Make sure the images for calibration is in folder calib-images
3. Run with jupyter notebook either on VSCode or notebook itself
4. Make sure opencv-contrib-python is installed otherwise it will not run

Measurement of box- 0.162 m by 0.141 m
