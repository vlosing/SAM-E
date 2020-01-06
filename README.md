# SAM-E
The Self-Adjusting Memory Ensemble (SAM-E) is a data stream learning algorithm, able to handle various types of concept drift. It combines the advantages of highly diverse Bagging Ensembles with the robustness of the Self-Adjusting Memory (SAM). Furthermore, it utilizes drift detection on top of the ensemble and replaces the worst-performing classifiers.

At the moment, SAM-E is integrated in this adapted [MOA](https://github.com/vlosing/moa) repository, which can be easily build using Intelli-J. It is a parallelized implementation which can be triggered by setting the parameter "number of jobs" accordingly within the MOA-ide.

The data sets used in the experiments are available [here](https://github.com/vlosing/driftDatasets).
