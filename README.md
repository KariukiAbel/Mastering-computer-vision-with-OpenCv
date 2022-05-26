# Mastering-computer-vision-with-OpenCv
A repo to get the hands on skill in working with opencv for machine learning and computer vision

<<<<<<< HEAD
### imread()
This method from cv2 reads an image. Normally it takes in one parameter which is the path of the image to be read inside quotation marks.

### imshow()
This method from cv2 displays the image

## GrayScalling
This is the ability to turn a coloured image into a grayscale image. There are two ways of doing this:

### 1. use cvtColor to grayscale an image
cv2.cvtColor(image, cv2.COLOR_BGR2GRAY)

### 2. use imread() to grayscale an image
cv2.imread('path_to_the_image', 0)
Here the zero converts the image to grayscale

## color spaces in HSV ie Hue Saturation and value
cv2.cvtColor(read_image, cv2.COLOR_BGR2HSV)

### Splitiintg images to different blue, green and red colour spaces
B, G, R = cv2.split(image)
=======
**GreyScalling notebook**
Has been used to convert a coloured image into grayscal image
cv2.imread('pathe to the image',0) Here the image is read and converted to grayscale directly by the zero value
>>>>>>> d28d00b720e91b847dff5816c78d7878d481c686
