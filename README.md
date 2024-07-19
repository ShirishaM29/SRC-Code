Real-time Color Picker using Python and OpenCV
This repository contains a Python script that enables real-time color picking from an image using OpenCV and pandas. The script allows users to click on any pixel in an image and displays the color name along with its RGB values. It also adjusts text color based on the brightness of the chosen color for better visibility.

Features:
Color Detection: Click on any pixel in the image to detect the color in real-time.
Color Name Lookup: Matches the RGB values of the selected color to the closest predefined colors stored in a CSV file (colors.csv).

Interactive Display: Shows the selected color and its details on the image itself, including color name, RGB values, and adjusts text color based on brightness.

Customizable: The script can be easily modified to include additional colors or adjust the color detection algorithm.

User-friendly Interface: Utilizes OpenCV's graphical interface for image display and interaction.

Dependencies:

Ensure Python 3.x and the following libraries are installed:

OpenCV (pip install opencv-python)

pandas (pip install pandas)
