# WEEK 3 - 
## 3.1 Basic Notation and Dot Productsdue

#### Problem Set 3
##### Problem 3: vector x = (1,0,-1) và y=(0,1,-1) . What is the angle between these two vectors, in degrees (give a number in the range 0 to 180)?
Để tính góc giữa hai vector, ta sử dụng công thức: `cos(theta) = (x.y) / (||x/|.}|y/|)`. Trong đó, x.y là tích vô hướng của hai vector x và y, ||x|| và ||y|| lần lượt là độ dài của x và y. Áp dụng vào hai vector x = (1, 0, -1) và y = (0, 1, -1), ta có: x.y = 01 + 01 + (-1)*(-1) = 1
`||x|| = sqrt(1^2 + 0^2 + (-1)^2) = sqrt(2)` , `||y|| = sqrt(0^2 + 1^2 + (-1)^2) = sqrt(2)` .  Vậy `cos(theta) = 1 / (sqrt(2) * sqrt(2)) = 0.5`, do đó góc giữa hai vector là arccos(0.5) = 60 độ.
##### Problem 4: For each pair of vectors below, say whether or not they are orthogonal. A. (1,3,0,1) and (-1,-3,0,-1) B. (1,3,0,1) and (1,3,0,-10)
If the dot product is zero => orthogonal.
- (1,3,0,1) . (-1,-3,0,-1) = 1(-1) + 3(-3) + 0(0) + 1(-1) = -12 
- (1,3,0,1) . (1,3,0,-10) = 1(1) + 3(3) + 0(0) + 1(-10) = 0 => orthogonal
##### Problem 5:
<img width="500" alt="image" src="https://user-images.githubusercontent.com/89530538/234463215-abdc86cc-2279-464f-a48e-712ca1ec246c.png">
The magnitude of x is: /| x /| = /sqrt(1^2 + 2^2 + 3^2) = /sqrt(14). So, the unit vector in the same direction as x is: `x_unit = x / | x |`, `x_unit = (1/sqrt(14), 2/sqrt(14), 3/sqrt(14))`. Therefore, the unit vector in the same direction as x is (1/sqrt(14), 2/sqrt(14), 3/sqrt(14)).



## 3.2 Matrix Products and Linear Functionsdue
## 3.3 Square Matrices as Quadratic Functionsdue
## 3.4 The Multivariate Gaussiandue
## 3.5 Gaussian Generative Modelsdue
## 3.6 More Generative Modelingdue
