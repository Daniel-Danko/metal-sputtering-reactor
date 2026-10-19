# Metal Sputtering Reactor

**Design, simulation and development of a custom magnetron-based vacuum deposition system.**

## Overview

This repository documents the engineering development of a metal sputtering reactor featuring a custom annular magnetron topology.

The project investigates the electromagnetic design, magnetic-field distribution, mechanical integration, thermal management and vacuum interfaces of the reactor. Numerical simulations are used to guide design decisions and establish a basis for future plasma modelling and experimental validation.

## Current Research Focus

- Electromagnetic modelling using FEMM and ANSYS Maxwell
- Magnetic-field extraction and analysis at the target surface
- Verification of field components, coordinate conventions and units
- Comparison of simulation results under equivalent modelling conditions
- Preparation of magnetic-field inputs for plasma simulation
- Development of the cooling, mechanical and vacuum systems

## Repository Structure

| Directory | Contents |
|---|---|
| `docs/` | Engineering documentation and design history |
| `simulation/femm/` | FEMM models and associated data |
| `simulation/ansys-maxwell/` | Maxwell models and field exports |
| `simulation/plasma/` | Plasma modelling and benchmark cases |
| `analysis/` | Data processing, calculations and figures |
| `data/` | Raw and processed datasets |
| `cad/` | CAD models and engineering drawings |
| `experiments/` | Experimental protocols and measurements |
| `references/` | Scientific literature and bibliography |

## Methodology

Simulation inputs, raw outputs and processed results are kept separate wherever practical. Analysis scripts are intended to make derived results reproducible and to document unit conversions, coordinate transformations and validation checks.

Numerical predictions are distinguished from experimentally validated results.

## Development Status

The project is under active research and development. Magnetic-field analysis is an established workstream; model-to-model validation, plasma coupling and experimental verification remain separate development milestones.

## Scientific References

Scientific claims and comparisons should be supported by cited literature. Model assumptions, limitations and unresolved questions are documented alongside the relevant results.
