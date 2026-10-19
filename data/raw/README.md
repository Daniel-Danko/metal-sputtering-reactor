# Raw Data

This directory stores original, unmodified data exported from simulation tools or acquired during experiments.

## Rules

- Preserve original files byte-for-byte whenever practical.
- Do not overwrite raw exports with corrected or reformatted data.
- Record the originating solver or instrument, export date, units, coordinate convention and relevant model/run identifier.
- Keep a copy of the source filename in processing documentation so every derived result can be traced back.
- If a file must be redacted or converted for compatibility, retain the original where permitted and document the derivative.

## Expected data

Examples include FEMM and ANSYS Maxwell field exports, as well as original measurement files.

## Large files

Avoid committing solver caches, temporary files or redundant mesh dumps. Consider Git LFS for large, important native model files. Do not commit confidential or third-party files unless redistribution is permitted.
