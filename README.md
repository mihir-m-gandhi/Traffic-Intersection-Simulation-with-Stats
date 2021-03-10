<p align="center">
 <img height=350px src="./simulation-output.png" alt="Simulation output">
</p>

<h1 align="center">Traffic Intersection Simulation with Stats</h1>

<div align="center">

[![Python version](https://img.shields.io/badge/python-3.1+-blue.svg)](https://www.python.org/downloads/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)

<h4>A simulation developed from scratch using Pygame to simulate the movement of vehicles across a traffic intersection having traffic lights with a timer. Some statistics and analytical features added to the simulation to help in Modelling problems, Data Analysis tasks, and AI applications.</h4>

</div>

-----------------------------------------
### Features added:

* `Vehicle counts` - The number of vehicles that have crossed the intersection are displayed adjacent to each traffic signal for each direction.
* `Time Elapsed` - The time elapsed since the start of the simulation is displayed at the top right.
* `Simulation Duration` - The total duration of simulation or end time can. be set. The simulation will quit automatically when time elapsed is equal to simulation time.
* `Printing timers on Terminal` - The timer values of all signals are printed on the Terminal every second. This is useful for effective debugging while customizing the simulation according to your application.
* `Printing cumulative statistics` - Statistics like direction-wise vehicle counts, total vehicles, and simulation time are printed on the Terminal at the end of the simulation, as shown in image below.

<p align="center">
 <img height=150px src="./stats.png" alt="Stats">
</p>

------------------------------------------
### Demo

The video below shows the final output of the simulation.

<p align="center">
    <img src="./Demo.gif">
</p>

------------------------------------------
### Prerequisites

[Python 3.1+](https://www.python.org/downloads/)

------------------------------------------
### Installation

 * Step I: Clone the Repository
```sh
      $ git clone https://github.com/mihir-m-gandhi/Traffic-Intersection-Simulation-with-Stats
```
  * Step II: Install the required packages
```sh
      # On the terminal, move into Traffic-Intersection-Simulation-with-Stats directory
      $ cd Traffic-Intersection-Simulation-with-Stats
      $ pip install pygame
```
* Step III: Run the code
```sh
      # To run simulation
      $ python simulation.py
```

------------------------------------------
### Author

Mihir Gandhi - [mihir-m-gandhi](https://github.com/mihir-m-gandhi)

------------------------------------------
### License
This project is licensed under the MIT - see the [LICENSE](./LICENSE) file for details.
