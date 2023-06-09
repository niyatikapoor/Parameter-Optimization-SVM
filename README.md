# Parameter-Optimization-SVM
## Sampling Assignment

<img width="541" alt="SVMQuestion" src="https://github.com/niyatikapoor/Parameter-Optimization-SVM/assets/72340288/17af53f6-73d7-4492-89df-817c069073ed">


**Dataset Used:** [Abalone Dataset](https://archive.ics.uci.edu/ml/machine-learning-databases/abalone/)

| Number of Instances:  | 4177 |
|-----------------------|--------|
| Number of Attributes: | 8   |

Predict the age of abalone from physical measurements
## Dataset Characteristics
Multivariate

## Subject Area
Life

## Associated Tasks
Classification

## Attribute Type
Categorical, Integer, Real


## Attribute Information:

**Input variables (based on physicochemical tests):**<br />
Given is the attribute name, attribute type, the measurement unit and a brief description.  The number of rings is the value to predict: either as a continuous value or as a classification problem.<br />


Name / Data Type / Measurement Unit / Description<br />
-----------------------------
1. Sex / nominal / -- / M, F, and I (infant)<br />
2. Length / continuous / mm / Longest shell measurement<br />
3. Diameter	/ continuous / mm / perpendicular to length<br />
4. Height / continuous / mm / with meat in shell<br />
5. Whole weight / continuous / grams / whole abalone<br />
6. Shucked weight / continuous	 / grams / weight of meat<br />
7. Viscera weight / continuous / grams / gut weight (after bleeding)<br />
8. Shell weight / continuous / grams / after being dried<br />
9. Rings / integer / -- / +1.5 gives the age in years<br />

The readme file contains attribute statistics.

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
- C : 7.112303
- Gamma : 0.053737   
The above parameter gave a maximum accuracy of 0.3142 .

### Convergence graph  : 

<img width="525" alt="Screenshot 2023-04-20 at 4 39 20 AM" src="https://user-images.githubusercontent.com/72340288/233218798-ed3b1597-7f28-4c4c-80ea-330355e469bd.png">




## Submission by :
**Name** : Niyati Kapoor
<br>
**Roll No** : 102003732


