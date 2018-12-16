# Project
Histogram

## Histogram of a Coloured (RGB) Image
An image histogram is a graphical representation of the tonal distribution in a digital image. The horizontal axis of the graph represents the tonal variations, while the vertical axis represents the number of pixels in that particular tone. 

Dark tones are displayed on the left side of the histogram. The middle portion of the histogram represents midtones. As you move rightward, tones get lighter. Histogram will give you a general idea of an image’s exposure.RGB histogram is essential if you who want the best, most accurate colors your camera is capable of producing.

Histograms usually display information for three primary colors – red, green and blue – and are known as RGB histograms.

## RGB image to grayscale
The rgb2gray function converts RGB images to grayscale by eliminating the hue and saturation information while retaining the luminance.

Formula: Grayscale image = ( (0.299 R) + (0.587 G) + (0.114 * B) )

## Otsu Thresholding
A grayscale image can be converted into a black-and-white image by choosing a threshold and converting all values above the threshold to the maximum intensity and all values below the threshold to the minimum intensity.

Otsu's thresholding method involves iterating through all the possible threshold values and calculating a measure of spread for the pixel levels each side of the threshold, i.e. the pixels that either fall in foreground or background. The aim is to find the threshold value where the sum of foreground and background spreads is at its minimum.

