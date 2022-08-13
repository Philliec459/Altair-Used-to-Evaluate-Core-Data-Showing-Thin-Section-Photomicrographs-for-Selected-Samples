# Altair-Used-to-Evaluate-Core-Data-Showing-Thin-Section-Photomicrographs-for-Selected-Samples
We are using python Altair to evaluate Core Data showing the Thin Section photomicrographs for our select samples.

>![Altair_TS](Mode_of_Image_Kurtosis_with_TS.gif)

Much o the data used in these Jupyter Notebook examples are from our analsis of the Thin Section images at the gray-level, scaled from 0 to 1. The gray level histograms are almost like T2 distributions. The shaley rock is at the low end of the gray-scale histogram, and the quartz grains are at the high level of the histogram. It is apparent that you can almost rock type just from the gray-level histograms alone in this formation. 

>![Altair_TS](gray-level_Kmean_Mode.png)

By the way, the thin sections used in this example do not exist in real life. They are predicted using conditional GANS pix2pix from tensorflow. Please consider this work in progress. They are good enough to demonstrate thes new features in Altair, but we have a long way to go in the creation of realistic thin section images. This will be the subject of our next repository. 

There are websites that show GAN generated people that do not exist in real life. They have 1,000's of images used in training while we have just a few thin sections. We have tried augmentation using flips, dips, jitter and mirror images, but we need more data. We have a long way to go in the creation of totally realistic looking thin section photomicrographs, but this is a start. 
