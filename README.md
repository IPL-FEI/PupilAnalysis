# PupilAnalysis
### Under construction

PupilAnalysis is a code developed in the R platform for pupil signal processing.
This code requires a database (.csv), which in our research was obtained through an eye tracking device (Tobii TX300).

This code shows how to do:
- Preprocessing;
- Variance Analysis;
- Statistical significance teste;
- Average curve of the pupil sign.

In addition, after pre-processing step, the [PCA and MLDA](https://github.com/IPL-FEI/SiProcess) can be used for feature extraction.

PCA and MLDA direct in R (coming soon)

## Preprocessing
#### How it works:

In this step is done the reconstruction of the missing data intervals.

Example of missing data by blink of an eye:

![Image](scr/MissingData.png)

Step 1: Location of missing data intervals.

![Image](scr/Pre0.png)

Removal of outliers and preservation of the positions of the data.

![Image](scr/Pre1.png)

Step 2: Data interpolation.

![Image](scr/Pre2.png)

Step 3: Smoothing for remove noise.

![Image](scr/Pre3.png)

Example with 220 seconds of recording. Signal before and after pre-processing.

![Image](scr/Pre4.png)


## Variance Analysis
#### How it works:

## Statistical significance teste
#### How it works:

## Average curve of the pupil sign
#### How it works:

![Image](scr/AverageCurve.png)

