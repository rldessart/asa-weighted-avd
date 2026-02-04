# ASA-weighted Vertical Derivative (AVD)

This repository contains GNU Octave / MATLAB-compatible scripts used to generate the synthetic magnetic models and enhancement attributes presented in the paper:

"ASA-weighted Vertical Derivative (AVD) for Magnetic Anomaly Enhancement"

## Description

The codes implement synthetic magnetic responses for simple geological models (body, vertical dike, and contact) and compute enhancement attributes based on the amplitude of the analytic signal (ASA) and vertical derivatives.

## Requirements

- GNU Octave (version 6.0 or later) or MATLAB-compatible environment

## Files

- synthetic_models.m : Generates synthetic magnetic profiles for body, dike, and contact models
- attributes_asa_avd.m : Computes ASA, AVD, ISA, Tilt Angle, and related attributes
- quick_test.m : Quick test script reproducing the main synthetic figures of the paper

## How to run

1. Open GNU Octave
2. Navigate to the repository folder
3. Run:

```octave
quick_test
% Quick test for ASA-weighted AVD method

clear all; close all; clc;

model_type = 2;   % 1=body, 2=dike, 3=contact

synthetic_models
attributes_asa_avd
