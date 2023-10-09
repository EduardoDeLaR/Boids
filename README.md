# Boids 🐦

A simulation of flocking behavior inspired by Craig Reynolds' Boids algorithm. Watch as a group of entities, called "boids", imitate the complex maneuvers of real-world birds.

## Table of Contents

- [Description](#description)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Scripts](#scripts)
- [Contributing](#contributing)
- [Credits](#credits)

## Description

The Boids simulation demonstrates the collective behavior of decentralized entities. Each boid makes decisions based on local observations of its neighbors, leading to emergent patterns. Obstacles can be placed in the environment to observe how boids navigate and avoid them.

## Features

- **Obstacle Avoidance**: Boids can sense and avoid obstacles in their path.
- **Flocking Behavior**: Boids exhibit flocking behaviors such as alignment, cohesion, and separation.
- **Configurable Settings**: Adjust various parameters like boid speed, influence ranges, and obstacle detection to observe different behaviors.
- **Colorful Visuals**: Boids leave a colorful trail, creating a beautiful visual experience.

## Installation

1. Ensure you have Unity installed.
2. Clone this repository.
3. Open the project in Unity.
4. Build and play!

## Usage

1. Start the simulation and watch as boids flock together.
2. Watch to see how boids navigate around obstacles.
3. Adjust parameters to observe various flocking behaviors.

## Scripts

- **Boid.cs**: Core script that defines each boid's behavior, including movement, obstacle avoidance, and interaction with neighbors.
- **Neighborhood.cs**: Allows each boid to sense its local environment, determining nearby neighbors and obstacles.
- **Attractor.cs**: Pull boids toward a point of interest to keep the flock from flying off into the distance.
- **Spawner.cs**: Manages the generation of multiple boids in the scene and provides global settings for the simulation.
- **LookAtAttractor.cs**: Causes the camera to turn and look at the Attractor each frame.

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes.

## Credits

- **Eduardo De La Rosa**: Initial creation and development.
- **Craig Reynolds**: For pioneering the original Boids algorithm.
