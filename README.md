# Intensity-Transformaiton-on-Image
Applying different intensity transformation functions on a Mammogram image.


Notation: r – pixel intensity of the input image; s - pixel intensity of the transformed image; L – the maximum intensity of the input image (e.g., L = 256 for an 8-bit grayscale image)

1. Given the mammogram image 𝐼 (‘Mammogram.png’), compute its negative image 𝐼𝑛, using 𝑠 = (𝐿 − 1) − 𝑟.

2. Apply log transformation onto the negative image 𝐼𝑛, i.e., 𝑠 = log (1 + 𝑟). (1pt)

3. Apply power-law transformation onto the negative image 𝐼𝑛, i.e., 𝑠 = 𝑟^𝛾. You can choose different 𝛾 to test it (e.g., 𝛾 = 0.1).

4. Apply the following piecewise linear transform for the contrast stretch on the negative image 𝐼𝑛, where 𝑟𝑚𝑖𝑛 is the 
minimum intensity value in the input image and 𝑟𝑚𝑎𝑥 is the maximum intensity value in the input image.

![Screenshot (1)](https://user-images.githubusercontent.com/104661324/222622561-55936732-2111-452b-b8da-0d569f1aea11.png)

