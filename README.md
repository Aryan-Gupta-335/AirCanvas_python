# AirCanvas_python
This is a Python script using OpenCV for a simple color-based painting application. Here's a brief overview:

Functionality:

1. Tracks the user's hand or a colored object using HSV color space and contour detection.
2. Allows the user to select a color by clicking on the corresponding button at the top of the screen.
3. Draws lines on the screen and a separate canvas window based on the selected color and hand movement.
4. Provides a "Clear" button to reset the canvas.

Key components:

1. Trackbar sliders for adjusting HSV values to detect the desired color.
2. Color buttons at the top of the screen for selecting the drawing color.
3. Canvas window for displaying the drawn artwork.
4. Hand tracking and contour detection using OpenCV.

How it works:

1. The script captures video feed from the default camera.
2. It converts each frame to HSV color space and applies thresholding to detect the selected color.
3. Contour detection is used to find the hand or colored object.
4. The script then draws lines on the screen and canvas based on the hand movement and selected color.
5. The user can switch colors by clicking on the corresponding button or clear the canvas by clicking the "Clear" button.

This script provides a basic color-based painting application using OpenCV. You can enhance it by adding more features, such as saving the artwork or implementing more advanced hand tracking algorithms.
