# [Linear Discriminant Analysis(LDA) ](https://en.wikipedia.org/wiki/Linear_discriminant_analysis) using python 

   
### Prerequisites

The things that you must have a decent knowledge on: 
```
    * Python
    * Linear Algebra
```

### Installation

* This project is fully based on python. So, the necessary modules needed for computaion are:
```
    * Numpy
    * Sklearm
    * Matplotlib
    * Pandas
```
* The commands needed for installing the above modules on windows platfom are:
```python

    pip install numpy
    pip install sklearn
    pip install matplotlib
    pip install pandas
```
* we can verify the installation of modules by  importing the modules. For example:
```python

    import numpy
    from sklearn.discriminant_analysis import LinearDiscriminantAnalysis
    import matplotlib.pyplot as plt
    import pandas as pd
```
### Explanation 

* We are performing the the **dimensionality reduction**  using [Linear Discriminant Analysis(LDA) ](https://en.wikipedia.org/wiki/Linear_discriminant_analysis). 
 * Here we are performing the operations on the [IRIS Dataset](https://archive.ics.uci.edu/ml/datasets/iris)
     

1. After performing the _Linear Discriminant Analysis_ on the dataset. It is reduced to two dimensions : 
     * The Explained variance Ratio of the principal components after  **_Linear Discriminant Analysis_**. Then result is shown in bargraph for **2 Pricipal Components** according to their _variance ratio's_ :

      
         ![v_r](https://user-images.githubusercontent.com/36328597/41587280-74003d4c-73cc-11e8-856a-9451d55734eb.png)
      
    Since, The initial two principal components have high variance. So, we selected the first two principal components.
      
      * The scatter plot for the **2 Pricipal Components** is :

      
         ![lda_iris](https://user-images.githubusercontent.com/36328597/41587279-73bacece-73cc-11e8-86b9-41ee1d24ce74.PNG)




   * The dimensionally reduced file is saved to [iris_after_LDA.csv](https://github.com/syamkakarla98/Linear-Discriminate-Analysis-Using-Python/blob/master/iris_after_LDA.csv).
 

   
### Classification

   * The classifier used for classification in [**K Nearest Neighbour Classifier**](https://en.wikipedia.org/wiki/K-nearest_neighbors_algorithm).
   * The **Classification Accuracy(C.A)** before **LDA** is shown below:
   
       ![ca _before_lda](https://user-images.githubusercontent.com/36328597/41587277-732277aa-73cc-11e8-9b86-a7a8ffcd319a.PNG)
       
       
   * The **Classification Accuracy(C.A)** before **LDA** is shown below:
   
       ![ca _after_lda](https://user-images.githubusercontent.com/36328597/41589718-d3c7d590-73d2-11e8-9e87-1fd197ff0e18.PNG)


   * The classification of the dataset _before_ and _after_  **Linear Discriminant Analysis(LDA)** is:
   
      | Dataset | Accuracy | Execution Time|
      | :---         |     :---:      |          ---: |
      | Before LDA   | 95.5555     | 0.004000425338    |
      | After LDA     | 97.7777       | 0.0040001869201      |
   

### Conclusion 

   * Hence performed the **Linear Discriminant Analysis(LDA)** on the iris data set.
   * since, the initial two Principal Components(PC'S) has more variance ratio. we selected two only.
   * Initially the dataset contains the dimensions **150 X 5** is drastically reduced to **150 X 3** dimensions including label.
   * The classification is improved and the execution times decreased a little bit after dimensionality reduction using Linear Discriminate Analysis(LDA).
   

## License

This project is licensed under the **MIT** License - see the [LICENSE.md](https://github.com/syamkakarla98/Linear-Discriminate-Analysis-Using-Python/blob/master/LICENSE.md)

