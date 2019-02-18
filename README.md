# t-SNE


## binder
https://mybinder.org/v2/gh/sonnypark/t-SNE/master


## Data files:
  ClusterFile_os_data.txt
  ClusterFile_os_data_amutile.txt

  Both have same format.

  Each file has 28 clusters (each cluster has 50 data points with 33 dimensions). The file format is like below.

  [# of clusters] [# of total data points] [# of dimensions] [N/A]
  // 1st cluster
  [cluster ID] [# of data points] [N/A] [N/A] [N/A]
  data[clusterID][0][0] data[clusterID][0][1] ... data[clusterID][0][32]
  data[clusterID][1][0] data[clusterID][1][1] ... data[clusterID][1][32]    
  ...
  data[clusterID][49][0] data[clusterID][49][1] ... data[clusterID][49][32]    
  // 2nd cluster
  [cluster ID] [# of data points] [N/A] [N/A] [N/A]
  data[clusterID][0][0] data[clusterID][0][1] ... data[clusterID][0][32]
  data[clusterID][1][0] data[clusterID][1][1] ... data[clusterID][1][32]    
  ...
  data[clusterID][49][0] data[clusterID][49][1] ... data[clusterID][49][32]
  // and so on
