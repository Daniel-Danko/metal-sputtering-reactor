# Magnetic-Field Analysis

This directory contains scripts and derived outputs used to analyse magnetic-field distributions from FEMM and ANSYS Maxwell.

## Intended contents

- `scripts/`: reproducible processing and plotting scripts
- `figures/`: generated plots for reports and comparisons
- `tables/`: derived numerical summaries and comparison metrics

## Analysis workflow

1. Identify the original solver export and record its filename.
2. Verify column meanings, coordinate system and units.
3. Convert units exactly once and document every transformation.
4. Calculate the field magnitude and the normal/tangential components only after confirming the local surface normal and coordinate mapping.
5. Generate plots and tables from version-controlled scripts.
6. Record assumptions, limitations and processing-script version.

## Data integrity

Do not edit original solver exports in this directory. Keep source exports in `data/raw/` and derived datasets in `data/processed/`.

A previously identified processing issue involved an extra factor of 1000 being applied to a parallel-field profile. Any corrected result must be traceable to the source export and the exact processing steps. Verify the field definition and units before using the result for physical interpretation.

## FEMM–Maxwell comparison

A comparison is meaningful only when geometry, excitation, material properties, boundary conditions, evaluation locations, coordinate conventions and field definitions are sufficiently equivalent. Record differences rather than treating the solvers as interchangeable.

## Status

Processing scripts, automated checks and cross-solver validation are to be added as the source files and model settings are consolidated.
