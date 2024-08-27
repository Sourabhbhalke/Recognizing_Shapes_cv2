# Recognizing_Shapes_cv2
Automated detection and recognition of shapes like lines and circles in images using OpenCV, with optimized parameters for diverse image sets.

## Project Structure

### Main Branch
The main branch contains the optimized code for the **subway image**. This serves as the base implementation, and the code includes:
- Grayscale conversion
- Canny edge detection
- Hough Line Transform
- Hough Circle Transform
- Gaussian Blur
- Optimized parameter settings for shape detection in the subway image

### Branches for Other Images
Each of the following images has its own branch, where the code is being optimized for the respective image:

- **breakfast** (`breakfast_branch`)
- **dinner** (`dinner_branch`)
- **building** (`building_branch`)

These branches are forks of the main branch, and contain specific adjustments to the following components:
- Grayscale settings
- Edge detection thresholds
- Hough Transform parameters (for lines and circles)
- Gaussian Blur settings

### Workflow
1. **Main Branch**: Start with the base code optimized for the subway image.
2. **Image Branches**: For each image branch:
   - Checkout the branch.
   - Adjust parameters specific to the image.
   - Test and refine the code to optimize shape detection.
3. **Final Integration**: Optionally, merge back the optimized code from the branches into the main branch or a new branch if a generalized solution is developed.

## How to Use

1. **Checkout the branch for the image you want to work with:**
    
    git checkout breakfast_branch

2. **Run the script** to detect shapes with optimized parameters for that image.

3. **To switch to another image:**
   
    git checkout <image_branch>

## Contribution

Feel free to fork the project and submit pull requests with improvements, especially in optimizing detection parameters for new images.

