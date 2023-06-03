# -Federalist-Papers-Authorship-K-means_Clustering in R
Unveiling the Mystery of the Federalist Papers: Using Clustering to Determine the Authorship

This project aims to solve a historical mystery by applying clustering methods to the disputed Federalist essays, attributed to either Alexander Hamilton or James Madison. The Federalist Papers were a collection of influential essays written by Hamilton, Madison, and John Jay to advocate for the ratification of the United States Constitution. However, 11 essays remain disputed, with the authorship claimed by "Hamilton or Madison."

To tackle this problem, we will utilize a computational approach known as authorship attribution, pioneered by statisticians Mosteller and Wallace in the 1960s. The data set for this analysis, named "HW4-data-fedPapers85.csv," provides features in the form of "function words" and their occurrence percentages in each essay.

The objective is to employ the k-Means clustering algorithm to determine the authorship of the disputed essays. By analyzing the clustering results and examining the position of the disputed papers in relation to the essays attributed to Hamilton and Madison, we can draw conclusions about the true author.

The steps involved in this analysis include:

Loading the data set and identifying the relevant authors.
Preprocessing the data by removing irrelevant authors (Jay and HM) and converting the data into a matrix format suitable for clustering.
Scaling the data using the scale() function to ensure uniformity.
Applying the k-Means clustering algorithm and analyzing the resulting clusters.
Identifying the most useful attributes for clustering by examining the differences in word values between the two clusters.
Visualizing the clusters to determine the authorship of the disputed essays based on their placement within the clusters.
By analyzing the cluster results, we can determine the true author of the disputed essays. Based on the clustering outcome, it is expected that the disputed essays will be situated within the cluster associated with the authentic author. This analysis will provide evidence for the patterns learned and offer insights into the distinguishing attributes used for authorship attribution.

In conclusion, this project combines historical investigation with computational methods to solve the mystery of the disputed Federalist essays. The results obtained from clustering analysis will shed light on whether the authorship should be attributed to Hamilton or Madison, contributing to our understanding of the Federalist Papers and their authors' intentions.
