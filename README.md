# Wood Knot Detection Project

## Introduction

In the construction and decoration industry, wood is a valuable material prized for its aesthetic and structural qualities. However, the presence of knots, remnants of branches in the living tree, can pose challenges. These knots can either add character and beauty to the wood or detract from its strength and final appearance.

This project aims to address this issue by developing a Python program dedicated to the precise identification of knots in wood samples. The fundamental goal is to create an automated method that detects and accurately locates knots while determining their relative size in the wood.

## Project Structure

The project is divided into several distinct sections:

1. **Initial Knot Detection Method**:
    - Implementation of a basic method for knot detection.
    - Analysis of the results obtained on the provided dataset.
    - Identification of the limitations of this method.

2. **Method Improvements**:
    - Proposals for specific improvements, including making the detection more objective by automating the threshold and the minimum area of knots based on the characteristics of each image.
    - A thorough discussion of the results obtained.
    - Application of histogram transformation to highlight dark areas in the image, corresponding to knots, to improve detection accuracy.

## Important Points

- **Data Path**: Specify the location of your data in the `Path` variable.
  ```python
  Path = "Data"
  ```
- **Librairies Used**:
  * `skimage.io`
  * `matplotlib.pyplot`
  * `skimage`
  * `numpy`
  * `skimage.color`
  * `skimage.morphology`
  * `glob`
  * `scipy.ndimage`
  * `matplotlib.patches`
  * `skimage.filters`
  * `skimage.exposure`
  * `os`
    
## Contact
For any questions or further information, please contact [randolfnkimo@gmail.com].
