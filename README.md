# Heart Trail Animation

This repository contains a JavaScript code snippet that creates a heart trail animation effect on the webpage. The animation creates heart-shaped particles that follow the mouse movement, leaving a trail of hearts behind.

## Usage

To use this animation effect on your webpage, follow these steps:

1. Include the JavaScript code in your HTML file or link the JavaScript file to your HTML file.
2. Make sure you have a container element on your page, such as the `<body>` element or any other element you want to attach the animation to. For this example, we're using the `<body>` element.
3. Add an event listener to the container element for the `mousemove` event.
4. Inside the event listener, create a `<span>` element to represent each heart particle.
5. Set the position of the `<span>` element to the current mouse position using `event.offsetX` and `event.offsetY`.
6. Generate a random size for the heart particle using `Math.random()` and apply it to the width and height styles of the `<span>` element.
7. Append the `<span>` element to the container element to display the heart particle.
8. After a certain period of time, remove the `<span>` element from the container element to clear the trail.

Feel free to customize the animation by adjusting the styling, such as the heart shape, colors, or duration.

## Contributions

Contributions to improve or extend the heart trail animation are welcome! If you have any suggestions or improvements, please submit a pull request.
