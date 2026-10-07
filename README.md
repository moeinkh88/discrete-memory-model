# Memory as a Mechanistic Perspective on Rise and Decline in Complex Systems

This repository contains the Python code to reproduce the discrete memory simulations and figures for the manuscript *Memory as a Mechanistic Perspective on Rise and Decline in Complex Systems*.

## Included Scripts

* **`memory_shapes_discrete.py`**: Generates **Figure 4**, which visualizes five types of discrete memory kernels: exponential, shifted Heaviside, bandpass Heaviside, Gamma, and fractional power law.


* **`scandal_discrete.py`**: Generates **Figure 5**, which demonstrates the dynamical consequences of these five memory kernels by simulating collective social behaviour (public outrage) in response to a discrete historical event (a scandal), compared against a memoryless Markovian baseline.



## Requirements

The scripts require a standard Python environment with the following packages:

* `numpy`
* `matplotlib`
* `scipy`

## Usage

Run the scripts directly from the command line. Each script will display the plot in an interactive window and automatically save both `.png` (at 300 dpi) and `.eps` versions of the figures to your current working directory.

```bash
python memory_shapes_discrete.py
python scandal_discrete.py

```

## Authors

Björn Kröger, Moein Khalighi, Aura Raulo, Silva Nurmio, Mirva Peltoniemi, Indrė Žliobaitė, and Leo Lahti.