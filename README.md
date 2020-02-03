## Gender-Voice-Determination-Male-or-Female-Based-on-Voice---Characteristics-

**Objcetive:**

With human hearing ability most of the times we correctly guess the gender of a person. If we want computer to do the same task is little challenging. In this activity we are attempting to develop a model which will guess the gender based once voice- characteristics.

**Dataset:**

This database was created to identify a voice as male or female, based upon acoustic properties of the voice and speech. The dataset consists of 3,168 recorded voice samples, collected from male and female speakers. The voice samples are pre-processed by acoustic analysis in R using the seewave and tuneR packages, with an analyzed frequency range of 0hz-280hz.
https://www.mldata.io/dataset-details/gender_voice/

**Attribute Information:**

    - duration: length of signal
    - meanfreq: mean frequency (in kHz)
    - sd: standard deviation of frequency
    - median: median frequency (in kHz)
    - Q25: first quantile (in kHz)
    - Q75: third quantile (in kHz)
    - IQR: interquantile range (in kHz)
    - skew: skewness (see note in specprop description)
    - kurt: kurtosis (see note in specprop description)
    - sp.ent: spectral entropy
    - sfm: spectral flatness
    - mode: mode frequency
    - centroid: frequency centroid (see specprop)
    - peakf: peak frequency (frequency with highest energy)
    - meanfun: average of fundamental frequency measured across acoustic signal
    - minfun: minimum fundamental frequency measured across acoustic signal
    - maxfun: maximum fundamental frequency measured across acoustic signal
    - meandom: average of dominant frequency measured across acoustic signal
    - mindom: minimum of dominant frequency measured across acoustic signal
    - maxdom: maximum of dominant frequency measured across acoustic signal
    - dfrange: range of dominant frequency measured across acoustic signal
    - modindx: modulation index. Calculated as the accumulated absolute difference between adjacent measurements of fundamental frequencies divided by the frequency range
    
    
    **Results: **
    
    ![a](https://github.com/kwankhede/Gender-Voice-Determination-Male-or-Female-Based-on-Voice---Characteristics-/blob/master/1.png)
    ![b](https://github.com/kwankhede/Gender-Voice-Determination-Male-or-Female-Based-on-Voice---Characteristics-/blob/master/2.png)
    ![c](https://github.com/kwankhede/Gender-Voice-Determination-Male-or-Female-Based-on-Voice---Characteristics-/blob/master/3.png)
    ![d](https://github.com/kwankhede/Gender-Voice-Determination-Male-or-Female-Based-on-Voice---Characteristics-/blob/master/4.png)
    
    
