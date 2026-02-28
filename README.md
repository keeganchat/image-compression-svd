# Low-Rank Matrix Approximation for Image Compression
## Overview
This project demonstrates the application of Singular Value Decomposition (SVD) to perform lossy image compression. By retaining only the most significant singular values of an image's RGB color matrices, we reconstruct compressed images and quantify the tradeoff between image quality and file size.

## Methods
* Decomposed images into RGB channels and applied truncated SVD to each
* Measured reconstruction quality using the Frobenius norm
* Modeled the relationship between singular values retained and JPEG file size
* Compared compression performance across multiple images

## Tools & Concepts
Python, NumPy, matplotlib, PIL — SVD, low-rank approximation, Frobenius norm
## Results
Images compressed to under 5% of original singular values remained visually interpretable, demonstrating significant size reduction with minimal perceptible quality loss.
## Paper
Full academic paper included — see Image_Compression_SVD.pdf
