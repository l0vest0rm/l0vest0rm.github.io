---
title: "基础机器学习算法"
toc: true
---

## 线性回归Linear regression

### 模型
\\[ f(x) = \sum_{i=1}^{n}w_i x_{i}+w_0={w}^Tx \\]

### 损失函数
#### 最小二乘法
\\[J(w)=\frac{1}{n}\sum_{i=1}^{n}(y_i - f(x_i))^2=\frac{1}{n}\|y-Xw\|^2\\]

### 参数求解
#### 正规方程
\\[ w=(X^TX)^{-1}X^Ty \\]