# LetsGrowMore Internship Projects

# Image to Pencil Sketch with Python

We need to read the image in RBG format and then convert it to a grayscale image. This will turn an image into a classic black and white photo. Then the next thing to do is invert the grayscale image also called negative image, this will be our inverted grayscale image. Inversion can be used to enhance details. Then we can finally create the pencil sketch by mixing the grayscale image with the inverted blurry image. This can be done by dividing the grayscale image by the inverted blurry image. Since images are just arrays, we can easily do this programmatically using the divide function from the cv2 library in Python. Reference:Watch Tutorial from here.



## Demo

# INPUT
![Ironman-1](https://user-images.githubusercontent.com/83171076/135080094-9f74bdde-572c-4522-b910-84a169436663.jpg)

# OUTPUT
![Final_Output](https://user-images.githubusercontent.com/83171076/135080041-da014980-60e6-492b-a658-fd4271f8a6c8.png)
  
