# Uncommon HTML Error: Typo in getElementById

This repository demonstrates a subtle yet common error in HTML and JavaScript interaction.  The code attempts to modify the content of a div element using JavaScript, but contains a typo in the function call. This results in the script failing without throwing an error, making it difficult to debug.

## Bug Description
The bug lies in the JavaScript code which uses `document.getElementByIdx` instead of the correct `document.getElementById` to select the div element.  This typo leads to the script failing without any obvious console errors, making it a challenging error to identify.

## Solution
The solution simply corrects the typo in the function call, ensuring the correct method `document.getElementById` is used to select the div element.