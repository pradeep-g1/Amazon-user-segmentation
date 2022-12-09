# Amazon-user-segmentation
we designed a project on how amazon segmented the users by using the K Algorithm.
here K means cluster
everyone have unique homepage in amazon.com because they uses their last/previous data to next how your homepage visible
First thing i choose k algorithm and before lets know whats this algorithm is
steps to be followed:
step 1:- we need to decide no of clusters k, for this we have a formula WCSS(defined as the sum of the square distance between each memberif cluster and its centroid)
        and plotting this we will get a graph and the following elbow method we find the optimal K(clusters).
step 2:-At random points select K the centroids(may not be from your dataset)
step 3:- Assign data point to the closest centroid.
step 4:- place the new centroid of each cluster after completing
step 5:-Reassign each data point to the new closest centroid if any reassignment took place go to step 4 otherwise go to FIN
then your model is ready 
based on this algorithm we have designed the project 
In this project we took Annual income and ratings as parameters for clustering if you want you would take more parameters for clustering..
And also this algorithm works for searching too.
