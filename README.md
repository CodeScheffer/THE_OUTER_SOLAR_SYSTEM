# THE_OUTER_SOLAR_SYSTEM

Geometric Integrators for the Outer Solar System

Author: Wellinton C. Scheffer

Numerical integration of the outer solar system (Sun, Jupiter, Saturn,
Uranus, Neptune, Pluto) as a Hamiltonian N-body problem, comparing
classical and geometric integrators. Initial data: 5 Sept 1994, 0h00
(Ahnert's Kalender für Sternfreunde 1994). Units: AU, earth days, solar masses.

## Methods implemented

| Method              | Order | Symplectic | Implicit |
|---------------------|-------|------------|----------|
| Explicit Euler      | 1     | no         | no       |
| Implicit Euler      | 1     | no         | yes (Newton) |
| Symplectic Euler    | 1     | yes        | no       |
| Störmer–Verlet      | 2     | yes        | no       |
| Yoshida (3 × SV)    | 4     | yes        | no       |
| Discrete gradient (midpoint) | 2 | no (conserves H) | yes (Newton) |
