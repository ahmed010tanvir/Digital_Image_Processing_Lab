# 🌅 Digital Image Processing Project

![GitHub](https://img.shields.io/badge/Python-3.7%2B-blue) ![OpenCV](https://img.shields.io/badge/OpenCV-4.x-green)

## 📖 Project Overview

- Lab Assignment 1: Extract a 100×100 pixel center region from an image and convert it to HSV, displaying each component in grayscale.
- Lab Assignment 2: Resize an image to 256x256, rotate 180° clockwise, apply a vertical flip, and display all transformations in a subplot.
- Lab Assignment 3: Create two 400x400 images (one with a green rectangle, one with a magenta circle) and apply bitwise operations, multiplication, alpha blending, and subtraction using OpenCV.


The implementation is done using Python and popular libraries like OpenCV, Matplotlib, and NumPy.

---

## 🛠️ Prerequisites

Before running the code, ensure you have the following installed:
- Python 3.7 or higher
- Required Python libraries:
  - `opencv-python`
  - `matplotlib`
  - `numpy`

## 🚀 Installation
git clone https://github.com/ahmed010tanvir/Digital_Image_Processing_Lab.git

## 🎯 Usage 
**For Lab Assignment-1** 
---
Run the script in a Python environment (e.g., Jupyter Notebook, Google Colab, or a local Python IDE).

Below are the steps: 

 Step 1: Load the Image 

    The script fetches an image from a URL and processes it. You can modify the image_url variable to use a different image.

 Step 2: Extract the Region
  
    The script extracts a 100×100 pixel region from the center of the image.

 Step 3: Convert to HSV
  
    The script converts the image to the HSV color space and displays the Hue, Saturation, and Value components in grayscale.
  
**For Lab Assignment-2** 
---
 Step 1: Resize

    Resize the image to 256×256 pixels to ensure uniform dimensions.

 Step 2: Rotate

    Rotate the image by 180 degrees clockwise to flip it upside down.

 Step 3: Flip

    Apply a vertical flip to invert the image along the vertical axis.

 Step 4: Display

    Display all transformations in a single subplot for easy visualization

**For Lab Assignment-3** 
===
Create two 400x400 images with black background :

    The first image should contain a green rectangle at the center.
    The second image should contain a magenta circle at the center.

Operations using OpenCV and display the results:


    Bitwise AND (cv2.bitwise_and): Show the overlapping region of the two images.

    Bitwise OR (cv2.bitwise_or): Combine both shapes while retaining their colors.

    Bitwise XOR (cv2.bitwise_xor): Retains only the non-overlapping parts of both images.

    Bitwise NOT (cv2.bitwise_not): Inverts the colors of each shape separately.

    Element-wise Multiplication (cv2.multiply): Observe the effect on overlapping areas.

    Alpha Blending (cv2.addWeighted): Blend both images with transparency effects-
                                    (α×Img1)+(β×Img2)+γ = result,for img-1,2 we can control the dominance of each img in blending(0-1).

    Image Subtraction (cv2.subtract): Highlights the differences between the two images.
  
