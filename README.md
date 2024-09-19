# Optimal Airport Operations using Quantum Algorithms

From basic research to everyday use: Dynex has developed quantum algorithms to optimize operations at airports. The goal of this joint endeavor is to solve the so-called “airport gate assignment problem” at airports around the world.

## Problem Formulation
We will optimize flight assignments to gates at an airport using PyQubo and Dynex. Our goal is to minimize conflicts and efficiently manage gate assignments considering various constraints.

## Constraints
- Gate Availability: Each flight must be assigned to an available gate, with no overlaps in time.
- Flight Timing: Flights must be scheduled without conflicts, with at least a one-hour gap between consecutive flights at the same gate if possible.
- Parking Position Constraints: Each flight should be assigned to a parking position based on the apron type and availability.
- Flight Conflicts: Avoid conflicts where multiple flights are assigned to the same parking position at the same time.
