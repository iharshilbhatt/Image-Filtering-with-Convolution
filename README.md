# Image-Filtering-with-Convolution
This repository contains a Python script that demonstrates various image filtering techniques using convolution. The script is designed to be run in a Google Colab environment and uses the cv2_imshow function for displaying images.

Features
The script applies the following filters to an input image:

Identity Filter: Leaves the image unchanged.
Horizontal Edge Detection: Detects horizontal edges in the image.
Vertical Edge Detection: Detects vertical edges in the image.
Sharpening Filter: Enhances the edges and details in the image.
Emboss Filter: Creates an embossing effect.
Small Blur Filter: Applies a small blur using an average filter.
Large Blur Filter: Applies a large blur using an average filter.
Box Blur Filter: Applies a box blur (average blur).
Gaussian Blur Filter: Applies a Gaussian blur.
Edge Enhancement Filter: Enhances the edges in the image.
Prerequisites
Python 3.x
Required Python packages: numpy, pandas, matplotlib, Pillow, scipy, opencv-python
Install the required packages using pip:
```bash
pip install numpy pandas matplotlib Pillow scipy opencv-python
```
This script defines and applies a variety of convolution kernels to an image, including identity, edge detection, sharpening, blurring, and custom filters. Each filter is applied using a helper function apply_filter which simplifies the convolution process and image display.

More Filters Description
Laplacian Filter: Detects edges in an image by approximating the second derivative of the image.
Sobel Filters (X and Y): Detects edges in the X and Y directions using Sobel operators.
Prewitt Filters (X and Y): Another method for detecting edges, similar to Sobel but with different weightings.
Unsharp Mask: Enhances edges by subtracting a blurred version of the image from the original image.
Custom Kernel: Example of a custom kernel for edge detection with different weightings.

Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

