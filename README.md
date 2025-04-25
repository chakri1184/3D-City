# 3D-City
# 3D City Project

## Description

This project creates a 3D city using **Three.js**, a popular JavaScript library for 3D graphics. The city is composed of buildings, smoke particles, and moving cars. The user can interact with the scene using the mouse to control the camera's view and explore the 3D world. 

### Features:
- Real-time rendering with **WebGL**.
- Dynamic cityscape with animated buildings, smoke, and moving cars.
- Fog and light effects to enhance the city atmosphere.
- Interactive mouse-based camera control to navigate the city.

## Technologies Used:
- **Three.js** - JavaScript 3D library for rendering the city and objects.
- **GSAP (GreenSock Animation Platform)** - For animations and transitions.
- **Bootstrap** - For styling and layout.
- **HTML5** & **CSS3** - For structure and styling of the webpage.

## Getting Started

### Prerequisites

To run this project locally, you’ll need the following installed:

- **Web Browser** (Chrome, Firefox, etc.)
- **Text Editor** (VSCode, Sublime, etc.)

### How to Run

1. **Clone the repository** to your local machine:

   ```bash
   git clone https://github.com/chakri1184/3d-city.git
## Project Structure
Project Structure
The project consists of the following files:

index.html – The main HTML file that includes the Three.js and Bootstrap links, and renders the 3D scene.

style.css – Custom CSS styles for the webpage.

main.js – The JavaScript file that defines the 3D city objects, lighting, camera settings, animations, and user interactions.

README.md – This file.

Key Code Details:
Scene Setup: A THREE.Scene() is created, where objects like buildings, smoke particles, and cars are added.

City Creation: Buildings are generated randomly, and their colors are randomized. Cars move along predefined paths with animations.

Camera Interaction: The camera is controlled by mouse movements, allowing users to look around the city.

Lighting: Ambient and spotlights are added to illuminate the scene.

License
This project is licensed under the MIT License – see the LICENSE file for details.

Acknowledgments
Victor Vergara for the original concept (codepen.io/vcomics/pen/aGmoae).

Three.js Documentation – https://threejs.org/docs/

Feel free to contribute to the project by submitting pull requests or issues!
