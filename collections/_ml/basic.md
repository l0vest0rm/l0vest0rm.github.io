---
title: "基础机器学习算法"
toc: true
---

## 线性回归Linear regression

### 模型
\\[ f(x) = \sum_{i=1}^{n}w_i x_{i}+w_0={w}^Tx \\]

### 代价函数
#### 正规方程
\\[J(w)=\frac{1}{m}\sum_{i=1}^{m}(y_i - f(x_i))^2=\frac{1}{m}\|y-Xw\|^2\\]

### 参数求解
#### 正规方程
\\[ w=(X^TX)^{-1}X^Ty \\]


## 逻辑回归Logistic regression

### 模型

\\[ f(x) = g(w^Tx) = \frac{1}{1+e^{-w^Tx}} \\]

\\[ g(z) = \frac{1}{1+e^{-z}} \\]
(logistic function or the sigmoid function)


### 代价函数
#### 正规方程
\\[J(w)=\frac{1}{m}\sum_{i=1}^{m}(y_i - f(x_i))^2=\frac{1}{m}\|y-Xw\|^2\\]

### 参数求解
#### 正规方程
\\[ w=(X^TX)^{-1}X^Ty \\]