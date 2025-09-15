The script is part of Lojko et al., (2026) "Warm-Conveyor Belt Persistence and Upstream Cyclone Tilt Shape the Predictability of a Rossby Wave Breaking Event". 
Pre-Print link: (Once available)

The script assigns amplitude (more or less amplified) and tilt direction (cyclonic, neutral or anti-cyclonic) to Rossby waves. The potential vorticity field is used. Specifically, contours of 2 potential vorticity units are used.
The amplitude is assigned based on a latitude threshold. The tilt is based on applying a weighted linear regression to the coordinates of the 2 PVU contour field, the slope value obtained determines tilt. 

Key parameters that can be easily modified in the script include:

PVU_THRESHOLD: What contour level to use (default = 2) 

THRESHOLD: Regression slope threshold for unclassified classification (default = 0.15)

MIN_CONTOUR_LENGTH: Minimum number of points in contour to classify be used in the calculation (defaukt = 30 points)

AMPLIFICATION_LAT: Threshold latitude to classify more or less amplified (default = 62)
