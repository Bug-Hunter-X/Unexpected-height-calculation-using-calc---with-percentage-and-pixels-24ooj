# Unexpected height calculation using calc() with percentage and pixels
This repository demonstrates a common CSS issue where using `calc()` with a percentage and pixel value for height, while intending to base the calculation on the element's height, inadvertently uses the width instead. This leads to an unexpected layout, particularly when the element's aspect ratio differs from the intended calculation.

## Bug
The `bug.css` file contains the erroneous CSS code.  The height is calculated unexpectedly.

## Solution
The `bugSolution.css` file shows how to solve this issue by correctly defining the height calculation. The solution calculates the height based on the element's parent or using the 'vh' unit which is based on the viewport height.

## How to reproduce
1. Clone this repository.
2. Open `index.html` (if provided) in a web browser. Observe the unexpected layout.
3. Examine the provided CSS files to understand the bug and solution. 