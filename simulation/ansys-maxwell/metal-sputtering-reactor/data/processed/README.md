# Processed Data

This directory contains datasets derived from original simulation exports or experimental measurements.

## Rules

Every processed dataset should identify:

- its source file(s) in `data/raw/`;
- the processing script or method;
- units and coordinate conventions;
- any filtering, interpolation, resampling or unit conversion;
- relevant model/run identifiers and known limitations.

## Reproducibility

Prefer generating these files from version-controlled scripts in `analysis/` rather than editing values manually. Do not place processed results in `data/raw/`.

## Magnetic-field processing

Check units before conversion and apply each conversion exactly once. Before deriving normal and tangential components, confirm the field-coordinate convention and the local surface normal. Include validation checks for missing values, non-finite values, unexpected ranges and inconsistent sample locations.

## Status

Derived datasets will be added when the source exports and processing pipeline are verified.
