# letsgrowmore_internship task 1
task- image to pencil sketch with python: 
we need to read the image in rgb fromat and then convert it to a grayscale image.
this will turn an image into a classic black and white photo.
then the next hing to do is to invert the grayscale image also called negative image, this will be our inverted grayscale image.
inversion can be used to enhanced the details. then we can finally create the pencil sketch by mixing the grayscale image wuth the inverted blurry image. this can be done by dividing the grayscale image by the inverted blurry image.
since images are just arrays, we can easily do this programatically using the divide function from the cv2 library in python.
