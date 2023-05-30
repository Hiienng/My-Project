# Week 4: Linear Regression and Probability Estimation
## 4.1 An Introduction to Linear Regression

    - The regression in one dimension
    - Predictor and response variable
    - A loss function fomular
    - Deriving the optimal solution

<img width="500" alt="image" src="https://user-images.githubusercontent.com/89530538/235345048-dbf26020-229f-4d42-a899-c7a4351a8010.png">
<img width="500" alt="image" src="https://user-images.githubusercontent.com/89530538/235346033-800aa4dd-c717-480e-a29c-a5ff87eda3bd.png">
- Chứng minh phương trình minimize loss function, với x_bar và y_bar là trung bình tất cả các x và tất cả các y
<img width="500" alt="image" src="https://user-images.githubusercontent.com/89530538/235346110-6e6267dd-b8db-48ae-a246-a97611d90b96.png">
<img width="500" alt="image" src="https://user-images.githubusercontent.com/89530538/235346212-e45bc084-6d76-4b77-8bc4-281525cc70ed.png">

### Problem set:
#### Problem 1:
Consider the following simple data set of four points : (1,1) (1,3) (4,4) (4,6). 
- Suppose you had to predict y without knowledge of x. What value would you predict?
- => The four y values in the data set are 1, 3, 4, and 6. The average of these values is: (1 + 3 + 4 + 6) / 4 = 14 / 4 = 3.5
- what is the  (MSE) of your prediction, on the given four points?
- => The actual y values in the data set are 1, 3, 4, and 6. The squared differences between each actual value and the predicted value of 3.5 are:
    - (1 - 3.5)^2 = 6.25
    - (3 - 3.5)^2 = 0.25
    - (4 - 3.5)^2 = 0.25
    - (6 - 3.5)^2 = 6.25
    - => y = $sum$ / 4= 3.25
- Now let's say you want to predict y based on x. Your initial choice of prediction rule is y = x. What is the MSE of the linear function y = x on the four given points
- => MSE = $(y - (x - 1)^2) / 4$ = ( ((1-(1-1))^2 + (3 - (1 - 1))^2 + (4 - (4-1)^2) + (6 - (4-1))^2 )/ 4 = 2
- Find the best prediction rule of the form y = ax + b. That is, you want to find the parameters  such that this rule has the smallest possible mean squared error on the four training points. What are a and b?
- $y = x + 1$
<img width="500" alt="image" src="https://user-images.githubusercontent.com/89530538/235406930-0cc54e38-81ec-44fc-b3a7-d98d715d353b.png">

#### Problem 2:
<img width="500" alt="image" src="https://user-images.githubusercontent.com/89530538/235407837-14c66756-dd83-49a1-b2a9-5bbf7510b195.png">

## 4.2 Linear Regression


    - Regression with multiple predictor variables
    - Least Square Regression and solution

<img width="1332" alt="image" src="https://user-images.githubusercontent.com/89530538/235417538-0b7fa391-faae-475b-9233-28f394cce9db.png">



- Assimilate: 