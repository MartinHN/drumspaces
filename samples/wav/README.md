#Maschine Drum sub-Dataset

- built from Native Instrument - Maschine studio drums sound
- original classes are : Open/closed HH , snare , Kick


this subset is has following property :

* uniqueness of semantic in filenames between classes
* equivalent distibution of samples per class

##Contents
* Total: 1226 samples

    * ClosedHH  : 266
    * Snare : 268
    * Kick : 426
    * OpenHH : 266

## Annotations
* 2d positions of each samples in similarity space made from t-SNE [1] from timbre-toolbox features [2]


##References 

[1] Van der Maaten, L., & Hinton, G. (2008). Visualizing data using t-SNE. Journal of Machine Learning Research, 9(2579-2605), 85.

[2] Peeters, G., Giordano, B. L., Susini, P., Misdariis, N., & McAdams, S. (2011). The timbre toolbox: Extracting audio descriptors from musical signals. The Journal of the Acoustical Society of America, 130(5), 2902-2916.


