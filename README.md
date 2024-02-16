# Parkinsons-Disease-Detection-Using-Machine-Learning

![This is an image](https://media.springernature.com/lw685/springer-static/image/art%3A10.1007%2Fs11831-022-09710-1/MediaObjects/11831_2022_9710_Fig1_HTML.png)

## Data Set Information:

This dataset comprises a range of biomedical voice measurements from 31 individuals, among which 23 have been diagnosed with Parkinson's disease (PD). Each column represents a specific voice parameter, and each row corresponds to one of the 195 voice recordings from these individuals (identified by the "name" column). The primary objective of the dataset is to distinguish between healthy individuals and those with PD, as indicated by the "status" column, where 0 denotes healthy and 1 denotes PD.

## Attribute Information:

**Matrix column entries (attributes):**

- name: ASCII subject name and recording number
- MDVP:Fo(Hz): Average vocal fundamental frequency
- MDVP:Fhi(Hz): Maximum vocal fundamental frequency
- MDVP:Flo(Hz): Minimum vocal fundamental frequency
- MDVP:Jitter(%), MDVP:Jitter(Abs), MDVP:RAP, MDVP:PPQ, Jitter:DDP: Various measures of variation in fundamental frequency
- MDVP:Shimmer, MDVP:Shimmer(dB), Shimmer:APQ3, Shimmer:APQ5, MDVP:APQ, Shimmer:DDA: Various measures of variation in amplitude
- NHR, HNR: Two measures of the ratio of noise to tonal components in the voice
- status: Health status of the subject (1 for Parkinson's, 0 for healthy)
- RPDE, D2: Two nonlinear dynamical complexity measures
- DFA: Signal fractal scaling exponent
- spread1, spread2, PPE: Three nonlinear measures of fundamental frequency variation
