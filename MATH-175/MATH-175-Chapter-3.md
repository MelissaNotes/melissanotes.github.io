<!-- TOC depthFrom:1 depthTo:6 withLinks:1 updateOnSave:1 orderedList:0 -->

- [Chapter 3 Annuities](#chapter-3-annuities)
	- [3.1 introduction:](#31-introduction)
	- [3.2 Annuities - immediate,](#32-annuities-immediate)
	- [3.3 Annuities - due](#33-annuities-due)
	- [3.4 Perpetuity](#34-perpetuity)
	- [3.5 Deferred annuities and values on any date](#35-deferred-annuities-and-values-on-any-date)
	- [3.6 Outstanding loan balance](#36-outstanding-loan-balance)
		- [Retrospective method:](#retrospective-method)
		- [Prospective method:](#prospective-method)
	- [3.7 Non-level Annuities](#37-non-level-annuities)
	- [3.8 Annuities with payments in geometry progression * :](#38-annuities-with-payments-in-geometry-progression-)
	- [3.9 Annuities with payments in arithmetic progression + :](#39-annuities-with-payments-in-arithmetic-progression-)
		- [annuity-immediate:](#annuity-immediate)
		- [annuity-due:](#annuity-due)
	- [3.10 Yield rate](#310-yield-rate)
	- [3.11 annuity symbols for non-integral terms](#311-annuity-symbols-for-non-integral-terms)
		- [Drop payment](#drop-payment)
		- [Balloon payment](#balloon-payment)

<!-- /TOC -->

# Chapter 3 Annuities  

## 3.1 introduction:

* **Annuity** is the series of payments made at specified intervals for a fixed or continent period.     
	`e.g.` repayment of loan, or deposits to a retirement fund;     
* **Payment period** , the interval.         

## 3.2 Annuities - immediate,
`Pay at the END of each payment period, receive first payment at the end of first payment period.`     

* Basic annuity immediate lasting $n$ period, with level payment \$1.      
* The Present value of basic annuity immediate equals the sum of the present value of the $n$ end-of-period payments:     
$v(1) + v(2) + \ldots + v(n)$.  
<br/>  
  * when it is compound interest at an effective rate of $i$ per period, $v(t) = (1+i)^{-t}= v^t$     
	therefore the sum is  $v+v^2+v^3+\ldots+v^n$.     
<br/>     

* Geomatric series: $c+cr+c^2+ \ldots +cr^{n-1} = \frac{c(1-r^n)}{1-r}$.     
<br/> &rarr; the present value of the basic annuuity-immediate lasting $n$ interest periods      
<br/>
$v+v^2+v^3+\ldots+v^n=\frac{v(1-v^n)}{1-v}=\frac{1-v^n}{i}$.   
<br/>  

* Present value symbol a<sub>${\overline{n|}}i$</sub>.      
<br/>    
* Compound interest annual effective rate:     
a<sub>${\overline{n|}}i$</sub>$=v+v^2+v^3+\ldots+v^n=\frac{1-v^n}{i}$.   
<br/>   
* Final payment is S<sub>${\overline{n|}}i$</sub>, measure teh value $n$ period after.
<br/>  
* When $a(n)=(1+i)^n$, compound interest rate, S<sub>${\overline{n|}}i$</sub>$=(1+i)^n$, $a$ <sub>${\overline{n|}}i$</sub>, and  $a$ <sub>${\overline{n|}}i$</sub> $=v^n$S<sub>${\overline{n|}}i$</sub>.     
<br/>  
* In General: S<sub>${\overline{n|}}i$</sub>$=a(n)$ $a$ <sub>${\overline{n|}}$</sub>, and $a$ <sub>${\overline{n|}}$</sub> $=v(n)$ S<sub>${\overline{n|}}$</sub>.   
<br/>  
* S<sub>${\overline{n|}}i$</sub>$=\frac{(1+i)^n-1}{i}$     
<br/>  
* PMT ＝ FV／a<sub>${\overline{n|}}i$</sub>     
If future value (Loan)is to be repaid by n level end-of-period PMT, with effective interest rate for the payment period is $i$.

* PMT ＝ FV／S<sub>${\overline{n|}}i$</sub>    
If future value is to be accumulated by n level end-of-period PMT, with effective interest rate for the payment period is $i$.

* ![relation1](assets/MATH-175-Chapter-3-844d3.png)

* Calculator, calculate without BGN on the top, meadning the payment is given at the end of period. `See page p120`.     
  * I/Y, interest rate per year, nominal interest rate, as percentage;
  * P/Y, payments per year;     
  * C/Y, the number of interest conversion period per year.

## 3.3 Annuities - due     
`Pay at the BEGINNING of each payment period.`

* ${\ddot  {a}}$ <sub>${\overline{n|}}i$</sub>, represents the value at (first payment time) that lasts $n$ periods.   (present value).
* ${\ddot  {S}}$ <sub>${\overline{n|}}i$</sub>, represents the value (at the end) that lasts $n$ periods.   
* ${\ddot  {S}}$ <sub>${\overline{n|}}i$</sub> $=(1+i)^n$ ${\ddot  {a}}$ <sub>${\overline{n|}}i$</sub>,
and ${\ddot  {a}}$ <sub>${\overline{n|}}i$</sub> $=v^n$ ${\ddot  {S}}$ <sub>${\overline{n|}}i$</sub>.     
<br/>  
* In General: ${\ddot  {S}}$ <sub>${\overline{n|}}$</sub>$=a(n)$ ${\ddot  {a}}$<sub>${\overline{n|}}$</sub>, and ${\ddot  {a}}$<sub>${\overline{n|}}$</sub> $=v(n)$ ${\ddot  {S}}$ <sub>${\overline{n|}}$</sub>.   
<br/>  
* Compound interest annual effective rate:     
${\ddot  {a}}$ <sub>${\overline{n|}}i$</sub>$=v+v^2+v^3+\ldots+v^n=\frac{1-v^n}{d}$.   
<br/>      
* $v+v^2+v^3+\ldots+v^{n-1}=\frac{1(1-v^n)}{1-v}=\frac{1-v^n}{d}$.       
* ${\ddot  {S}}$ <sub>${\overline{n|}}i$</sub>$=\frac{(1+i)^n-1}{d}$     
<br/>  
`Note:`  
<br/>
* ${\ddot  {a}}$ <sub>${\overline{n|}}i$</sub> $=(1+i)$ a<sub>${\overline{n|}}i$</sub>     
<br/>
${\ddot  {S}}$ <sub>${\overline{n|}}i$</sub> $=(1+i)$ S<sub>${\overline{n|}}i$</sub>      
<br/>     

* ${\ddot  {a}}$ <sub>${\overline{n|}}i$</sub> $=$ a<sub>${\overline{n-1|}}i$</sub> $+1$     
<br/>      
${\ddot  {S}}$ <sub>${\overline{n|}}i$</sub> $=$ S<sub>${\overline{n+1|}}i$</sub> $-1$


## 3.4 Perpetuity
`annuity with an infinity term`.     
* infinite payment periods, ${\ddot  {a}}$ <sub>${\overline{∞|}}i$</sub> $=$ a<sub>${\overline{∞|}}i$</sub> $+1$     

* ${\ddot  {a}}$ <sub>${\overline{∞|}}i$</sub> $=\frac{1}{d}$     
* a<sub>${\overline{∞|}}i$</sub> $=\frac{1}{i}$     
<br/>     


## 3.5 Deferred annuities and values on any date      
* A wait of more than one payment period for a payment. retrospective method     
* times $v^n$

## 3.6 Outstanding loan balance     
how to find loan balance at an intermediate date between the loan origination date and the date of the final payment.      

### Retrospective method 回顾法:     
$L$, the amount to be paid at the end of $n$ times period.      
$i$, effective interest rate per payment,     
loan balance at time $k$ is $L(1+i)^k$.      
$OLB_k$ the loan balance at the end of k payment period(right after k payment),      
$Q$ is each payment of first $k$ period.     
&rarr;  $OLB_k=L(1+i)^k-Q$ S<sub>${\overline{n|}}i$</sub>.     
<br/>     

### Prospective method:     
$OLB_k$, the remaining value after time $k$ payment.     
$Q$, the amount of all but last payment     
$R$, last payment.     
$OLB_k=Q$ a<sub>${\overline{n-k-1|}}i$</sub> $+R(1+i)^{n-k}$.     
when all payments are equal $OLB_k=Q$ a<sub>${\overline{n-k|}}i$</sub>.          
<br/>        

## 3.7 Non-level Annuities
use CASHFLOW.     

## 3.8 Annuities with payments in geometry progression * :     
* $(1+g)$ times its predecessor, $i$, effective interest rate for the payment period. $n$, payment period.      
annuity one period before the first payment is      
<br/> $P(\frac{1- \frac{1+g}{1+i}^n }{i-g})$     
<br/>     

## 3.9 Annuities with payments in arithmetic progression + :     
At the end of $j^{th}$ interest period, $P$, the first payment, **increased** by constant amount of $Q$,     

### annuity-immediate:           
PV = $(I_{P,Q} a)$<sub>${\overline{n|}}i$</sub> $=P a$ <sub>${\overline{n|}}i$</sub> + $\frac{Q}{i}($ a <sub>${\overline{n|}}i$</sub> $-nv^n)$.     
<br/>
FV = $(I_{P,Q} S)$<sub>${\overline{n|}}i$</sub> $=P S$ <sub>${\overline{n|}}i$</sub> + $\frac{Q}{i}($ S <sub>${\overline{n|}}i$</sub> $-n)$.     

* when $P=Q=1$, PV = $(Ia)$<sub>${\overline{n|}}i$</sub>, FV = $(I S)$<sub>${\overline{n|}}i$</sub>.      
* when $P=n, Q=-1$, decreasing annuity, payment is $n, n-1, n-2, \ldots 2,1$     
<br/> $(D a)$<sub>${\overline{n|}}i$</sub> $=n$ a<sub>${\overline{n|}}i$</sub> $-\frac{1}{i}($ a<sub>${\overline{n|}}i$</sub> $-nv^n)$ =$(n-a$ <sub>${\overline{n|}}i$</sub> $)/i$     
<br/>
$(D S)$ <sub>${\overline{n|}}i$</sub>$=(D a)$ <sub>${\overline{n|}}i$</sub> $(1+i)^n$.     
<br/>     

### annuity-due:          
PV = $(I_{P,Q} {\ddot  {a}})$<sub>${\overline{n|}}i$</sub> $=P  {\ddot  {a}})$ <sub>${\overline{n|}}i$</sub> + $\frac{Q}{d}(a$ <sub>${\overline{n|}}i$</sub> $-nv^n)$.     
<br/> FV = $(I_{P,Q} {\ddot  {S}})$<sub>${\overline{n|}}i$</sub> $=P  {\ddot  {S}})$ <sub>${\overline{n|}}i$</sub> + $\frac{Q}{d}(s$ <sub>${\overline{n|}}i$</sub> $-n)$.     

* when $P=Q=1$,      
PV = $(I {\ddot  {a}})$<sub>${\overline{n|}}i$</sub>,      
<br/> FV = $(I {\ddot  {S}})$<sub>${\overline{n|}}i$</sub> $=({\ddot  {S}}$ <sub>${\overline{n|}}i$</sub>$-n)/d$;        

* when $P=n, Q=-1$, decreasing annuity, payment is $n, n-1, n-2, \ldots 2,1$     
PV = $(D {\ddot  {a}})$<sub>${\overline{n|}}i$</sub>$=(n-a$ <sub>${\overline{n|}}i$</sub> $)/i$,

`Note:`     
$(Ia)$<sub>${\overline{n|}}i$</sub> $+(D a)$<sub>${\overline{n|}}i$</sub> $=(n+1)a$<sub>${\overline{n|}}i$</sub>,     
$(I {\ddot  {a}})$<sub>${\overline{n|}}i$</sub> $+(D {\ddot  {a}})$<sub>${\overline{n|}}i$</sub> $=(n+1){\ddot  {a}}$<sub>${\overline{n|}}i$</sub>     
<br/>     

## 3.10 Yield rate     
* guess and check
* Newton's method
* TVM worksheet, use CASHFLOW.     

## 3.11 annuity symbols for non-integral terms     
1. positive real number $r$, then, we have $a$<sub>${\overline{r|}}i$</sub> $=\frac{1-v^{r}}{i}$,      
let $L$ be the total amount and $Q$ be **end-of-period payment**, with $i$ effective interest rate.     

2. then when we calculate $r*lnv =ln(1-\frac{iL}{Q})$, $r$ may be not an integer.     

3. Therefore we re-write $r=n+f$, where n is an integer and $0≤f≤1$.     

4. $L=Qa$<sub>${\overline{n|}}i$</sub> $+Q(\frac{(1+i)^f-1}{i})v^r$     

### Drop payment
* make $n$ payment of $Q$, then make the $n+1$ -th payment of $Q(\frac{(1+i)^f-1}{i})(1+i)^{1-f}$     
The last time smaller payment is drop payment.
<br/>     

### Balloon payment     
* make $n-1$ payment of $Q+Q(\frac{(1+i)^f-1}{i})v^f$.     
The last larger payment is ballon payment.
