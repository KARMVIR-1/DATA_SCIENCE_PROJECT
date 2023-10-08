# DATA_SCIENCE_PROJECT - COLOR DETECTION SYSTEM
This Python script allows you to identify colors in an image by double-clicking on any part of the image. It will display the color name along with the RGB values of the selected pixel.
#overview :
This script provides a simple graphical interface for color identification in an image. It utilizes the OpenCV library to read and display images and pandas to load color data from a CSV file.


# Prerequisite
# Before running the script, make sure you have the following prerequisites:

Python 3.x installed
OpenCV (cv2) library installed (pip install opencv-python)
Pandas library installed (pip install pandas)
An image file you want to analyze
A CSV file (colors.csv) containing color information, with columns for color name, hex code, and RGB values.


# Usage
Clone this repository or download the color_detection.py script to your local machine.
Ensure you have the necessary prerequisites installed (Python, OpenCV, and Pandas).
Prepare your image and make sure it's in the same directory as the script.
Run the script by executing the following command in your terminal:
# command : python color_identification.py -i your_image.jpg
Replace your_image.jpg with the actual path to your image file.
When the script opens the image, double-click on any part of the image to identify the color of that pixel. The color name, along with RGB values, will be displayed on the image.
Press the 'esc' key to exit the application


# How it works 
The script uses OpenCV to read and display the image, allowing the user to interact with it.
When the user double-clicks on a pixel in the image, the script retrieves the RGB values of that pixel.
It then compares these RGB values with the RGB values of colors in the colors.csv file to find the closest matching color.
The color name and RGB values of the selected pixel are displayed on the image.
If the selected color is very light, the text will be displayed in black for better visibility.




