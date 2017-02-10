<!-- TOC depthFrom:1 depthTo:6 withLinks:1 updateOnSave:1 orderedList:0 -->

- [chapter 4, Utility maximazation and choices](#chapter-4-utility-maximazation-and-choices)
	- [The Budget Constraint:](#the-budget-constraint)
	- [First Order condition for a maximum.](#first-order-condition-for-a-maximum)
	- [Second Order condition for a maximum](#second-order-condition-for-a-maximum)
		- [Marshallian Demand Funciton](#marshallian-demand-funciton)
		- [Corner Solutions](#corner-solutions)
	- [Indirect Utility Function:](#indirect-utility-function)

<!-- /TOC -->

# chapter 4, Utility maximazation and choices
1. determind all available choices (budgest constrain),
2. then choose the one we prefer.

## The Budget Constraint:
* set $x,y$ two goods, $p_x, p_y$ are the price of two goods, income I
$p_x x+ p_y y≤I$
1. when $x=0, p_y y = I,y= \frac{I}{p_y}$, vertical intersection.
2. when $y=0, p_x x = I,x= \frac{I}{p_x}$, horizontal intersection.
3. Connect the points then we get the bundles we can choose.
* $y= -\frac{p_x}{p_y} + \frac{I}{p_y}$, slope is negative.

> $x$ = champagng, $y$ duck, $p_x = $100, p_y$ = 20/lB
> $-\frac{p_x}{p_y}$ = 100/20 = -5:      
One more champagng give up one pound of duck     

## First Order condition for a maximum.
* Outside the budget constrain, happier but cannot afford;     
* Tangent point of utility curve (consumption bundle) and indifference curve.     
the budget constrain and the tangent line have same slope.    
* slope of budget constraint $=-\frac{p_x}{p_y}$      
slope of indifference curve $\frac{dy}{dx}=-\frac{\frac{ \partial U}{ \partial X}}{\frac{ \partial U}{ \partial y}}=-MRS$     
<br/>    

**Example:**     
Max $U(x, y)$, $p_y y+p_x x=I$     
$L=U(x, y)+ \lambda(I-p_y y-p_x x)$      
$\frac{ \partial L}{ \partial x}-\frac{ \partial U}{ \partial x} = \lambda p_x = 0$     
$\frac{ \partial L}{ \partial y}-\frac{ \partial U}{ \partial y} = \lambda p_y = 0$      
$\frac{ \partial L}{ \partial \lambda } = I-p_y y-p_x x$

&rarr; $\frac {p_x}{p_y}=MRS$;     


## Second Order condition for a maximum     
* MRS is diminishing &rarr; always have maximum;
* MRS is not diminishing &rarr; check second order derivatives;     
<br/>    
* Increasing x, MRS is flatter,
how to check:     
$\frac{ \partial MRS}{ \partial x}=\frac{ \partial {\frac{MU_x}{MU_y}}}{ \partial x}<0$     
<br/>     
<br/>     


`in this class, first order is max, no need to check second order, except 2 following situations`
### Marshallian Demand Funciton
$x_1$ = Food in $p_1, x_2$ =  other goods in $p_2$,     

$U(x_1,x_2)= x_1^{0.5} + x_2^{0.5}$     

$L= x_1^{0.5} + x_2^{0.5} = \lambda (I- p_1-p_2)$     

$\frac{ \partial L}{ \partial x_1} = 0.5 x_1^{-0.5} - \lambda p_1 = 0$     

$\frac{ \partial L}{ \partial x_2} = 0.5 x_2^{-0.5} - \lambda p_2 = 0$     

$\frac{ \partial L}{ \partial \lambda } = I-p_1 x_1 - p_2 x_2$     

&rarr; $\frac{x_2}{x_1} ^{0.5} = \frac{p_1}{p_2}$
plug in and solve for $x_1$ and $x_2$     

$x_1^* = \frac{I}{p_1(1+\frac{p_1}{p_2})} = g_1(p_1, p_2, I)$     

&rarr; similar: $x_2^* = \frac{I}{p_2(1+\frac{p_2}{p_1})} = g_2(p_1, p_2, I)$     

`$g_1, g_2$ are **Marshallian Demand Funciton`    

$\frac{\partial x_2^* }{ \partial p_2} = \frac{\partial g_2(p_1, p_2, I)}{\partial p_2}<0$     

* Because of:     
$x_1^* = \frac{I}{p_1(1+\frac{p_1}{p_2})} = g_1(p_1, p_2, I)$     
$x_2^* = \frac{I}{p_2(1+\frac{p_2}{p_1})} = g_2(p_1, p_2, I)$      
&rarr;

### Corner Solutions     
Maximize utility by choosing to consume only one of the goods, where the indifference curve is not tangent to the budget constraint.      
* negative consumption - sell (not common);     

**Perfect Substitution Example**: $U(x_1, x_2) = 0.4x_1 + 0.8x_2$       
* indifference curve is flatter than the budget constraint:     
$x_1^* = \frac{I}{p_1}, x_2^* = 0$;     

* indifference curve is steeper than the budget constraint:     
$x_2^* = \frac{I}{p_2}, x_1^* = 0$;     

`find out the indifference curve is flatter or steeper`      

slope indifference curve: $\frac{dx_1}{dx_2}=-\frac{\frac{ \partial U}{ \partial x_2}}{\frac{ \partial U}{ \partial x_1}}=-2$     
$\frac{p_2}{p_1}<2, x_2^* = \frac{I}{p_2}, x_1^* = 0$     

$\frac{p_2}{p_1}>2, x_1^* = \frac{I}{p_1}, x_2^* = 0$     

$\frac{p_2}{p_1}=2$     
<br/>     

**Perfect Complements Example**: $U=min(x_1,2x_2)$     
max min $(x_1, 2x_2), p_1 x_1 + p_2 x_2 = I$     
set $x_1 = 2x_2$, and on the budget constraint.     
solve:      
$x_1 = 2x_2$     
$p_1 x_1 + p_2 x_2 = I$     

## Indirect Utility Function:
How the welfare/utility change when the price and income vary.
find the optimal consumption, replace in Utility,    
$U(x_1^* (p_1,...,p_n,	I),  x_2^* (p_1,...,p_n,	I))$
