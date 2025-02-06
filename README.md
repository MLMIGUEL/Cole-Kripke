# The Cole-Kripke algorithm - Google colab

The code simulates realistic actigraphy data (activity counts over time) for 10 days using a combination of baseline activity patterns, random bursts, and simulated sleep periods. It then applies the Cole-Kripke algorithm to this data, which uses a weighted sum of activity counts over a rolling window to generate a sleep score. Based on this score, each minute is classified as either 'Sleep' or 'Wake'. Finally, Webster's rescoring rules are applied to refine this classification, adjusting for brief awakenings or extended periods of wakefulness. The generated data, along with sleep/wake classifications, is saved to a CSV file and visualized in a plot showing activity counts over time with shaded regions indicating periods of sleep.


References:

Cole, R. J., Kripke, D. F., Gruen, W., Mullaney, D. J., & Gillin, J. C. (1992). 
Automatic Sleep/Wake Identification From Wrist Activity. Sleep, 15(5), 461–469. http://doi.org/10.1093/sleep/15.5.461

Webster, J. B., Kripke, D. F., Messin, S., Mullaney, D. J., & Wyborney, G. (1982). 
An Activity-Based Sleep Monitor System for Ambulatory Use. Sleep, 5(4), 389–399. https://doi.org/10.1093/sleep/5.4.389

Link to the Google Colab file: https://colab.research.google.com/drive/1Wq4KpLOBBWlX8EtZh1irTZqGiP9JG1Tm?usp=sharing
