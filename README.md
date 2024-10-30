# Animated Text Effect Using CSS

This project showcases a stylized animated text effect using CSS animations. The text effect includes a background animation with a clipping path that gives the text a wave-like motion, creating an eye-catching design.

## Features

- **Dynamic Text Animation**: Uses CSS `@keyframes` to animate the `clip-path` property, creating a dynamic wave effect that repeats infinitely.
- **Dual Layered Text**: The main text has two overlapping layers:
  - One with a black color for the shadow effect.
  - One with a vibrant pink color (`rgb(255, 70, 104)`) that animates, providing the illusion of movement.
- **Custom Font**: Includes a Google font (`Poppins`), giving the text a modern, clean style.

## Technologies Used

- **HTML**: Structure for the animated text effect.
- **CSS**: Handles text styling, animations, and layout.
- **Google Fonts**: Imports the `Poppins` font from Google Fonts for a polished look.

## How It Works

1. **Overlayed Text Layers**: Two `<h1>` elements are stacked on top of each other. The second layer is animated to reveal portions of the pink text beneath.
2. **Keyframe Animation**: The `@keyframes` rule animates the `clip-path` property, creating the visual effect of movement across the text. The animation runs infinitely for a continuous effect.
3. **Positioning**: The `.container` class is positioned slightly to the right and bottom of the screen, giving a unique layout placement.

## Installation

To use or modify this project:

1. Clone or download the files to your local machine.
2. Ensure you have an active internet connection for the Google Fonts link.

## Customization

- **Text Color**: Update the color in `.container h1:nth-child(2)` to change the animated layer's color.
- **Animation Speed**: Adjust the `animation` duration in the `move` keyframe to control the animation speed.
- **Font Size**: Modify the `font-size` in `.container h1` to increase or decrease text size.


