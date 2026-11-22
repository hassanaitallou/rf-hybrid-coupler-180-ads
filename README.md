# RF Hybrid Coupler 180° — Design & Simulation (ADS)

RF / microwave study: theoretical analysis, S-parameter study, design and simulation of a **180° hybrid ring coupler** in the **S-band** with **Advanced Design System (ADS)**.

## Overview

The 180° hybrid ring coupler is a four-port passive component used to split or combine RF signals with a defined phase relationship (0° / 180°). This repository documents the study, the design methodology and the simulation results.

## Objectives

- Understand the operating principle of the hybrid ring coupler
- Dimension the ring for the S-band centre frequency
- Simulate the S-parameters and validate the expected behaviour
- Analyse balance, isolation and matching

## Theory

The hybrid ring (rat-race coupler) consists of a ring of total electrical length 3λ/2 with four ports spaced λ/4 apart. Under matched conditions:

- Input at port 1 → equal outputs at ports 2 and 4, isolated port 3
- Input at port 3 → outputs at ports 2 and 4 in phase opposition (180°)
- S-parameters: S11 (matching), S21 / S41 (transmission), S31 (isolation)

## Simulation (ADS)

- Schematic of the ring coupler with ideal transmission lines
- S-parameter simulation over the S-band
- Extraction of matching, isolation, amplitude balance and phase difference

## Results

- Matching and isolation evaluated on the S-band
- Amplitude balance and 180° phase difference characterised
- Design rules and methodology documented for reproduction

## Future Improvements

- Microstrip implementation and layout simulation
- Broadband / multi-section design
- Comparison with branch-line and Lange couplers
