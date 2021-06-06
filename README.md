# FatMaxxer

![Screenshot](https://raw.githubusercontent.com/IanPeake/FatMaxxer/main/Screenshot_20210606-151127_FatMax%20Optimiser_downscale.jpg)

Android app for the Polar H10 to advise Detrended Fluctuation Analysis alpha1 in real time.
There is preliminary research that running or cycling at DFA 0.75 corresponds to the first ventilatory threshold or FatMax.

2 minute rolling window for alpha1, evaluated every 20 seconds

Graphical display shows elapsed time, heart rate, DFA alpha1 and RMSSD

Audio output advises HR, alpha1 and artifact rejection rate.

Graph view
- green trace for alpha1 (values appear at 100x, e.g. 0.75 reads as 75, to share primary axis with HR)
- red trace for heart rate
- blue trace for RMSSD

Very rough, but it seems to approximate Marco Altini's Python code.

Produces audio output of HR, Alpha1 and dropped artifacts.
