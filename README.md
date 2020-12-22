# Logistic-Regression-from-scratch

**It is a machine learning algorithm based on probability used for the classification problem**   

# Steps:

1. Data Preprocessing
2. Training  (Fitting logistic regression to the training set)
3. Testing    (Predicting the test result)
4. Visualize the result
5. Evaluation (Calculate accuracy,precision and recall)  

### Hypothesis:  

<img src="https://render.githubusercontent.com/render/math?math=h(x)=w_0%2Bw_1x_1%2Bw_2x_2">   

<img src="https://render.githubusercontent.com/render/math?math=\sigma(h(x))=\dfrac{1}{1%2B\exp(-h(x))}">

### Cost function:

<img src="https://render.githubusercontent.com/render/math?math=J(w)=\dfrac{-1}{m}\sum_{i=1}^{m}y^{(i)}log(h(x^{(i)}))%2B(1-y^{(i)})log(1-h(x^{(i)})">  

                m: no. of training examples
                
### Gradient Descent:

**Minimize J(w):**

**Repeat{**   

<img src="https://render.githubusercontent.com/render/math?math=w_j=w_j-\alpha\sum_{i=1}^{m}(h(x^{(i)})-y^{(i)})x_j^{(i)}">
 
 **}**
       
       
       
## Confusion Matrix

|    |h=1|h=0|
|:-:|:-:|:-:|
|y=1|True Positive|False Negative|
|y=0|False Positive|True Negative|  

## Accuracy: 
   **It quantifies the fraction of samples that are predicted correctly**

<img src="https://render.githubusercontent.com/render/math?math=\dfrac{h==y}{no.of samples}">


## Precision:  
   **It quantifies the fractin of predicted one's is correct**

<img src="https://render.githubusercontent.com/render/math?math=\dfrac{h=1,y=1}{h=1}">


## Recall:   
**It quantifies the fraction of actual one's is predicted correctly**

<img src="https://render.githubusercontent.com/render/math?math=\dfrac{h=1,y=1}{y=1}">


  
