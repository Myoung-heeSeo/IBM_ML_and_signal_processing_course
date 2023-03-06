# Week1-1_What is Machine Learning?

# Linear Algebra

---

- Scalar: basically any number
    - e.g. 53
- Vector: Group a number of scalars together as a list, but each element has to have the sample type. e.g. (1, 5, 3)
- Tuple: Same format as Vector, but types can be mixed for the elements.
    - e.g. (9, 1, 2.1), (1, 5, 3)
- Matrix: Big brother of a vector. The number of rows and columns can be different, but each element has to have the same type. Matrix has n columns and m rows ⇒ m - by - n matrices.
    - e.g.
    
    ![Screen Shot 2023-03-02 at 12.03.29 AM.png](Week1-1_What%20is%20Machine%20Learning%207306d6156b3949a5b5b472d8e4a91bf7/Screen_Shot_2023-03-02_at_12.03.29_AM.png)
    

- Tensor: 0D → Scalar, 1D → Vector, 2D → Matrix
    - Handy in image processing. For example, 3D tensor can have 1d for height, 1d for width, 1d for colors, alpha channel, and focus information.

![Screen Shot 2023-03-02 at 12.04.30 AM.png](Week1-1_What%20is%20Machine%20Learning%207306d6156b3949a5b5b472d8e4a91bf7/Screen_Shot_2023-03-02_at_12.04.30_AM.png)

- Multiplication
    - Scalar Multiplication
        - e.g. 2 * 3 = 6
    - Vector Multiplication
        
        ![Screen Shot 2023-03-02 at 12.10.07 AM.png](Week1-1_What%20is%20Machine%20Learning%207306d6156b3949a5b5b472d8e4a91bf7/Screen_Shot_2023-03-02_at_12.10.07_AM.png)
        
        ![Screen Shot 2023-03-02 at 12.08.37 AM.png](Week1-1_What%20is%20Machine%20Learning%207306d6156b3949a5b5b472d8e4a91bf7/Screen_Shot_2023-03-02_at_12.08.37_AM.png)
        
    

# Supervised vs Unsupervised Machine Learning

/divi

### 1. Regression

Predict the continuous value.

![Screen Shot 2023-03-06 at 11.18.46 PM.png](Week1-1_What%20is%20Machine%20Learning%207306d6156b3949a5b5b472d8e4a91bf7/Screen_Shot_2023-03-06_at_11.18.46_PM.png)

### 2. Classification

Process of predicting a discrete (categorical) value.

![Screen Shot 2023-03-06 at 11.21.19 PM.png](Week1-1_What%20is%20Machine%20Learning%207306d6156b3949a5b5b472d8e4a91bf7/Screen_Shot_2023-03-06_at_11.21.19_PM.png)

![Screen Shot 2023-03-06 at 11.32.51 PM.png](Week1-1_What%20is%20Machine%20Learning%207306d6156b3949a5b5b472d8e4a91bf7/Screen_Shot_2023-03-06_at_11.32.51_PM.png)

label is not a continuous value, binary value or at least a discrete value. → predict a class variable zero or one, a broken yes or no instead of the number.

have only two classes → binary classification

more than two classes → multi-class classification

### 3. Clustering

Process of finding data points which belong together.

![Screen Shot 2023-03-06 at 11.32.12 PM.png](Week1-1_What%20is%20Machine%20Learning%207306d6156b3949a5b5b472d8e4a91bf7/Screen_Shot_2023-03-06_at_11.32.12_PM.png)

Data centered around the clusters without a label.

### 4. Dimension Reduction

Compress the data set into small dimension without loosing too much informations.