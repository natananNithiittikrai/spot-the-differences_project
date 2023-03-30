# Image Difference Detection
This Python script detects the differences between pairs of images using OpenCV library. It calculates the absolute difference between two grayscale images and applies threshold to the difference image. Then, it identifies contours and draws bounding boxes around the contours to highlight the differences between the images. Finally, it displays the two images side by side with bounding boxes around the differences.

## Usage
- Clone the repository
- Install OpenCV and imutils libraries by running ```pip install opencv-python imutils``` on the command line
- Add your pairs of images to the image_pairs list
- Run the script by running ```python image_diff_detection.py``` on the command line
## Example
Suppose you have two images of toys named toys1.png and toys2.png and you want to compare them. You can add the pair to image_pairs list as follows:

```image_pairs = [('toys1.png', 'toys2.png')]```

## Output
The script displays the images with bounding boxes around the differences. If you want to save the output, you can modify the script to save the figures using ```plt.savefig``` instead of displaying them using ```plt.show```

## Video Demo
[Insert video demo here]

## Requirements
* Python 3.x
* OpenCV
* imutils
* matplotlib
