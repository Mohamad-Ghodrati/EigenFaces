# Eigenfaces

The notebook demonstrates two applications of Eigenfaces: facial recognition and image compression. Eigenfaces utilize Principal Component Analysis (PCA) to extract the most salient features from a dataset of facial images.

📓 **Explore the detailed Jupyter Notebook [here](./EigenFaces.ipynb)**.


<img src="/images/Eigenfaces.jpg" alt="First 4 Eigenfaces">



## Overview

### Facial Recognition

By projecting new faces onto the subspace spanned by the extracted eigenfaces, we can effectively compare them to known faces and establish matches or non-matches.


**Facial Recognition Results:**

![Facial Recognition GIF](https://raw.githubusercontent.com/Mohamad-Ghodrati/EigenFaces/main/images/Eigenfaces0.gif)

### Image Compression

Eigenfaces can also be leveraged for image compression. By representing images using a smaller set of eigenfaces and corresponding coefficients, we can significantly reduce the storage requirements while preserving essential facial features.

#### Reconstruction:

In the following GIF, you can observe how image reconstruction quality improves as more eigenfaces are used.

![Reconstruction GIF](https://raw.githubusercontent.com/Mohamad-Ghodrati/EigenFaces/main/images/Eigenfaces1.gif)




## Contribution

Feel free to contribute to this project by:

- Reporting issues or suggesting improvements.
- Implementing additional functionalities.
