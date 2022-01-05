# Self-Driving-Lane-Detector-Python-Project
# Package/Script Name

## What does the Project do? 


Purpose of the script is to detect Lane from the Image and make it more and more accurate.

## Short description of package

- This project help us to detect the Road Lane.
- Libraries Imported :
    - CV2
    - Matplotlib
    - Numpy


## Workflow of the Project

- Here Firstly the image is read from Images folder using OpenCV library.
- Setting the region of interest between which the road lane is their. (mentioned data is according to the given input, If u want to try your own input image try to change the value and after testing fix the region).
- Converting the image to grey scale image.
- Using canny's edge detection function, detecting the edge.
- Using HoughLines function detecting the points from the canny's detected image.
- At last drawing the line and showing the output as Detected_Lane.jpg file. 



## Setup instructions

First install the above mentioned library, If you want to detect lane on your given input just changge the path in cv2.imread function and set your path and run the file.

## Compilation Steps:
   - Install CV2, Matplotlib and Numpy library in your system. (syntax : pip install library_name)
   - Clone the project on local system.
   - Execute/Run .py file and get the output.

## Output
- Input Image
    - ![road](https://i.ibb.co/M63K9q7/road.jpg)

- Output Image
    - ![Detected Lane](https://i.ibb.co/WDMbWY6/Detected-Lane.png)
 


## Made by 

<h2>✔Project Maintainer/Owner</h2>

<table>
  <tr>
<td align="center"><a href="https://github.com/txtgrey"><img src="https://i.ibb.co/LxB1mpH/278685-D2-71-BE-4982-B37-E-4-F008-ADE219-B.jpg" width="180px;" alt=""/><br /><sub><b>Tejas Agrawal</b></sub></a></td>  

  </tr>
</table>
<h2>✔Contributors/Admin</h2>

<table>
 <tr>
<td align="center"><img src="https://i.ibb.co/N2J4dv9/Ayush-Gaur.jpg" width="180px;" alt=""/><br /><sub><b>Ayush Gaur</b></sub></a></td>  
<td align="center"><img src="https://i.ibb.co/pz429K2/IMG-20210318-192949-384.jpg" width="150px;" alt=""/><br /><sub><b>Prateek Mahant</b></sub></a></td>  
<td align="center"><img src="https://i.ibb.co/4gcYC3t/Whats-App-Image-2022-01-05-at-11-31-23-PM.jpg" width="150px;" alt=""/><br /><sub><b>Parikshit Singh</b></sub></a></td>  

</tr>
</table>

##
[![forthebadge](https://forthebadge.com/images/badges/built-with-love.svg)](https://forthebadge.com) [![forthebadge](https://forthebadge.com/images/badges/built-by-developers.svg)](https://forthebadge.com) [![forthebadge](https://forthebadge.com/images/badges/made-with-python.svg)](https://forthebadge.com)
