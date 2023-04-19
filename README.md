# Parameter-Optimization-of-SVM
## Sampling Assignment

**Dataset Used:** [Nursery Data Set](https://archive.ics.uci.edu/ml/datasets/nursery)

| Number of Instances:  | 12960 |
|-----------------------|--------|
| Number of Attributes: | 8     |

## Attribute Information:

parents: usual, pretentious, great_pret<br>
has_nurs: proper, less_proper, improper, critical, very_crit<br>
form: complete, completed, incomplete, foster<br>
children: 1, 2, 3, more<br>
housing: convenient, less_conv, critical<br>
finance: convenient, inconv<br>
social: non-prob, slightly_prob, problematic<br>
health: recommended, priority, not_recom<br>

## Tasks Performed
1. Download the dataset
2. Pre-process the dataset
3. Create ten samples 
4. Split the samples in  70 : 30 for training and testing
5. Optimise SVM using randomisation for every sample and report best accuracy and best parameters
6. For the best sample plot the convergence graph


## Results

The best parameters of SVC for the given dataset are:
- Kernel : rbf
- C : 6.393915  
- Gamma : 0.117114    

The above parameter gave a maximum accuracy of 0.9915.

### Convergence graph  : 

![image](https://user-images.githubusercontent.com/72309401/233136025-ea315ba2-4531-4984-b527-63d9ec7e844d.png)




## Submission by :
**Name** : Nitish Kumar
<br>
**Roll No** : 102196010


