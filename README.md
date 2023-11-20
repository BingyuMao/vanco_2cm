# PKRNN-2CM

This code repository provides the code to run the PKRNN-2CM, an autoregressive recurrent neural network (RNN) model containing a two-compartment (2CM) pharmacokinetic (PK) model as the prediction head for vancomycin dynamic prediction using time-series electronic health record (EHR) data.

## Overview

The PKRNN-2CM model integrates an RNN for predicting PK parameters and a 2CM PK model for concentration calculation. This model has been developed using time series EHR data from a cohort of 5,483 patients.

<img src="PKRNN-2CM model architecture.png"/> <br>

Please refer to our paper

>**A deep-learning-based two-compartment predictive model (PKRNN-2CM) for vancomycin therapeutic drug monitoring**<br>Bingyu Mao, Ziqian Xie, Masayuki Nigo, Laila Rasmy, Degui Zhi

for more details.

## Steps to reproduce PKRNN-2CM

### Data

We won't provide the original dataset we used to develop the PKRNN-2CM model, but an example of the input data can be found here: [sample_data](https://github.com/ZhiGroup/PK-RNN/blob/main/sample_data.pkl). You may also refer to the [main branch](https://github.com/ZhiGroup/PK-RNN) for more details about the input data.
