# IMAGE BLURRING USING DIFFERENT SIZED AVERAGING FILTERS
<img width="950" height="709" alt="image" src="https://github.com/user-attachments/assets/9ccd30e9-7f11-4eb5-98bd-9279eba00d9a" />
<img width="754" height="989" alt="image" src="https://github.com/user-attachments/assets/1032607f-834d-465e-9114-a4be34a551ab" />



# AIM

To demonstrate the effect of image blurring using averaging filters of different kernel sizes.

# SOFTWARE USED

* **Google Colab**
* **Python**
* **OpenCV (`cv2`)**

# THEORY

## IMAGE SMOOTHING

Image smoothing, also known as **image blurring**, is a technique used to reduce noise and soften sharp details or edges in an image. It is commonly used as a preprocessing step in image processing and computer vision.

## AVERAGING FILTER

An **averaging filter**, also called a **mean filter**, smooths an image by replacing each pixel with the average value of its neighboring pixels.

* A small window called a **kernel** is moved across the image pixel by pixel.
* At each position, the average intensity of all pixels within the kernel is calculated.
* The center pixel is replaced with this average value.
* This reduces sudden changes in pixel intensity and produces a smoother image.

## EFFECT OF KERNEL SIZE

The **kernel size** determines the amount of blurring applied to the image.

* **3 × 3 kernel** → Mild blur and preserves more details.
* **5 × 5 kernel** → Moderate blur and removes more details.
* **9 × 9 kernel** → Strong blur and significantly reduces fine details.

As the **kernel size increases, the intensity of blurring also increases**. However, excessive blurring can remove important features and fine details from the image.

# CONCLUSION

The experiment demonstrates that averaging filters can effectively smooth an image. A **smaller kernel preserves more details**, while a **larger kernel produces stronger blurring** and removes more image details.
