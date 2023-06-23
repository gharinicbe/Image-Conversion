
Image Conversion using OpenCV and EasyGUI
This project demonstrates how to use OpenCV and EasyGUI to convert an image into five different versions, each with a different modification or effect applied.

Dependencies
Python 3.x
OpenCV (cv2) library
EasyGUI library
Installation

Clone the repository:

git clone https://github.com/your-username/image-conversion.git
Install the required dependencies:

pip install opencv-python
pip install easygui
Usage
Place the image you want to convert in the project directory. ( Bird image can be used too, place it in the project dir)

Run the main script:

Copy code
6diffimgconvertcv.ipynb
A GUI window will appear asking for an image from your local folder.

After conversion, the program will ask to save the cartoon image. The converted images will be saved in the project directory.

Supported Conversions
Grayscale Conversion: Converts the image to grayscale.

Edge Detection: Applies edge detection algorithm to highlight the edges in the image.

Color Image: Displays the original color image without any modifications.

Cartoon Image: Applies a combination of filters to create a cartoon-like effect.

Smooth Gray: Smoothens the grayscale image using adaptive thresholding.


Acknowledgments
This project was inspired by the need to showcase different image conversions using OpenCV and EasyGUI.
