# ASA-weighted Vertical Derivative (AVD)

This repository contains GNU Octave / MATLAB-compatible scripts used to generate the synthetic magnetic models and enhancement attributes presented in the paper:

**“ASA-weighted Vertical Derivative (AVD) for Magnetic Anomaly Enhancement”**

## Description

The codes implement synthetic magnetic responses for simple geological models, including a buried body, a vertical dike, and a vertical contact. Enhancement attributes are computed based on the amplitude of the analytic signal (ASA), vertical derivatives, and related directional attributes.

These scripts were used to generate the synthetic examples and figures presented in the associated publication.

## Requirements

- GNU Octave (version 6.0 or later)  
  or  
- MATLAB-compatible environment

## Files

- `synthetic_models.m`  
  Generates synthetic magnetic profiles for body, dike, and contact models.

- `attributes_asa_avd.m`  
  Computes ASA, vertical derivatives (AVD), ISA, Tilt Angle, and related enhancement attributes.

- `quick_test.m`  
  Quick test script that reproduces representative synthetic models and enhancement results shown in the paper.

## How to run

1. Open GNU Octave.
2. Navigate to the repository folder.
3. Run the following command:

```octave
quick_test
synthetic_models
attributes_asa_avd
