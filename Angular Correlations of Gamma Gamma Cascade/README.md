# Title: Angular correlations of  &#947;-&#947; cascade
### Aim: To measure the γ-γ angular correlaton in the decay of <sup>60</sup>Co by determining the multipole expansion coefficients experimentally and compare them against the theoretically obtained values.
#### Procedure:
###### 1. Preparation of setup: It involves the following:
   * Carefully placing the source on the mount at the center of the table.
   * Alignment and orientation of the detectors was checked with the distance from the center being 5cm.
   * The necessary connections were checked.
###### 1.2 Energy Branch-Adjusting gain:
   * Using an oscilloscope the outputs of the two amplifiers `A1` and `A2` were measured.
   * The amplifiers were set in the linear range.
###### 1.3 Timing Branch-Adjustment of CFD:
   * The threshold was set such that maximum noise could be filtered out without destroying the signal.
   * A set of reading were taken by varying the thresholds of the CFDs, once with source and once without source.
   * The counts was measured, which would tell us where signal/noise ratio is high.
   * From the graphs, the threshold was set at 50mV for both CFDs.
###### 1.4 Setting up the fast coincidence:
   * To compensate for the delay between the two fast signals, a fixed delay was introduced between a CFD and FC, and a variable in the other.
   * The resolving time was set at τ =20ns and the output was connected to a counter through an inverter and the coincidence counts was measured for various delays.
   * A graph was plotted and the region of maximum coincidence was obtained.
   * With the aid of the provided curve fit, the center was found at around 23.65± 0.19ns and FWHM of 28.3± 0.61ns, so a delay of 23ns was used for the experiment.
###### 1.5 Setting up the slow coincidence:
   * For the UC to give an output signal, the signals from the SCAs and the FC must be coinciding in time. 
   * This was done by connecting the outputs of the SCAs and the FC to an oscilloscope, and by changing the internal delays of the SCAs such that the signals coincided with the FC signal. The alignment was
      made by aligning the leading edges of the pulses.
###### 1.6 Calibrating the SCAs:
   * The SCAs were used to select γ ray events of the energy range corresponding to <sup>60</sup> Co transition.
   * The window width was kept constant all throughout the experiment because changing window widths would give varying counts and hence we cannot use the data for calibration. 
   * Using the graph the window for the both the SCAs was set from channel 500 to 800 as both photo-peaks were visible in this range.
##### 2. Measurements:
###### 2.1 Measurement of Angular Correlation:
   * One set of measurements were made with fine stepping of 30<sup>◦</sup> from 90<sup>◦</sup> to 270<sup>◦</sup> with a short count duration of 200±1s. This gives an idea of the overall angular dependence.
   * A second set of measurements were made at 90<sup>◦</sup> , 135<sup>◦</sup> , 165<sup>◦</sup> , 180<sup>◦</sup> , 195<sup>◦</sup> , 225<sup>◦</sup> , 235<sup>◦</sup> with a longer count duration of 400±1s. These data help us to precisely predict the correlation coefficients. At least four readings were necessary to obtain the three unknown parameters A,B and C with an error bar associated with the fit.
###### 2.2 Measurement of stability of setup:
   * Readings were taken at 180 ◦ at three different time intervals: at the beginning, in the middle and at the end of the measurements.
   * The count duration of each measurement was 400±1s. 
   * This was done to checkthe stability of the setup over the entire duration of the measurement process.
###### 2.3 Measurement of random coincidence:
   * Random coincidences do have an angular correlation in the pressence of misalignment. But in absence of misalignment they don’t have an angular correlation since the random sources of gamma rays causing the coincidence are isotropic in the Universe.
##### 3. Analysis:
###### 3.1 Subtracting random coincidence:
   * A random coincidence count N<sub>random</sub> =745 was obtained for a count duration of 400s at 180<sup>◦</sup> with the fast delay time set to 12ns.
   * The same value of random coincidence was used  for all angles because random coincidences do not have any angular correlation.
   * Hence on subtraction of the coincidence count from the universal counter, gives the true count. 
   * The error wass estimated using Poisson distribution.
###### 3.2 Fitting a curve to the obtained data:
   * A random coincidence count N<sub>random</sub> =745 was obtained for a count duration of 400s at 180<sup>◦</sup> with the fast delay time set to 12ns.
   * The same value of random coincidence was used  for all angles because random coincidences do not have any angular correlation.
   * Hence on subtraction of the coincidence count from the universal counter, gives the true count. 
   * The error wass estimated using Poisson distribution.
