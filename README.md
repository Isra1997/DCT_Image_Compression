# DCT Image Compression

# DCT_Compression_RMS
A Python function that takes a image as an input and does the following:
* Computes the Discrete Cosine Transform (DCT) of a gray-scale image
* Discards coefficients with magnitude <10
* Computes the inverse DCT of the modified coefficients
* Computes the root-mean-square error between the reconstructed image and the original image

# DCT_Compression
A Python function that takes an image and the size of the DCT block (n) and does the following:
* Divides the image to multiple n x n subimages
* Computes the Discrete Cosine Transform (DCT) of each subimage
* Discards coefficients with magnitude <20
* Computes the inverse DCT of each subimage
* Reconstructs the original image
Examine the output image when the function is applied to the “cameraman.tif” image with n = 2, n = 4, n = 8 and n = 16.
