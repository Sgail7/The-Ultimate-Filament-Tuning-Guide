# The Ultimate Filament Tuning Guide

## How to tune 3D printer filaments to perfection!

This guide details how I tune in my 3d printing filaments. It takes approximately 60-70 grams of filament and a few hours of time, including print times. If your printer profiles are tuned in properly, following this guide will give you the best quality out of the filaments that you can buy. This is NOT a guide on how to fine tune your printer's motion system and settings, for that, please see [Ellis' Excellent Print Tuning Guide](https://ellis3dp.com/Print-Tuning-Guide/). My flowrate calibration method does not agree with his, however I am more interested in the dimensional accuracy of my parts rather than their looks.

This guide assumes that you are using Klipper firmware, but everything except for the probe calibration method is transferrable to any other 3D printer firmware.

# THE GUIDE

### First Time Steps

1. First Layer Calibration
2. Elephant's Foot Compensation
3. Infill/Perimeter Encroachment Test
4. Bridge Flow Rate Calibration Test

### Mandatory Steps

1. Temperature Test
2. Volumetric Flowrate Test
    - Uses Volumetric Flow Test RR.3mf
3. Linear Advance Test
4. Flow test
    - +-2% is negligible
5. Retraction Test
6. Fan Speed Test
7. Minimum Layer Time Test
    - Use Minimum Layer Time Test.3mf
8. Minimum Layer Speed Test
    - Use Test Pieces_Cone 10mm Tall.stl
9. Validate Results
    -Print a Voron Cube to validate bridging and corner accuracy
    - Print a Cali-Dragon to validate small detail quality, layer quality, and cooling characteristics

### Optional (but still recommended) Steps

9. Material Expansion/Contraction Calibration
10. Also include manual bed leveling with feeler gauges and probe calibration.
11. Include something about tuning retraction and un-retraction speeds with the stringing-test model included.
12. VFA Tuning Tests
    - 
    - 
13. 
14. 
15. 