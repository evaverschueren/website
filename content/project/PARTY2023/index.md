---
date: "2023-01-30T00:00:00Z"
external_link: ""
summary: On the Pricing of Capped Volatility Swaps using Machine Learning Techniques
tags:
- Talks
title: "Winter School for young researchers on actuarial risks 2023, Valencia, Spain "
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""
---

<dt> <font size="5"> On the Pricing of Capped Volatility Swaps using Machine Learning Techniques </font> </dt>
<br/>
<p style='text-align: justify;'> 
A volatility swap is an over-the-counter financial derivative of which the payoff is based upon the volatility of the underlying asset. The instrument represents a two-party contract wherein future, annualized, realized volatility, over a fixed period of time, is traded against the implied volatility at initiation, also referred to as the strike. To limit the risk exposure of the issuer of the contract, the future realized volatility is often capped at 2.5 times the strike level, leading to what is called capped volatility swaps. At expiration, the payoff of this contract is given by  </p> 
<center>
Notional x [min(CapLevel, RealizedVolatility)-VolatilityStrikePrice].
</center>
<br/>

<p style='text-align: justify;'> 
The volatility swap allows investors to get a direct and pure exposure to the volatility of the underlying asset, without being exposed to the direction of the asset itself, making one of the most common measures of risk a tradable market instrument and an asset class of its own. With the growing popularity of trading volatility, the pricing of (capped) volatility swaps has been an actively pursued research topic. Dealing with a highly non-linear payoff structure, because of the cap level on volatility and volatility itself being dependent on a square root operation, this pricing problem is challenging. The currently existing literature focuses on model-based pricing approaches, but so far, only approximations of this price, under the assumptions of the models, are found. </p> 

<p style='text-align: justify;'> 
In this presentation, we show how we can deploy model-free, data-driven machine learning techniques to price capped volatility swaps. To this purpose, we build a unique dataset consisting of daily observed prices of traded volatility swaps over the lifetime of the contract, on individual stocks as well as stock indices. Before settlement of the contract, the unknown component within the payoff structure is the capped future realized volatility, meaning that especially features with predictive power for this future realized volatility need to be taken into account. To this end, we explore distributional information on the underlying asset and more specifically information from the forward implied volatility and higher implied moments. This information complements other features such as strike, (remaining) time till maturity and accrued volatility up to the valuation date.  </p> 

- <a href="https://wp.unil.ch/party/" target="_blank"> Conference Website </a>
- {{< staticref "uploads/PARTY_EvaVerschueren.pdf" "newtab" >}}Slides{{</staticref>}}