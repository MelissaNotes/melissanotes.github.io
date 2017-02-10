<!-- TOC depthFrom:1 depthTo:6 withLinks:1 updateOnSave:1 orderedList:0 -->

- [Discussion 2016/9/27 Tuesday](#discussion-2016927-tuesday)
	- [Single Variable Max](#single-variable-max)
	- [Multivariate Calculus](#multivariate-calculus)
		- [Partical derivatives](#partical-derivatives)
		- [Lagrangian, MAX = $F(x_1,x_2) +  \lambda G(x_1,x_2)$](#lagrangian-max-fx1x2-lambda-gx1x2)

<!-- /TOC -->

# Discussion 2016/9/27 Tuesday
- Office : 2nd floor of bunch.

## Single Variable Max
---
* First Order      

$$\displaystyle \frac {d}{dx} A* x^b = A*b*x^{b-1} $$

$$\displaystyle  \frac {d}{dx} f(g(x)) = f'(g(x)) * g'(x) $$

$$\displaystyle Max \, of \, ln(15x) - 2x^2$, when \, x \gt 0$$

$$\displaystyle derivative  \frac {1}{15x}  * 15  - 4x  = 0$$  

$$\displaystyle \Rightarrow \frac {1}{x} = 4x$$      

$$\displaystyle \Rightarrow x^* =\frac{1}{2},  (the \, critical \, point)$$

* Second Order  

$$
\displaystyle
d^2 * \frac {f(x^* )}{dx^2} =
\begin{cases}
\lt 0,  & \text{if $x^* $ is a max} \\[4ex]
\gt 0, & \text{if $x^* $ is a min}  \\
\end{cases}
$$


$$\displaystyle \frac {d}{dx}(\cfrac {1}{x} - 4x) = 0 \Leftarrow\Rightarrow \frac {d^2}{dx^2}(ln(15x) - 2x^2) \Rightarrow -x^{-2}-4$$

The answer is alway negative, therefore the critical point $x^* = \frac{1}{2}$ is a maximum point.

## Multivariate Calculus  
---

$$\displaystyle f(x_1, x_2) = (x_1)^3 + 8x_2, \, such \, that \, \displaystyle (x_1) + 2(x_2) = 10$$    

###  Partical derivatives

$$\displaystyle \frac {\partial f(x_1, x_2)}{\partial x_1} = f$$

Everything that is **not $x_1$** is taken as a **constant**.

$$\displaystyle \frac {\partial F}{\partial x_1} = 3(x_1)^2, \frac {\partial F}{\partial x_2} = 8$$  

* Second Order

$$\displaystyle \frac{\partial^2 F}{\partial x_1} * \partial x_2 , \, cross \, partial \, \frac{\partial^22 F}{\partial x_1^2} = (x_1^3)'' = (3(x_1)^2)' = 6x_1$$    

$$\displaystyle \frac{\partial^2 F}{\partial (x_2)^2} = 8' = 0$$

Therefore,
$$\displaystyle \frac{\partial^2 F}{\partial x_1} * \partial x_2 = \frac {\partial ^ 2 F}{\partial x_2} * \partial x_1$$      

* Example:     
$$\displaystyle F(x_1,x_2) = (x_1)^{\frac{1}{2}} * (x_2)^{\frac{1}{2}}$$

$$\displaystyle \frac {\partial F}{\partial x_1} = (x_2)^{\frac{1}{2}} * \frac{1}{2} * (x_1)^{-\frac{1}{2}}$$     

**To Find the Max $\displaystyle F(x_1,x_2)$, first order $\displaystyle \frac{\partial F}{\partial x_1} = \frac {\partial F}{\partial x_2} = 0$**.     

### Lagrangian, MAX = $F(x_1,x_2) +  \lambda G(x_1,x_2)$
---   
[$F(x)$ is the function we want to maximise, $G(x)$ is the conditions ]

$MAX(x_1,x_2)$ in **$F(x_1, x_2)$** $= (x_1)^3 + 8(x_2)$, such that **$G(x_1, x_2)$** $= (x_1) + 2(x_2) = 10$     

**Always take left hand side to right hand side**

$\displaystyle (x_1)^3 + 8(x_2)$, such that $G(x) = 0$

$$\displaystyle max(x_1, x_2, \lambda): \, Let \,  L = (x_1)^3 + 8(x_2) +  \lambda[(10 - (x_1) - 2(x_2)]$$

First order: **$\frac{\partial L}{\partial x_1}$** $= 3(x_1)^2 -  \lambda$, **$\displaystyle \frac{\partial L}{\partial x_2}$** $= 8 - 2\lambda$,  **$\frac{\partial L}{\partial \lambda}$** $= 10 - (x_1) - 2(x_2)$ [ Always $G(x_1, x_2)$].

To find the max, all these derivatives are zero.
