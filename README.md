# image-edge-detector
Program accepts a ppm 6 image as a command line argument. imath.c will then create a new output image in grayscale where the brighter the pixel,
the more defined of an edge that exists at that point. Calculates edges using the lapacian filter and multithreading to speed up computation.
