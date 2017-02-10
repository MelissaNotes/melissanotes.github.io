<!-- TOC depthFrom:1 depthTo:6 withLinks:1 updateOnSave:1 orderedList:0 -->

- [Discussion 2016/10/4 Tuesday](#discussion-2016104-tuesday)
	- [Example of Profit, Cost, and Revenue, **Second Order Condition**](#example-of-profit-cost-and-revenue-second-order-condition)
	- [Example of consumer problem, **Envelope method**](#example-of-consumer-problem-envelope-method)

<!-- /TOC -->

# Discussion 2016/10/4 Tuesday
---

> To Solve Problem like $\displaystyle \pi = revenue - cost$

## Example of Profit, Cost, and Revenue, **Second Order Condition**
---      

$$\displaystyle R = 6x_1 + \frac{99}{4}x_2$$

$$\displaystyle C = \frac{x_1x_2}{4} + ln(\frac{1}{x_{1}^{1/8}}) + \frac{x_2^2}{2}$$  

$$\displaystyle max(x_1, x_2) = R - C$$      

$$\displaystyle \max_{x_1, x_2} \left.(6x_1 + \frac{99}{4}x_2 - \frac{x_1x_2}{4} + \frac{1}{8}\ln(x_1) - \frac{x_2^2}{2})\right.$$

FIRST ORDER

$$\displaystyle \frac{\partial \pi}{\partial x_1} = 6 - \frac{x_2}{4} + \frac{1}{8x_1} = 0$$

$$\displaystyle \frac{\partial \pi}{\partial x_2} = \frac{99}{4} - \frac{x_1}{4} = x_2$$

REPLACE $x_2$

\[
  \begin{align}
    \displaystyle 6 - \frac{1}{4}(\frac{99}{4} - \frac{x_1}{4}) + \frac{1}{8x_1} & = 0 \\
    \frac{1}{16x_1}(x_1^2 - 3x_1 + 2)  & = 0 \\
    x_1 & = \frac{3 \pm \sqrt{9-8}}{2}
  \end{align}
\]

Find the critical points

$$\displaystyle x_1 = 2 ~ or ~ x_1 = 1, (x_1, x_2) = (2, \frac{97}{4}) ~ or ~ (1, \frac{49}{2})$$

SECOND ORDER FOR MAX

$$\displaystyle \frac{\partial^2 F}{\partial x_1^2} \lt 0, \frac{\partial^2 F}{\partial x_2^2} \lt 0$$    

$$\displaystyle \frac{\partial^2 F}{\partial x_1^2} * \frac{\partial^2 F}{\partial x_2^2} \gt (\frac{\partial^2 F}{\partial x_1 \partial x_2})^2$$

$$\displaystyle \frac{\partial^2 \pi}{\partial x_1^2} = -\frac{1}{8x_1^2}$$

$$\displaystyle \frac{\partial^2 \pi}{\partial x_2^2} = -\frac{1}{}$$

$$\displaystyle \frac{\partial^2 \pi}{\partial x_1 \partial x_2} = -\frac{1}{4}$$

FOR $\displaystyle x_1 = 2, x_2 = \frac{97}{4}$

$$\displaystyle \frac{\partial^2\pi}{\partial x_1^2} < 0$$

$$\displaystyle \frac{1}{32} < \frac{1}{16}$$

This is not a MAX.

FOR $\displaystyle x_1 = 1, x_2 = \frac{49}{2}$

$$\displaystyle \frac{1}{8} \gt \frac{1}{16}$$

This is the only MAX.



## Example of consumer problem, **Envelope method**      
---

To find max of $\displaystyle x_1^{2/5} x_2^{3/5}$, such that  

$$\displaystyle p_1x_1 + p_2x_2 = I$$     

$$\displaystyle max(x_1, x_2, \lambda):x_1^{2/5}x_2^{3/5} + \lambda(I - p_1x_1 + p_2x_2);$$     

$$\displaystyle \frac{2x_2}{3x_1} = \frac{p_1}{p_2} \rightarrow x_2 = \frac{3x_1p_1}{2p_2}$$       

Replace in constraint:
$$\displaystyle x_1^* = \frac{2I}{5p_1}, x_2^* = \frac{3I}{5p_2}$$  

$$\displaystyle \frac{\partial x_1^* }{\partial p_2} = 0$$

NO CHANGE WHEN $P_2$ CHANGES

$$\displaystyle \frac{\partial x_1^* }{\partial I} = \frac{2}{5p_1} \gt 0$$      

$$\displaystyle \frac{\partial x_1^* }{\partial p_1} = -\frac{2I}{5p_1^2} \lt 0$$


The value of the function:     
$$\displaystyle V(x_1^* ,x_2^* ) = (\frac{2I}{5p_1})^{\frac{2}{5}} * (\frac{3I}{5p_2})^{\frac{3}{5}}$$      

Change in well-being when I changes, $\displaystyle \frac{\partial V(x_1^* ,x_2^* )}{\partial I}$       



**$\rightarrow$ the definition of envelope theorem:**       
Derivative of the value of the function =     

$$\displaystyle \frac{\partial L(x_1^* ,x_2^* , \lambda)}{\partial I} = (chain ~ rule) = \frac{\partial L}{\partial I} + \frac{\partial L}{\partial x_1} * \frac{\partial x_1}{\partial I} + \frac{\partial L}{\partial x_2} * \frac{\partial x_2}{\partial I} + \frac{\partial L}{\partial \lambda} * \frac{\partial \lambda}{\partial I}$$     

Then plug in the value of $x_1^* ,x_2^* ~ and ~ \lambda$.
