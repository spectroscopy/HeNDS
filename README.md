# HeNDS

This is a Mathematica program for calculating the average Helium NanoDroplet Size (HeNDS) given a range of input variables (temperature, pressure, and nozzle diameter).

Place HeNDS.nb and HeNDS_batch.nb in same folder then run "HeNDS_batch.nb".

Calculations are for Regions I, II, I&III, II&III, and III for T>Tc (5.2014 K); see Fig. 9 in McCarty, R. D., J. Phys. Chem. Ref. Data, 2 (4), (1973), 923-1042.

Output values are suppressed when the input pressure is greater than the vapor pressure (for a given input temperature).

Example output for a 5.0 micron nozzle diameter:

![HeNDS_batch](https://user-images.githubusercontent.com/75122115/113648886-5f4cef80-965b-11eb-92a5-72a0d43c3dd1.png)
