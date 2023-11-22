# First-principles-of-Computer-Vision

## main.py

Image Reading:

The cv2.imread function is used to read an image from disk. The image, in this case, is named "wood_img.jpg" and is loaded in color.
GUI Window Creation:

A GUI window is created using the cv2.imshow method. This window displays the image loaded in the previous step.
Wait for User Input:

The cv2.waitKey(0) method is used to hold the window on the screen until the user inputs something. In this case, it waits indefinitely (0 milliseconds) until the user closes the window.
Window Destruction:

The cv2.destroyAllWindows() method is called to remove the created GUI window from the screen and free up memory.

## main2.py

Library Imports:

The script imports the necessary libraries, including OpenCV (cv2), NumPy (numpy), and Matplotlib (matplotlib.pyplot).
Image Loading:

The image "wood_img.jpg" is loaded using the cv2.imread method, creating an image object.
Color Conversion:

The script converts the image from the default BGR (Blue, Green, Red) color format to the more commonly used RGB (Red, Green, Blue) format using cv2.cvtColor.
Image Display:

The RGB-formatted image is displayed using Matplotlib's plt.imshow() method. This function is specifically designed for displaying images and visualizing data.
Wait for User Input:

The plt.waitforbuttonpress() method is utilized to pause the execution of the script, waiting for a button press from the user before proceeding.
Close All Windows:

Finally, all open windows are closed using plt.close('all').

## main3.py

Library Import:

The program begins by importing the OpenCV library (cv2).
Image Path:

The path to the image file, named "wood_img.jpg," is specified using the variable path.
Image Reading:

The cv2.imread() method is employed to read the image from the specified path. Additionally, the cv2.IMREAD_GRAYSCALE flag is used, indicating that the image should be read in grayscale mode.
Image Display:

The program utilizes cv2.imshow() to display the read image. The window title is set to 'image,' and the image is displayed.
User Interaction:

The cv2.waitKey(0) method is used to wait for a key press from the user. It waits indefinitely (0 milliseconds) until a key is pressed.
Window Closure:

Finally, the cv2.destroyAllWindows() method is called to close the image window and free up system resources.
This program provides a basic example of how to read an image in grayscale using OpenCV
