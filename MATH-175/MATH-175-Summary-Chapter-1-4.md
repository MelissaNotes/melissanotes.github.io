# Chapter 1
A derivative is a financial instrument ,an agreement between two people) that has a value deter­mined by the price of something else.

* Uses of Derivatives
  - Risk management
  - Speculation
  - Reduced transaction costs
  - Regulatory arbitrage      
<br/>     

* Perspectives on Derivatives
  - The end-user perspective
  - The market-maker Perspective
  - The economic observer

## buying and short-selling financial assets

* buy: offer price, ask price     
Pay: price * shares + commission(transaction fee to broker)

* sell: bid price     
Receive: stock price * shares - commission

* difference between is bid-ask spread     

* long selling (lending)     
pay money buying stocks, receive money in the future by selling stocks, unknown rate of return     
  - buy low, sell high     
<br/>     

* short-selling (borrowing)     
borrow stocks from lender, and sell them, receiving money, then buy back the stock by paying money for them, and return stocks to lender.     
  - makes money when the price of the stock goes down;(sell high, buy low)
  -  borrow money     
  - offset the risk
<br/>     

# Chapter 2     
**forward contract, fixed everything**      
**call option 爱买不买, 卖股票的收期权金, 买股票的买期权**     
**put option 爱卖不卖, 买股票的收期权金, 卖股票的买期权**

## forward contracts     
1. Specifies the quantity and exact type of the assets that the seller must deliver;

2. Specifies delivery logistic(time, date, and place), transfer money from buyer to seller;     

3. Specifies the price buyer will pay at the time of delivery.

4. Obligates the seller to sell and the buyer to buy.      

`requires no initial payment or premium`     

* **Expiration date**: the time at which the contract settles.      

* **Underlying asset**: asset or com­modity on which the forward contract is based.     

* **stock index** is the average price of a group of stocks.     

* **spot price**: the market price for immediate delivery of the index.     

### the Payoff on a Forward Contract     
* Long - buyer:     
**long position** is one that makes money when the price goes up.      
Payoff to long forward = Spot price at expiration - forward price

* Short - seller:     
**short position** is one that makes money when the price goes down.     
Payoff to short forward = Forward price - spot price at expiration

* At expiration, we receive the payoff from the contract, and repay any borrowed amounts. We will call this the **net payoff/profit**.      
<br/>     
<br/>     
<br/>     
<br/>     
<br/>     
<br/>     
<br/>     

## Call Option:     
* a contract where the buyer has the right to buy, but not the obligation to buy.     

* the buyer must pay the seller an initial price, or **premium** at the time buyer and seller agree to the contract.     

* **Strike price**: The strike price, or exercise price, of a call option is what the buyer pays for the asset.   

* **Exercise**: The exercise of a call option is the act of paying the strike price to receive the asset.   

* **Expiration**: The expiration of the option is the date by which the option must either be exercised or it becomes worthless.

**European-style**: exercise could occur only at expiration.

**American-style**: buyer has the right to exercise at any time during the life of the option.     

**Bermudan-style**: the buyer can only exercise during specified periods, but not for the entire life of the option.

### Purchased call option

* Purchased call payoff  = max[0, spot price at expiration - strike price]

* Purchased call profit  = max[0, spot price at expiration - strike price] - future value of option premium     

### Written call option
seller is the **option writer**     

* Written call payoff  = - max[0, spot price at expiration - strike price]

* written call profit  = - max[0, spot price at expiration - strike price] + future value of option premium     
<br/>     
<br/>     
<br/>     
<br/>     
<br/>     
<br/>     

## Put Option     
a contract where the seller has the right to sell, but not the obligation.     

(the buyer of the put is a seller of the index)


### Purchased put option

* Purchased put payoff  = max[0, strike price - spot price at expiration]

* Purchased put profit  = max[[0, strike price - spot price at expiration] - future value of option premium     

### Written put option
**option writer** receives the premium, option seller, who buy the index.

* Written call payoff  = - max[0, spot price at expiration - strike price]

* written call profit  = - max[0, spot price at expiration - strike price] + future value of option premium       
<br/>     
<br/>     
<br/>     
<br/>     
<br/>     
<br/>     
<br/>     
<br/>            

### Summery     
#### Profit:
|   | Max Loss | Max Gain     
--- | ---| ---
long forward (buy stocks, buy contract) | - forward price | unlimited     
short forward (sell stocks, receive premium = 0) | unlimited | Forward price     
long call (choose to buy stocks, buy option) | - premium | unlimited     
short call (have to sell stock, receive premium) | unlimited | premium     
long put (choose to sell stock, buy option) | - premium | strike price - premium     
short put (have to buy, receive premium) | - strike price + premium | premium     
#### position
|long position | |  | |short position | | |       
|--- | --- | --- | --- | --- | --- | --- |    
long forward | have to buy | pay fixed price | |short forward | have to sell | receive fixed price         
purchase call | choose to buy | pay strike | | written call | have to sell if they buy| receive strike
written put | have to buy if they sell | strike | | purchased put | choose to sell | strike
