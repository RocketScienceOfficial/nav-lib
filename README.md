# Rocket Navigation Library

## Overview
This repository contains all scripts needed to derive Extended Kalman Filter equations, simulate either fake or real data and analize it

There are also scripts used to download current magnetic tables (NOAA) and containing equations for transforming geographic coordinates

## Features
1. EKF
   - Matrices and equations derivation (C files)
   - Simulation using fake and real data
   - Generating fake CSV data
   - Plotting results
2. Geo
   - Downloading magnetic data from NOAA and saving it in C header file
   - Functions for usage of magnetic data
   - Functions for transforming geographic coordinates

## Setup
Install dependencies:

```
pip install -r requirements.txt
```

## Usage
The project is written in Python and each folder is a [package](https://docs.python.org/3/tutorial/modules.html#packages)

Some scripts only provide useful functions!

For example to generate EKF equations run (from project root directory):

```
python -m ekf.derivation
```