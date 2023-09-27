# Cartoonify Image

**Cartoonify Image** is a Python program that allows you to apply a cartoon effect to your images. It uses various image processing techniques to achieve this effect. This README provides instructions on how to set up and use the program.

## Installation

Before you can use this program, make sure you have the required Python packages installed. You can install them using pip:

```bash
pip install easygui
pip install imageio
If the above commands return an error, you can use the following commands to ensure pip is installed and then install the packages:

-->py -3.11 -m ensurepip --default-pip
-->py -3.11 -m pip install easygui
-->py -3.11 -m pip install imageio

#Usage
-Clone or download this repository to your local machine.

-Ensure you have the required dependencies installed as mentioned in the Installation section.

-Run the cartoonify_image.py script. This will launch a graphical user interface (GUI) for you to interact with.

-Click the "Select an Image" button to choose an image from your computer.

-The program will process the selected image and display a series of image transformations, ultimately resulting in a cartoonified version of the image.

-You can save the cartoonified image by clicking the "Save cartoon image" button.

-The cartoonified image will be saved in the same directory as the original image with the filename "cartoonified_Image."

#Example

![WhatsApp Image 2023-09-27 at 16 49 20](https://github.com/Spraveen8-chary/cartoonify-image/assets/108536707/0aee1c7b-0ac3-4d87-b812-9cfa09abd5a5)

-Here's an example of how to cartoonify an image using the program:

-Run the cartoonify_image.py script.

-Click "Select an Image" and choose an image from your computer.

-The program will process the image and display the cartoonified version.

-Click "Save cartoon image" to save the cartoonified image.

#Dependencies
-OpenCV (cv2): For image processing.
-EasyGUI: For opening the file dialog.
-NumPy: To store image data.
-ImageIO: To read images stored at a particular path.
-Matplotlib: For displaying images.
-Tkinter: For creating the graphical user interface.
-Pillow (PIL): For image handling.
