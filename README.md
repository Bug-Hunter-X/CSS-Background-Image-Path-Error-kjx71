# CSS Background Image Path Error

This repository demonstrates a common error in CSS involving incorrect paths for background images. The `bug.css` file contains the erroneous code, while `bugSolution.css` provides the corrected version.  The issue stems from using a relative path that is not correctly resolving the location of the image file relative to the CSS file.

## How to Reproduce

1. Clone this repository.
2. Open `bug.html` in your browser.  You will see that the background image is missing.
3. Open `bugSolution.html` in your browser.  You will see that the background image now displays correctly.

## Solution

The solution involves verifying the relative path used for the `background-image` URL. Ensure that the path correctly points to the location of the image file from the perspective of the CSS file.