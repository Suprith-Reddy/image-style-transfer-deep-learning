# image-style-transfer-deep-learning

Although there is a quick development in the style transfer, current methodologies for multi-style or arbitrary style transfer are using feed-forward network that are commonly produces low quality and less flexible images. It is profoundly tricky to accomplish style transfer using one dimensional representation. To overcome this
challenge, we used a Co-Match layer which matches the second order statistics with style images. We also built
a Multi-style Generative Network (MSG-Net) which improves the performance and an up-sampled convolution
that avoids checkerboard artifacts created by fractional stride. This MSG-Net for style transfer is well-suited
for most of the applications such as color preservation, spatial and brush stroke size control, and content-style
interpolation. We have used Torch, Torchvision, PIL, and Numpy frameworks for our implementation.
