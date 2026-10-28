# Urban Flood Simulation Using 3D City Models

A computational framework for simulating urban flood propagation through rainfall-runoff modeling, grid-based water-flow computation, dynamic water-depth analysis, and 3D visualization.

## Overview

This project aims to simulate how rainfall-driven flooding develops and propagates across an urban environment using a 3D city model and a grid-based simulation approach. It focuses on modeling water movement over time and visualizing flood behavior through maps, 3D representations, and animations.

## Core Capabilities

- **Rainfall–Runoff Modeling:** Represent rainfall inputs and estimate effective runoff using configurable parameters.
- **Grid-Based Water Flow:** Compute water transfers between neighboring cells to simulate flood propagation.
- **Dynamic Water-Depth Analysis:** Update and track water depth across simulation cells over time.
- **Boundary Condition Handling:** Define water-flow behavior at the edges of the simulation domain.
- **Flood Visualization:** Present simulated results through 2D flood maps, 3D city visualizations, and time-based animations.
- **Simulation Analysis:** Support mass-balance checks and analysis of changing flood conditions.

## System Workflow

1. **Data Input:** Load the 3D city model, rainfall inputs, and simulation parameters.
2. **Pre-processing:** Prepare the computational grid and required model inputs.
3. **Simulation:** Calculate rainfall contributions, water transfers, losses, and updated water depths at each time step.
4. **Visualization:** Display flood propagation and changing water levels.
5. **Output:** Generate maps, visualizations, animations, and simulation results.

## Technology Stack

- Python
- Google Colab
- NumPy
- Matplotlib
- Trimesh
- GLB-based 3D city models

## Project Status

**Status: In Development**

The project is being developed as an academic simulation and visualization framework. Its capabilities and accuracy will depend on the implemented flow model, terrain elevation data, rainfall inputs, drainage representation, and boundary conditions.

## Limitations

A 3D city model provides geometric visualization but does not necessarily contain accurate ground elevations, drainage networks, or hydrological information. Results based on assumed parameters should therefore be considered illustrative until the model is validated against suitable geographic data and observed flood conditions.

## Future Scope

- Integrate digital elevation models (DEMs) and terrain data.
- Improve water-flow computation and flood propagation.
- Incorporate building footprints and drainage information where available.
- Enhance time-dependent 3D flood visualization.
- Evaluate simulation performance using mass-balance checks and reference flood data.

## Objective

To develop a structured and extensible framework for exploring urban flood dynamics through computational modeling and 3D visualization.
