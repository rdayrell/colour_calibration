[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.7877540.svg)](https://doi.org/10.5281/zenodo.7877540)

# Colour calibration

The colour chart Spyder Checkr® 24 card (Datacolor, NJ, USA) is used for colour calibration of images. All images were acquired with a flatbed scanner (HP Scanjet G4010) at a resolution of 1,200 dpi at the same colour and light settings. The code creates a colour conversion matrix, which is then applied to images.

# Contents

- Jupyter notebook with code for colour calibration.

files:
- colour chart scans
- csv file with colour standards

test_images:
- 4 test images with no colour correction

test_results:
- colour correction image
- difference between original and colour corrected image (it requires the highest level of screen brightness to be visualised as differences are subtle)

results:
- 4 test images after colour correction
