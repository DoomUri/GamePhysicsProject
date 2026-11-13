# GamePhysicsWork

Research project exploring the application of physics principles, mainly kinematics, in video games and simulations. Includes theoretical research and five interactive physics simulators developed from scratch using HTML, CSS, and JavaScript.

## Repository Structure

The repository is organized into two main folders:

- **`Documentation/`**: Contains all the theoretical research, including explanations of the physics principles studied and the learning process of the programming languages and graphical environments used throughout the project. It also includes an appendix with images and demonstrations.

- **`Code/`**: Contains all the source code for the five physics simulators. Each simulator is developed using HTML, CSS, and JavaScript.

## Technical Overview

The project includes five interactive physics simulators covering six different motion models:

- **MRU (Uniform Rectilinear Motion)**
- **MRUA (Uniformly Accelerated Rectilinear Motion)**
- **Projectile Motion**
- **1D Collision**
- **Circular Motion (MCU and MCUA)**

### Simulation Features

Each simulator allows users to customize different physical parameters before running the simulation. Depending on the model, these include initial velocity, acceleration, mass, and other simulation-specific properties.

The **Circular Motion** simulator implements both MCU and MCUA within the same code. Setting the angular acceleration to zero results in Uniform Circular Motion (MCU), while using a non-zero angular acceleration produces Uniformly Accelerated Circular Motion (MCUA).

In the **1D Collision** simulator, the size of each object's visual representation dynamically scales according to its assigned mass, providing a graphical representation of the mass differences.

All simulators, except for **1D Collision**, also offer the option to render the complete trajectory instead of playing the simulation directly. This allows users to visualize and analyze the resulting motion path.

### Implementation

The simulators are built using **HTML, CSS, and JavaScript**, following a modular approach to organizing the code:

- **HTML:** Defines the structure of each simulator and separates its different components.
- **CSS:** Organizes visual properties into classes, controlling the appearance and graphical representation of the simulations.
- **JavaScript:** Implements the simulation logic, button interactions, object movement, and physical calculations.

The movement of simulated objects is calculated using fundamental kinematics equations, applying the corresponding physical principles to determine their positions and motion over time.

This approach allows users to experiment with different physical parameters and observe how they affect the resulting motion in an interactive graphical environment.

## Running the Simulators

No installation or additional setup is required to run the simulators.

Simply open the corresponding `.html` file inside the `Code/` folder using any modern web browser to interact with the simulation.
