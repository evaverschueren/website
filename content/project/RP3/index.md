---
date: "2019-09-01T00:00:00Z"
external_link: ""
summary: On the Pricing of Capped Volatility Swaps using Machine Learning Techniques
tags:
- Research
title: "Project 3"
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""
---

<dt> <font size="5"> <p style='text-align: justify;'> On the Pricing of Capped Volatility Swaps using Machine Learning Techniques </p> </font> </dt>
<br/>
<p style='text-align: justify;'> 
A volatility swap is a forward contract on an asset's annualized, realized volatility, over a fixed period of time. At expiration, the payoff of the contract is given by  </p> 
<center>
Notional x [min(CapLevel, RealizedVolatility)-VolatilityStrikePrice].
</center>
<br/>

<p style='text-align: justify;'> 
The cap level limits the risk exposure of the issuer of the contract and is most often fixed at 2.5 times the strike. </p> 

<p style='text-align: justify;'> 
Volatility swaps are directly exposed to the volatility of the underlying asset, making volatility a tradable market instrument. For this reason, the contracts are nowadays popular tools in fund-based risk management and are used for both speculative and hedging purposes. Volatility swaps are traded over-the-counter, meaning that no price is readily available on exchange. However, fund managers can call upon external pricing entities to receive the current price of a specific contract. In reality, this price is often the end product of an unknown internal procedure. Moreover, occasionally, prices from different pricing sources differ substantially. </p> 

<p style='text-align: justify;'> 
In this project, we show how we can deploy machine learning techniques to price capped volatility swaps. To this purpose, we build a unique dataset consisting of daily observed prices of traded volatility swaps over the lifetime of the contract, on individual stocks as well as stock indices. Before settlement of the contract, the unknown component within the payoff structure is the realized volatility, meaning that especially features with predictive power for this future realized volatility need to be taken into account. To this end, information from the implied moments on the underlying asset is exploited, to complement other features such as strike, (remaining) time till maturity and accrued volatility up to the valuation date. </p> 

- Research project in collaboration with<a href="https://www.assenagon.com/en/" target="_blank"> Assenagon. </a>