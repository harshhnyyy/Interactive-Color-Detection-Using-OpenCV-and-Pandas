
# Interactive Color Detection Using OpenCV and Pandas

A Python application that identifies the nearest named colour from any point clicked on an image, using Manhattan distance calculation on RGB values.

## What it does
- Loads any image and lets the user click on a pixel
- Extracts the RGB value at that point
- Calculates the nearest matching colour name from a reference dataset using Manhattan distance
- Displays the colour name and RGB values in real time on the image

## Tech Stack
Python, OpenCV, Pandas, NumPy

## How to run
1. Clone the repository
2. Install dependencies: pip install opencv-python pandas numpy
3. Run: python color_detection.py
4. Click anywhere on the image to identify the colour

## Notes
- Tested on common image formats: JPG, PNG
- Sub-second response time on standard hardware
- Includes exception handling for unsupported formats and missing files
- Known edge case: very dark or near-black pixels may return ambiguous matches due to similar Manhattan distances across dark colour names
