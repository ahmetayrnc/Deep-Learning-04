# Deep-Learning-04


Learning the underlying distribution of a dataset can help with performing various tasks such as detecting out of distribution data points, learning relevant features of the data, and performing classification when only very few labels are present. This assignment serves as an example of that.
For this assignment, assume we have data coming from some process according to a distribution with five modes, i.e. the data can be said to belong to five classes. While collecting data from this process, something went wrong: some of the data got corrupted and moreover, some data that doesn’t belong in the dataset accidentally got mixed up in it. Furthermore, for most of the data, we have no idea which of the five classes it belongs to. Because manually labeling data is expensive, only a small fragment of the collected dataset was la- beled, and a slightly larger segment of the collected dataset has been verified to be without anomalies.
Your goal now is now to come up with a model that can be used for three things:
1. it should be able to detect out of distribution data;
2. it should give a low (e.g. ten) dimensional description of the dataset in terms of the five modes of the distribution;
3. it should be able to classify the remaining data points into the five classes.

The assignment description can be found [here] (https://github.com/ahmetayrnc/Deep-Learning-04/blob/master/description.pdf)

The assignment report can be found here [here] (https://github.com/ahmetayrnc/Deep-Learning-04/blob/master/assignment_04_report.pdf)
