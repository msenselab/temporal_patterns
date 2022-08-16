# Influences of temporal order in temporal reproduction

Cemre Baykan, Xiuna Zhu, Fredrik Allenmark, Zhuanghua Shi

General and Experimental Psychology, LMU Munich

## Abstract

Despite the outstanding role of complex temporal sequences, such as a flow of speech or a sample of music, in our everyday lives, the way we acquire or reproduce those patterns is still susceptible to many perceptual biases. Here we examined how the temporal order affects the temporal reproduction. Participants were asked to reproduce either accelerating, decelerating or random auditory sequences, consisting of the same four intervals, with finger taps. Our results showed that the mean reproduction and the precision of reproduced intervals depended on the sequential structure and their positions. The mean reproduced interval was dilated by the first interval of the sequence, with the lowest for the decelerating and the highest for the accelerating sequence. Moreover, the central tendency bias was dependent on the volatility of the sequence. The random sequence, which had higher volatility than the structured accelerating and decelerating sequences, yielded the lowest precision of the reproductions and a stronger central tendency bias. Using Bayesian integration between the ensemble mean of the sequence and individual durations and assuming the perceptual uncertainty depending on the sequential structure and position, we were able to predict the behavioral results. We conclude that the temporal order of a sequence plays a critical role in temporal pattern reproduction, with a higher weight of the first interval in the mean reproduction and the volatility of the sequence contributing to the perceptual uncertainty of individual intervals and the central tendency bias.  

## Experimental design

Participants received five beep sounds marking the four sequential intervals, followed by a 300-ms-long presentation of the fixation cross. Then, they were asked to reproduce the temporal pattern by clicking the mouse. After the reproduction, a feedback was shown to indicate the accuracy of the reproduction (see the main text in Procedure for more details). After a blank period of 1000 ms, the next trial began.

In the experiment, three temporal patterns were compared: the decelerating sequence (DS), accelerating sequence (AS) and random sequence (RS). There were four individual intervals used in each sequence. The DS condition consisted of two sets of intervals  with the same mean (700 ms) and the standard deviation (SD of 294.39 ms): [400, 500, 900, 1000] ms and [400, 600, 700, 1100] ms, whereas the AS condition had the same sets of intervals but in an inverted order. We used two sets that were randomly mixed across trials to avoid participants recognizing four fixed intervals. In the RS condition, the orders of the sample intervals were randomized, and all-four-intervals ascending or descending orders were excluded to distinguish them from the other two conditions. Thus, in all sequences, the first and second moments of the ensemble statistics were the same (M = 700 ms, SD = 294.39 ms).

## Data and analysis codes

### raw data - data.csv

This data includes all valid participants. The critical columns are:

1. Cond - temporal pattern conditions (AS, DS, RS)
2. Set  - temporal sets (mainly for the RS condition)
3. Interval ID - two sets of intervals
4. NSub - Subject No.
5. NT - the trial No.
6. Serial N - the order of intervals within each trial
7. Dur - Duration of individual interval
8. RP - reproduced duration for individual interval
9. subj_mean - reproduced mean duration
10. Err - reproduced error (in ms)
11. Rerr - relative reproduced error (normalized to 1000 ms)

### Analysis notebook - TP_modeling.ipynb

The notebook contains all results. 

### figures - main figures in the manuscript


