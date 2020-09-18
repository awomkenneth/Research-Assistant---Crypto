# Research-Assistant---Crypto

Bitcoin stock-to-flow model

In 2008, Satoshi Nakamoto published the bitcoin white paper, creating the bitcoin genesis block, and later on releasing the bitcoin code. A popular journey that leads to a $70bn bitcoin (BTC) market today.

Bitcoin has unforgeable costliness because it costs a lot of electricity to produce new bitcoins. Producing bitcoins cannot be easily faked which is different for fiat money. 

Gold and bitcoin are different from consumable commodities like copper, zinc, nickel, brass because they have high Stock to Flow ratio.
For gold, a price spike that causes a doubling of annual production will be insignificant, increasing stockpiles by 3% rather than 1.5%.
It is this consistently low rate of supply of gold that is the fundamental reason it has maintained its monetary role throughout human history.
The high stock-to-flow ratio of gold makes it the commodity with the lowest price elasticity of supply.
The existing stockpiles of Bitcoin in 2017 were around 25 times larger than the new coins produced in 2017. This is still less than half of the ratio for gold, but around the year 2022, Bitcoin's stock-to-flow ratio is estimated to overtake that of gold.

The Stock-to-Flow model attempts to value BTC in a way similar to other scarce assets like gold and silver. Its basic concept is that widely produced commodities like oil, wheat and copper aren’t good stores of value because new supply is always coming online. But only small amounts of new BTC, gold and silver are regularly introduced. This theoretically makes its value more stable.

Also known as “S2F”, the model quantifies scarcity by taking the total global supply of a commodity and dividing it be annual production. A higher value means that less new supply is entering the market. That translates into more scarcity and less inflation.

Based on historical prices, the S2F model originally estimated BTC’s total value “should be” about $1 trillion. That would translate into more about $55,000 per coin — about 5 times its current value. An unnamed Dutch investor using the moniker PlanB updated the model on April 27, 2020, to include more calculations based on gold and silver. He or she then raised their price forecast more than fivefold to over $288,000.
Due to the limited historical record of cryptocurrencies like BTC, I am not able to assess the effectiveness of PlanB’s Stock to Flow model.

As an example, Pleifderer provides the following scenario:

Imagine an asset pricing model based on the assumption that there is no uncertainty about any asset's returns. … No serious person would suggest that the predictions of the model should be subjected to rigorous empirical testing before rejecting it. The model can be rejected simply on the basis that a critical assumption is contradicted by what we already know to be true.

Darrell Huff wrote in “How to Lie with Statistics“: “Many a statistic is false on its face. It gets by only because the magic of numbers brings about a suspension of common sense.”
Investors should be highly sceptical of this model even if they believe bitcoin is digital gold. The SF paper is not proper empirical analysis, but more akin to a marketing piece in which the author is trying to convince readers that bitcoin is going to be worth a lot more tomorrow.


Yara Inc is listed on the NYSE with a stock price of $40 - the company is not known to pay dividends. We need to price a call option with a strike of $45 maturing in 4 months. The continuously-compounded risk-free rate is 3%/year, the mean return on the
stock is 7%/year, and the standard deviation of the stock return is 40%/year. What is the Black-Scholes call price?


Stock Price = $40 
Stock Price in 4 months = $45

Black-Scholes Formula: C0=S0N(d1)−Xe−rTN(d2)
where

d1=ln(S0X)+(r+σ22)TσT‾‾√
d2=d1−σT‾‾√
C0  is the value of the call option at time 0.

S0: the value of the underlying stock at time 0.

N(): the cumulative standard normal density function (NORMSDIST() in Excel)

X: the exercise or strike price.

r: the risk-free interest rate (annualized).

T: the time until option expiration in years.

σ: the annualized standard deviations of log returns.

e and ln are the exponential and natural log functions respectively (EXP() and LN() in Excel).

Why is it a bad idea to use a recursion method to find the Fibonacci of a number?

There are some language interpreters/compilers that cannot simplify tail recursion to a loop, and therefore may be slow at doing this, if your implementation is naive.

But the real irony here is that, under certain circumstances, the Fibonacci series is actually best solved by recursion.

Write a function that takes in a Proth Number and uses Proth's theorem to determine if said number is prime? You can write this in any programming language but C/C++/Golang are preferred

N/A

Over all real numbers, find the minimum value of a positive real number, y such that

    y = sqrt((x+6)^2 + 25) + sqrt((x-6)^2 + 121)

Y^2 = ((x^2 + 12x + 36) + 25) + ((x^2 - 12x + 36) + 121)
Y^2 = 2x^2 + 218

