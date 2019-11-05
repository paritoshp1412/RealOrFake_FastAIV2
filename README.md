# RealOrFake_FastAIV2

An image classifier model built using fastAI.
We have modified the problem to differentiate between the noise patterns arising in a natural (real) vs an edited (fake) image. A high pass filter was used to extract the noise component of the image while reading it, by editing the corresponding function in the fastAI library.

The notebook serves as a guideline and proof of concept for the idea. The code here might be messy and out of place in certain sections.
