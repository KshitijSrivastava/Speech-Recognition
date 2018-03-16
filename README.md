# Speech-Recognition

Project done in the course of Digital Signal Processing ( Autumn 2017) on the topic the Gender Identification and Classification.

There are 11 data (wav files) which is being used for classification. In this few of the sample are male and few are females.

The gender is classified by taking the characteristics such as pitch, short period energy, number of zero crossing.

# Code
The Charac_features.m takes the features taking in the input data and finding the features with it.

The identification.m takes all the inputs and creates a datamat variable which has all the features of all the dataset.

Manually thereshold is set and basic classifier is made. Finally it successfully classifies any input as being male or female.
