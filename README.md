# PupilAnalysis (Under construction)

PupilAnalysis is a code developed in the R platform for pupil signal processing.
This code requires a database (.csv), which in our research was obtained through an eye tracking device (Tobii TX300).

This code shows how to do:  
- Loading original database;
- Filter to extract only the signal of interest;
- Function to cut and extract interval of interest;
- Missing Data Analysis;
- **Pre-processing**;
- Variance Analysis;
- Statistical significance test;
- Average curve of the pupil sign.

In addition, after pre-processing step, the [PCA and MLDA](https://github.com/IPL-FEI/SiProcess) can be used for feature extraction.

## Coming soon
- PCA and MLDA direct in R;
- Crossing rate by zero;
- Signal energy.

## Pre-processing

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

## Statistical significance test

## Average curve of the pupil sign

![Image](scr/AverageCurve.png)

## Paper that used this code:  
- [Classificação automática do desempenho humano em tarefas cognitivas por meio da mensuração do diâmetro pupilar](https://ssl4799.websiteseguro.com/swge5/PROCEEDINGS/PDF/CBA2018-0441.pdf)
- The Influence of Emotional Characteristic Stimuli on Human Pupillary Behavior (Coming soon)
- Eye-tracking data analysis during cognitive task (Coming soon)
