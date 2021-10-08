# Test cases from "Two-Stage Homotopy Method to Incorporate Discrete Control Variables into AC-OPF"
These are the synthetic networks tested on for the paper "Two-Stage Homotopy Method to Incorporate Discrete Control Variables into AC-OPF", submitted for consideration for PSCC 2022 <arxiv link>.

## Source
These are modified versions of synthetic networks provided by ARPA-E as part of the Grid Optimization Competition (Challenge 2). The original cases can be found [here](https://gocompetition.energy.gov/challenges/23/datasets). 

## Format
Each folder contains two files:
- case.raw: synthetic network information 
- case.jon: contains generator cost information, which is formatted according to the specification found in the [GO2 Problem Formulation](https://gocompetition.energy.gov/sites/default/files/Challenge2_Problem_Formulation_20210531.pdf). These files have been modified to ensure all generators have linear costs.

The "Star" directories have had initial settings for the discrete devices (tap ratio for tap-changer transformers, phase shift angle for phase shifter transformers, and initial B value for switched shunt banks) removed. For taps and phase shifts, the median setting was written. For shunts, initial B is set to 0.
