# Clustering
# Part 1: K-Means Cluster on RFM Retail Decisions
See code for implementation.  More details shown below: </br>
RFM Retail Customer Clustering </br>
Determine the "categories" or "clusters" of popular purchases that customers will make. Ultimately will help with determining business strategy and marketing.
Results
4 clusters appears to yield the best accuracy based on kmeans.inertia_
Dataset
https://www.kaggle.com/datasets/hellbuoy/online-retail-customer-clustering/code

# Part 2: Heierchical Cluster on Avian Species
See code for implementation.  More details shown below:
This project attempts to utilize Agglomerative Heierchical Clustering to identity different bird groups based on bone structure.

Full Dataset can be found here: https://www.kaggle.com/datasets/zhangjuefei/birds-bones-and-living-habits
Dataset Description:
There are many kinds of birds: pigeons, ducks, ostriches, penguins… Some are good at flying, others can't fly but run fast. Some swim under water, others wading in shallow pool.
According to their living environments and living habits, birds are classified into different ecological groups. There are 8 ecological groups of birds:
- Swimming Birds
- Wading Birds
- Terrestrial Birds
- Raptors
- Scansorial Birds
- Singing Birds
- Cursorial Birds (not included in dataset)
- Marine Birds (not included in dataset)
First 6 groups are main and are covered by this dataset.
Apparently, birds belong to different ecological groups have different appearances: flying birds have strong wings and wading birds have long legs. Their living habits are somewhat reflected in their bones' shapes. As data scientists we may think of examining the underlying relationship between sizes of bones and ecological groups , and recognising birds' ecological groups by their bones' shapes.


There are 420 birds contained in this dataset. Each bird is represented by 10 measurements (features):
Length and Diameter of Humerus
Length and Diameter of Ulna
Length and Diameter of Femur
Length and Diameter of Tibiotarsus
Length and Diameter of Tarsometatarsus

# Part 3: EM Gaussian Mixtures Cluster on Random Data
Play Around with Expectation Maximization (EM) for a random seed of data. In this example, 2 Gaussian Functions merged together were accurate enough to fully represent the random data seed.
