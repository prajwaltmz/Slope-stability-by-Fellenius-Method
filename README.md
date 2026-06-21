# Slope Stability Analysis Tool

## Overview

This project is a Python-based slope stability analysis tool developed and tested using the Anaconda Python environment.

The program allows users to input slope geometry parameters through a simple interface. Based on the provided inputs, the code automatically:

* Generates the slope geometry
* Creates potential slip surfaces
* Performs stability calculations
* Calculates the Factor of Safety (FOS)
* Produces graphical plots showing the slope and critical slip surface

This tool can be used for educational purposes, research, and preliminary slope stability assessments.

## Environment

The code was developed and tested in:

* Anaconda Distribution
* Python 3.x

## Required Inputs

The user will be prompted to enter slope parameters such as:

* Slope height (H)
* Slope angle or geometry
* Soil properties
* Unit weight
* Cohesion
* Friction angle
* Groundwater conditions (if applicable)

## Output

After providing the required inputs, the program automatically:

1. Creates the slope geometry.
2. Searches for potential slip surfaces.
3. Computes the Factor of Safety (FOS).
4. Identifies the critical slip surface.
5. Displays graphical results.

## Installation

1. Install Anaconda.
2. Clone this repository:

```bash
git clone https://github.com/yourusername/repository-name.git
```

3. Navigate to the project folder:

```bash
cd repository-name
```

4. Install required packages:

```bash
pip install -r requirements.txt
```

## Running the Program

Run the main Python file:

```bash
python main.py
```

Follow the prompts and enter the required slope parameters.

## Example Workflow

1. Enter slope height.
2. Enter soil properties.
3. Run analysis.
4. Review generated plot.
5. Check calculated Factor of Safety (FOS).

## Disclaimer

This software is intended for educational and research purposes. Engineering decisions should always be verified using established commercial software and professional engineering judgment.
