# Uncommon HTML Bug: Incorrect DOM Access

This repository demonstrates a subtle yet important error related to accessing DOM elements in HTML. The `bug.html` file shows the incorrect approach, while `bugSolution.html` provides the correct solution.

## Bug Description:

The bug lies in how the JavaScript code attempts to interact with the HTML element. The script fails because it doesn't properly select the element before attempting to manipulate it.

## Solution:

The correct approach involves using `document.getElementById()` to retrieve the DOM element by its ID before changing its `innerHTML` property.

## How to reproduce:

1. Clone the repository.
2. Open `bug.html` in your web browser. You should see an error in your browser's console.
3. Open `bugSolution.html` to see the corrected code and the expected output.