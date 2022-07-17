# Community-Detection-Algorithms-Performance-comparison
The implementation was done using python networkx and matplot libraries. Zachary karate club dataset is used as a benchmark dataset between the different community  detection algorithms. Karate is the well-known and much-used dataset to benchmark algorithms as  ground truth of it is two so if a detection algorithm is close to these two sets, then it is most likely to  be accurate at detection.
The data was collected from the members of a university karate club by  Wayne Zachary in 1977. Each node represents a member of the club, and each edge represents a  tie between two members of the club. The network is undirected. The network captures 34 members  of a karate club, documenting links between pairs of members who interacted outside the club.  During the study a conflict arose between the administrator "John A" and instructor "Mr. Hi", which  led to the split of the club into two. Half of the members formed a new club around Mr. Hi; members  from the other part found a new instructor or gave up karate. Based on collected data Zachary  correctly assigned all but one member of the club to the groups they joined after the split.


the implementation contains 4 methods of community detection
1- Girvan and Newman Algorithm (GN)
2-  Modularity Maximization
3-  Louvain Method for Community Detection
4- Clique Guided Community Detection

