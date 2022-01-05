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
<td align="center"><a href="https://github.com/Knighthawk-Leo"><img src="https://github.com/Knighthawk-Leo/ML-Based-Dog-Breed-Identifier/blob/main/Images/IMG20211212132226.jpg" width="180px;" alt=""/><br /><sub><b>Tejas Agrawal</b></sub></a></td>  

  </tr>
</table>
<h2>✔Contributors/Admin</h2>

<table>
 <tr>
<td align="center"><img src="https://avatars.githubusercontent.com/u/72202404?v=4" width="180px;" alt=""/><br /><sub><b>Ayush Gaur</b></sub></a></td>  
<td align="center"><img src="https://github.com/Knighthawk-Leo/ML-Based-Dog-Breed-Identifier/blob/main/Images/IMG20211102195542.jpg" width="150px;" alt=""/><br /><sub><b>Prateek Mahant</b></sub></a></td>  
<td align="center"><img src="https://github.com/Knighthawk-Leo/ML-Based-Dog-Breed-Identifier/blob/main/Images/%E2%80%94Pngtree%E2%80%94cartoon%20male%20teacher%20holding%20a_5552300.png" width="150px;" alt=""/><br /><sub><b>Parikshit Singh</b></sub></a></td>  

</tr>
</table>

