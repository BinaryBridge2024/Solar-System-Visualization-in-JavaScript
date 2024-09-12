# 3D Solar System Simulation

This project is a 3D simulation of the Solar System built using **JavaScript** and **Three.js**. It provides a visual representation of the planets orbiting around the sun, complete with their relative sizes, speeds, and distances. Users can interact with the simulation by zooming, panning, and rotating the view.

## Features

- **Realistic Solar System**: The planets are modeled to scale with respect to size and distance, and they orbit the sun at appropriate speeds.
- **3D Rendering**: Utilizes Three.js for rendering the 3D Solar System in the browser.
- **Interactivity**: Users can control the view by rotating, zooming, and panning around the scene.
- **Planet Information**: Display pop-ups with basic information about each planet when clicked.
- **Performance Optimization**: Efficient rendering for smooth simulation experience.

## Technologies Used

- **JavaScript**: The core programming language used to create the simulation.
- **Three.js**: A 3D library for rendering graphics in WebGL, used for creating and rendering the planets and their movements.
- **HTML/CSS**: For structuring and styling the user interface.

## Project Setup

### Prerequisites

To run the project locally, you'll need a simple HTTP server because some browsers block loading local files due to security policies. You can use one of the following:

- **Node.js**: Using a package like `http-server`.
- **Python**: Built-in HTTP server for local development.
- **XAMPP** or any other web server environment.

### Steps to Run the Project

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/BinaryBridge2024/solar-system-simulation.git

   ```
Run a local server Using Node.js:

If you have Node.js installed, you can use http-server

```bash
npm install -g http-server
http-server
 ```

Then, open the provided URL (usually http://localhost:8080) in your browser.

Using Python:

If you have Python installed, you can run a simple server:
```bash
python3 -m http.server
 ```

Then, open http://localhost:8000 in your browser.

Using XAMPP or another web server:

Place the project folder inside the server's htdocs directory (for XAMPP).
Start the server and navigate to http://localhost/solar-system-simulation