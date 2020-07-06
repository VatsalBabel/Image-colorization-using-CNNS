# Image-colorization-using-CNNS
Training NN to fill colors in a grayscale image

For training our model, we have used the following methodology -
 1. Converted the colored input images to LAB color space
 2. Using openCV we have extracted the individual color matrix, that is, the L, A, B component from the images
 3. Passing the L component (grayscale image) as input and training to get approximate A and B component.

NN architecture used in this project -
![NN architecture](/images/model.png)
