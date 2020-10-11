# Automatic Nipple Detection 
Artificial Vision and Pattern Recognition, Universitat Rovira i Virgili

## Introduction
The paper titled ‘Automatic nipple detection in breast thermograms’ proposes an unsupervised, automatic, accurate, simple and fast method to detect nipples in thermograms. The main stages of the proposed method are: human body segmentation, determination of nipple candidates using adaptive thresholding and detection of the nipples using a novel selection algorithm.

## Paper
[Automatic nipple detection in breast thermograms](./paper/paper.pdf), 2016 <br>
Mohamed Abdel-Nasser, Adel Saleh, Antonio Moreno, Domenec Puig.

## Usage
Open the Matlab Live Script 'nipple_detection.mlx' and run it!

## Directories
- input: contains the input images for the script.
- segmented (runtime): contains the images created after the human body segmentation phase (image + binary mask).
- filtered (runtime): contains the binary images created after the adaptive threshold phase.
- output (runtime): the output images with the nipples labelled.
- paper
