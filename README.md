# Uncommon HTML Bug: Accessing Non-Existent Element

This repository demonstrates a common yet easily overlooked error in HTML JavaScript interaction: attempting to access properties of an element that doesn't exist.

The `bug.html` file contains the erroneous code.  The `bugSolution.html` file provides a corrected version.

This error frequently occurs when dealing with dynamically generated content or elements that might not always be present on the page.  Always check for the existence of an element before attempting to manipulate its properties to prevent runtime errors.