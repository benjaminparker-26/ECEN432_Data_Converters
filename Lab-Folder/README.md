# ECEN432_Data_Converters
# Pipelined ADC Behavioral Modeling
This project explores a 3-stage, 2.5-bit/stage Pipelined ADC architecture implemented in Python.

## Key Features
* **Redundancy:** Implements 1-bit interstage redundancy to mitigate sub-ADC comparator offsets.
* **Non-Ideal Modeling:** Analyzes the impact of gain error, DC offset, and harmonic distortion (alpha2, alpha3) on SNDR and ENOB.
* **Sensitivity Analysis:** Compares redundant (2.5-bit) vs. non-redundant (2-bit) architectures.
