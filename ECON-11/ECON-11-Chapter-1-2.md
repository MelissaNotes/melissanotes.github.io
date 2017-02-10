<!-- TOC depthFrom:1 depthTo:6 withLinks:1 updateOnSave:1 orderedList:0 -->

- [Preface](#preface)

- [Chapter 1](#chapter-1)
	- [General features](#general-features)
	- [Theorey of value](#theorey-of-value)
	- [Microeconomics](#microeconomics)

- [Chapter 2](#chapter-2)
	- [Derivates](#derivates)
		- [first order derivatives](#first-order-derivatives)
		- [Second order derivatives](#second-order-derivatives)
	- [Function with several variable](#function-with-several-variable)
		- [Utility function](#utility-function)
		- [Partial derivatives](#partial-derivatives)
		- [Total Differential](#total-differential)
	- [Constrained Maximisation, Lagrangian](#constrained-maximisation-lagrangian)
		- [$\lambda$ - Economic interpretation](#lambda-economic-interpretation)
	- [Implicit function theorem: $g(x, y) = 0$, how $x,y$ are related](#implicit-function-theorem-gx-y-0-how-xy-are-related)
	- [The Envelope theorem](#the-envelope-theorem)
	- [Homogeneous Functions](#homogeneous-functions)
	- [Euler's Theorem](#eulers-theorem)

<!-- /TOC -->


# Preface
---
* Midterms 	10/25, 11/17 in class, 1hr 15 mins     
  - 1st midterm chapter 1-4
  - 10 Mul Choice + 2 long question
  - Scantron 882-E

* Final 		12/8 11:30-2:30
* Problems set will be graded due in one week
* HW 10%
* Exam 90%     
  * 30/30/30, when final is lower than midterm
  * 50% higher midterm, 40% final, when final is higher than midterm.      
<br/>      

# Chapter 1
## General features
* the **ceteris paribus** assumption, meaning other things stay same.     
* Optimization assumptions, maximize the profits.     
* positive - normative distinction
  * positive = real world;     
  * normative = how things shoule be like.    

## Theorey of value     
* Determine Equilibrium price,     
set quantity demanded = quantity supplied, $q_D=q_S$         

* Production possibility frontier,
  * No free luch, oppotunity cost;     
  * Oppotunity cost depends on how much each goods is produced.     
<br/>     

## Microeconomics
`Behavior of individual decision makers (consumers and firms)`
* Maximizing behaviours.     
`e.g.` stay bed/go to class, bacon/cereals,

* Price elasticity / Income effect.     
`e.g.` bus/car to school

* Price is not only the money you pay. Psychological cost (do not want to risk/ waste time).     
`e.g.` bank/parent loan/ investments (bonds, stocks)

* Marginal rate of substation. (cost of behavior), maximizing behavior.     
`e.g.` listen to the lecture/doze off, history/econ/job     
<br/>     

# Chapter 2
---
* Mathematics of Optimization.
  * Consumers attempt to maximize their welfare/utility when making decision.     
  * Firms attempt to maximizing their profit when choosing input and outputs.     

* Profits $\pi$ = total revenue - total cost     
* Total revenue = $p*q$, $p$ is the price and $q$ is the quantity.

## Derivates
###first order derivatives
$f(x) = Q, ~ Q ~ is ~ a ~ constant, ~ f'(x) = 0$     

$f(x) = Q*x, ~ f'(x) = a$     

$f(x) = a*g(x),~ f'(x) = a ~ d ~ of ~  g(x)$     

$f(x) = x^b, ~ b ~ is ~ constant, ~ f'(x) = b x^{(b-1)}$     

$f(x) = a x^b = a g(x) ~ f'(x) = a*b*x^{(b-1)}$     

$f(x) = ln(x) ~ f'(x) = \frac {1}{x}$     
> $e = ruler's~number~ \approx ~ 2.72$     
> $ln(e^{x}) = x$     
> $ln(e) =1$     
> $ln(a*b) = ln(a) + ln(b)$     
> $ln(\frac {a}{b}) = ln(a) - ln(b)$     
> $ln(b^a) = a*ln(b)$     

$f(x) = a^x ~ f'(x) = ln(a) * a^x$     

$f(x) = e^x ~ f'(x) = e^x$     

$f(x) = g(x) + h(x) ~ f'(x) = g'(x) + h'(x)$     

$f(x) = g(x) * h(x) ~ f'(x) = g'(x)h(x) + h'(x)g(x)$     

$f(x) = \frac {g(x)}{h(x)}  ~ f'(x) = \frac {[g'(x)h(x) - h'(x)g(x)]} {g^{2}(x)}$     

$f(x) = g[h(x)] ~ f'(x) = \frac {dg}{dh} * \frac {dh}{dx} ~~~ chain ~ rule$     
<br/>     

### Second order derivatives
* first order condition
max of a function with one variable, the derivative at that point is 0;
* second order condition
to make sure the critical point is the max ( second derivative is negative).
critical point is min when second derivative is positive.
* MAX: "mountain shape",  **concave**
* MIN: "smile face", **convex**     
<br/>     

**Example**:      
$\pi = f(q) = 11q - 8 - q - q^2, ~ find ~ max:$     
1. write down     
$f.o.c ~ \Rightarrow ~  f'(q) = 0$     
$f'(q) = 11 - 0 - 1 -2q = 10 - 2q$     
$~~~~~~~~~and ~ set$
$10 - 2q = 0, ~ \rightarrow ~ q* = 5$     
2. check s.o.c
$f''(q) \lt 0$     
$f''(q) = - 2 \lt 0$     
3. &there4; $f(q)$ is the maximum when $q = 5$.      
<br/>      

**Example**:     
Max of $ln(15x) - 2x^2$,

$\displaystyle derivative  \frac {1}{15x}  * 15  - 4x  = 0$  

$\displaystyle \Rightarrow \frac {1}{x} = 4x$      

$\displaystyle \Rightarrow x^* =\frac{1}{2},  (the \, critical \, point)$     
<br/>     

## Function with several variable
### Utility function
> x<sub>1</sub> = Food consumption, x<sub>2</sub> = Transportation, x<sub>3</sub> = Housing , ... , x<sub>n</sub> = leisure
> $U =f (x_1 , x_2 , x_3 , \cdots , x_n  )$     
> and real problem is to solve the max of U.
because of Budget constraint ( limited sources and unlimited wants).

> set  p<sub>1</sub> = price of x<sub>1</sub>,  p<sub>2</sub> x<sub>2</sub>,   p<sub>3</sub> x<sub>3</sub>  ... p<sub>n</sub> = Price Leisure
I = income
> $I = p_1x_1 + p_2x_2 + p_3x_3 +, \cdots, p_nx_n;$     
> $\rightarrow max ~ f(x_1, x_2, x_3, \ldots, x_n)$     
<br/>     

### Partial derivatives
* $f(x_1, x_2) = ax_1^2 + bx_1x_2 + cx_2^2$     
$f'(x_1) = \frac {\partial f}{\partial x_1} = 2ax_1 + bx_2$     
$f'(x_2) = \frac {\partial f}{\partial x_2} = bx_1 + 2cx_2$     

* $f(x_1, x_2) = e^{ax_1 +bx_2} = g(h(x_1, x_2))$     
$g(h) = e^h, ~ h(x_1, x_2) = ax_1 +bx_2$     
$f'(x_1) = (\frac{\partial f}{\partial h}) * (\frac{\partial h}{\partial x_1}) = a2^{ax_1+bx_2}$     
$f'(x_2) = (\frac{\partial f}{\partial h}) * (\frac{\partial h}{\partial x_2}) = b2^{ax_1+bx_2}$     

* $\frac{[\partial(\cfrac{\partial f}{\partial x_1})]}{\partial x_2} = f_{ij}$     
<br/>

### Total Differential
* Consider $U=f(x_1,x_2,x_3, \cdots, x_n)$, How much f changes if all variable by a small amount ($dx_1, dx_2, dx_3, \ldots, dx_n$) ?     
* Set $du = df = (\frac{\partial f}{\partial x_1}) * dx_1 + (\frac{\partial f}{\partial x_2}) * dx_2 + (\frac{\partial f}{\partial x_3}) * dx_3 + \ldots + (\frac{\partial f}{\partial x_n}) * dx_n$     

* **First order conditions**, a necessary condition for a maximum (or a minimum ) of the function $f(x_1, x_2, x_3, \ldots, x_n)$, is that $du = 0$, for any combination of small changes in the $x's(dx_1, dx_2, dx_3, \ldots, dx_n)$
the only way for this to be true is if $f_1 = f_2 = f_3 = \ldots = f_n = 0;$


## Constrained Maximisation, **Lagrangian**

* $L(x)$ is the function we want to maximise, $G(x)$ is the conditions
* $max = L(x_1, x_2) + \lambda G(x_1, x_2)$
* λ is called a **Lagrangian multiplier**, often called **Lagrangian**     
* Find the first order conditions of the new objective function L;     
`assume the answer is max/min, what the question asks for, no need to check second order derivative. `

**Example 1**:     
$c_1$ = consumption of food,
$c_2$ = consumption of other goods;     
$p_1$ = the price of $c_1$,
$p_2$ = the price of $c_2$;     
$U = f(c_1, c_2) = 2ln(c_1) + (1-\alpha)ln(c_2)$     
<br/>     

**Example 2, Find the max**     

$\alpha ln(c_1) + (1-\alpha)ln(c_2)$ under condition of $I = p_1c_1 + p_2c_2$     
therefore, $I - p_1 * c_1- p_2 * c_2 = 0$     
$L = 2ln(c_1) + (1-\alpha)ln(c_2) + \lambda(I - p_1 * c_1 + p_2 * c_2)$;     
<br/>     

$\frac{\partial L}{\partial c_1} = \frac {\alpha}{c_1} - \lambda * p_1 = 0$     

$\frac{\partial L}{\partial c_2} = \frac {1- \alpha}{c_2} - \lambda * p_2 = 0$     

$\frac{\partial L}{\partial \lambda} = I - p_1 * c_1 + p_2 * c_2 = 0$     

$\frac {2}{c_1} = \lambda * p_2$     

$\frac {1-\alpha}{c_2} = \lambda * p_2$     

$I - p_1 * c_1 + p_2 * c_2 = 0$, Divided both side $\frac {c_1}{c_2} = \frac {1-\alpha}{\alpha} * \frac {p_1}{p_2}$;     
$c_1^{ * } = \alpha \frac {I}{p_1}$     
$c_2^{ * } = (1-\alpha) \frac {I}{p_2}$     
$\lambda^{ * } = \frac {1}{I}$     
if $p_1$ increases, $\alpha \frac {I}{p_1} >0$.

<br/>     

**Example 3, Profit, Cost, and Revenue, Second Order Condition**:     
> $\displaystyle R = 6x_1 + \frac{99}{4}x_2$     

> $\displaystyle C = \frac{x_1x_2}{4} + ln(\frac{1}{x_{1}^{1/8}}) + \frac{x_2^2}{2}$     

> $\displaystyle max(x_1, x_2) = R - C$      

> $\displaystyle \max_{x_1, x_2} \left.(6x_1 + \frac{99}{4}x_2 - \frac{x_1x_2}{4} + \frac{1}{8}\ln(x_1) - \frac{x_2^2}{2})\right.$     

>  &rarr; FIRST ORDER     
>  $\displaystyle \frac{\partial \pi}{\partial x_1} = 6 - \frac{x_2}{4} + \frac{1}{8x_1} = 0$     

>  $\displaystyle \frac{\partial \pi}{\partial x_2} = \frac{99}{4} - \frac{x_1}{4} = x_2$

>  &rarr;  REPLACE $x_2$
>  \[
  \begin{align}
    \displaystyle 6 - \frac{1}{4}(\frac{99}{4} - \frac{x_1}{4}) + \frac{1}{8x_1} & = 0 \\
    \frac{1}{16x_1}(x_1^2 - 3x_1 + 2)  & = 0 \\
    x_1 & = \frac{3 \pm \sqrt{9-8}}{2}
  \end{align}
\]

>  &rarr;Find the critical points
>  $\displaystyle x_1 = 2 ~ or ~ x_1 = 1, (x_1, x_2) = (2, \frac{97}{4}) ~ or ~ (1, \frac{49}{2})$     

>  &rarr;SECOND ORDER FOR MAX
>  $\displaystyle \frac{\partial^2 F}{\partial x_1^2} \lt 0, \frac{\partial^2 F}{\partial x_2^2} \lt 0$    

>  $\displaystyle \frac{\partial^2 F}{\partial x_1^2} * \frac{\partial^2 F}{\partial x_2^2} \gt (\frac{\partial^2 F}{\partial x_1 \partial x_2})^2$     

>  $\displaystyle \frac{\partial^2 \pi}{\partial x_1^2} = -\frac{1}{8x_1^2}$      

>  $\displaystyle \frac{\partial^2 \pi}{\partial x_2^2} = -\frac{1}{}$     

>  $\displaystyle \frac{\partial^2 \pi}{\partial x_1 \partial x_2} = -\frac{1}{4}$     


>  &rarr;FOR $\displaystyle x_1 = 2, x_2 = \frac{97}{4}$
>  $\displaystyle \frac{\partial^2\pi}{\partial x_1^2} < 0$     
>  $\displaystyle \frac{1}{32} < \frac{1}{16}$     
>  This is not a MAX.     

>  &rarr; FOR $\displaystyle x_1 = 1, x_2 = \frac{49}{2}$     
>  $\displaystyle \frac{1}{8} \gt \frac{1}{16}$
>  This is the only MAX.

### $\lambda$ - Economic interpretation
meaning How much we can increase the objective function $f$ if the constraint is relaxed slightly.
* a HIGH value of $\lambda$ indicates that the utility could be increased substantially by relaxing the constraint (poor  people );
* a LOW value of $\lambda$ indicates that there  is not much to be gained by relaxing the constraint (rich people);
* $\lambda = 0$ implies that the constraint is not binding;

## Implicit function theorem: $g(x, y) = 0$, how $x,y$ are related
* total differential is $dg = 0$, how much the function changes
$$g_y dy + g_x dx = 0;$$
* we solve for $dy$ and divide by $dx$, we get the implicit derivate;
$$\rightarrow \frac{dy}{dx} = -\frac{g_x}{g_y}, ~ when ~ g_y ~ is ~ not ~ zero.$$
* conditions are always satisfied in this class.

## The Envelope theorem
$$ U = f(c_1, c_2, \alpha) = \alpha ln(c_1) + (1-\alpha)ln(c_2) + \lambda(I - p_1 * c_1+ p_2 * c_2);$$     

**Example of consumer problem, Envelope method**      
To find max of $\displaystyle x_1^{2/5} x_2^{3/5}$, such that  
> $\displaystyle p_1x_1 + p_2x_2 = I$  

> $\displaystyle max(x_1, x_2, \lambda):x_1^{2/5}x_2^{3/5} + \lambda(I - p_1x_1 + p_2x_2);$     

> $\displaystyle \frac{2x_2}{3x_1} = \frac{p_1}{p_2} \rightarrow x_2 = \frac{3x_1p_1}{2p_2}$       

> &rarr; Replace in constraint:
$\displaystyle x_1^* = \frac{2I}{5p_1}, x_2^* = \frac{3I}{5p_2}$  

> $\displaystyle \frac{\partial x_1^* }{\partial p_2} = 0$

> &rarr; NO CHANGE WHEN $P_2$ CHANGES

> $\displaystyle \frac{\partial x_1^* }{\partial I} = \frac{2}{5p_1} \gt 0$      

> $\displaystyle \frac{\partial x_1^* }{\partial p_1} = -\frac{2I}{5p_1^2} \lt 0$

> &rarr; The value of the function:     
> $\displaystyle V(x_1^* ,x_2^* ) = (\frac{2I}{5p_1})^{\frac{2}{5}} * (\frac{3I}{5p_2})^{\frac{3}{5}}$      

> &rarr; Change in well-being when I changes, $\displaystyle \frac{\partial V(x_1^* ,x_2^* )}{\partial I}$       
<br/>     

* The definition of envelope theorem:            
Derivative of the value of the function =     

$$\displaystyle \frac{\partial L(x_1^* ,x_2^* , \lambda)}{\partial I} = (chain ~ rule) = \frac{\partial L}{\partial I} + \frac{\partial L}{\partial x_1} * \frac{\partial x_1}{\partial I} + \frac{\partial L}{\partial x_2} * \frac{\partial x_2}{\partial I} + \frac{\partial L}{\partial \lambda} * \frac{\partial \lambda}{\partial I}$$     

Then plug in the value of $x_1^* ,x_2^* ~ and ~ \lambda$.

* a formula to compute , at the optimum , the derivative of $U$ with respect to parameter in the maximisation problem:
$\frac {dU}{d\alpha} = f_{\alpha}$     
<br/>     


## Homogeneous Functions
called Homogeneous of degree K, if
$f(tx_1,tx_2,\cdots, tx_n) = t^{k} f(x_1, x_2, \cdots, x_n)$    
<br/>     

## Euler's Theorem
Special relationship between value of function and the partial derivatives of the function.
