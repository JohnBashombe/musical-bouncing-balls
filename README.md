# Musical Bouncing Balls - Repelling Balls

<img width="1280" height="759" alt="Screenshot 2025-08-12 at 12 46 48" src="https://github.com/user-attachments/assets/5c8a0e10-b18b-4182-b114-ef341cb1297c" />

## Overview

This project is an HTML5 Canvas animation featuring colorful balls that bounce around the screen, play unique musical tones when they hit walls, and produce different tones when colliding with each other. The balls repel each other upon contact, ensuring they never overlap or stick together. A soft, subtle background text reading "Klassik Details" is displayed to add a visual watermark without interfering with the animation.

## Features

* **HTML5 Canvas Animation** with smooth rendering.
* **20 colorful balls**, each with a unique size, velocity, color, and musical note.
* **Wall collision sounds**: Each ball plays its own tone when hitting a wall.
* **Ball-to-ball collision sounds**: A separate sequence of tones plays when balls collide.
* **Repelling physics**: Balls push away from each other upon contact.
* **Radial gradient fill** for a glowing visual effect.
* **Soft background text** for branding.

## File Structure

All HTML, CSS, and JavaScript are contained within a single `.html` file.

## How to Run

1. Save the code as an `.html` file (e.g., `musical_balls.html`).
2. Open the file in any modern web browser (Chrome, Firefox, Edge, Safari).
3. Click anywhere on the page to allow audio playback (due to browser autoplay restrictions).

## Customization

* **Number of Balls**: Change the `for` loop limit in the ball initialization section.
* **Colors**: Edit the `colors` array.
* **Notes**: Adjust the `notes` and `collisionNotes` arrays for different sound sets.
* **Background Text**: Modify the `<div id="backgroundText">Klassik Details</div>` and its CSS.

## Requirements

* A modern web browser with HTML5 Canvas and Web Audio API support.
* JavaScript enabled.

## License

You may use and modify this code for personal or educational projects. For commercial use, please credit the original creator.
