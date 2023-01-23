# Project_0: Getting Started
The purpose of this exercise is to get you familiar with tools and basic knowledge for working with video files. After completing this exercise, you should create basic software for processing videos and visual debugging your code.

NOTE: Submit your program source code on GitHub Classroom. However, you DO NOT need to submit a report for this project on Gradescope.

## Part I - Setting up the environment.
- You will use Python, or C/C++ for this exercise.
- Download and install OpenCV with ffmpeg capabilities on your computer. Recommend version 3.0+. There are many online resources for installing the required packages depending on your OS.

## Part II - Processing video files and visual debugging.
- Write a program that reads video in one of 3 formats, and displays it at one of 3 speeds: as fast as possible, 30 fps, and one frame at a time. For your program to be a  exible start to future assignments, it should not have hard-wired input but instead take inputs from the command line. Required formats:
  - YUV format, one byte per pixel.
  -  A compressed video file like *.mp4.
  - A series of JPEG images with names ''file\%4d.jpg", where the ''\%4d" means a 4-digit integer (or bigger) to denote frame number, like tennis0010.jpg is the 11-th image (because time starts at 0).

- Write a program that reads video in one of 3 formats, and saves it in the other two formats. For your program to be a flexible start to future assignments, it should not have hard-wired input but instead take inputs from the command line.
Required formats:
  - YUV format, one byte per pixel.
  -  A compressed video file like *.mp4.
  - A series of JPEG images with names ''file\%4d.jpg", where the ''\%4d" means a 4-digit integer (or bigger) to denote frame number, like tennis0010.jpg is the 11-th image (because time starts at 0).

- Augment your program to compute and display the frame difference image, which is the difference between two adjacent frames.

- Augment your program to respond to keyboard and mouse commands. You should include the following set of operations:
  - Stop/Start (when the space bar is pressed).
  - Step One Frame (when the "." period key is pressed).
  - Print (x,y) (when the left mouse is pressed).
  - Print (R,G,B) when the right mouse is pressed).
You may use online tutorials and sample codes to get you started, but be sure to give credit where credit is due.

- Sample video files in .yuv, .mp4, .jpg formats can be found on [HERE](https://engineering.purdue.edu/~zhu0/ece634/sample_video.zip).
