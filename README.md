# Floating Point Group : FinTech Case Study

## Overview and Origin

* Name of company: **Floating Point Group**

* When was the company incorporated? **2018**

* Who are the founders of the company? **John Peurifoy, Kevin March, and Van Phu**
![](./images/FPG_founders_960x0.jpg){ width=20% }

* How did the idea for the company (or project) come about? 
**The students-turned-cofounders, while working to create a hedge fund from their dorm rooms at MIT, learned the crypto space and recognized that it had real opportunities. After being accepted into the MIT summer accelerator program, they refined what would be the real world business problem they aimed to solve: the need for crypto trading efficiency through smart order routing (SOR) in an aggregated platform.** (add citation [here](https://venturefizz.com/stories/nyc/floating-point-group-profile))

* How is the company funded? How much funding have they received?  
**FPG is a funded by tech VCs General Catalyst and First Round Capital, other financial institutions, and Naval Ravikant, the founder and CEO of Angellist.  Their last seed funding was 2M USD.** (add citation [here](https://floating-point-group.breezy.hr/?))


## Business Activities:

* What specific financial problem is the company or project trying to solve?
**The MIT-student founders saw that cryptocurrency trading markets are in their infancy, relatively speaking, but would ultimately need to model after other types of assets that came before them.  Specifically, they recognized a liquidity problem with trading many cryptocurrencies and a demand for an aggregated, accessible platform for exchanging cryptocurrencies at stable prices.** (add citation [here](https://www.forbes.com/sites/frederickdaso/2020/04/13/floating-point-group-an-mit-crypto-fintech-startup-modernizes-digital-currency-trading/#149d6eca6740))


* Who is the company's intended customer?  Is there any information about the market size of this set of customers?
**FPG's intended customers are crypto traders, whether buying and selling these currencies directly or through a market exchange.  Their specifically targeted audience are hedge funds that struggle with a lack of effective, stable platforms for trading crypto currencies across various exchanges.  The market size of crypto currencies in relation to varius traditional or fiat currencies, like USD, fluctates and can be difficult to calculate. However, two widely traded cryptocurrencies include Bitcoin and Ethereum which have market caps at \$174,376,524,338 and \$26,560,510,055, respectively, at the time of this reserach.** (add citation [here](https://coinmarketcap.com/))
* What solution does this company offer that their competitors do not or cannot offer? (What is the unfair advantage they utilize?) **The co-founders for FPG were able to learn and develop their business model and intellectual property as both entrepreneurs and students at MIT.  After indepth research campaigns and hundreds of focused industry interviews, FPG pivoted from their initial product approach in an attempt to have a more competitive stance. Initially, the extent of their intent was providing a centralized trading platform overlay using smart order routing. However, their competition included internal development groups within hedge funds developing customized applications in order to have API drivin connectivity with various global crypto exchanges. With the goal of providing the best product in a competitive landscape, they needed differentiation. Their refined focus became "creating software facilitating the building of systems traders use to securely and effectively execute crypto trades."** (add citation [here](https://medium.com/profiles-in-entrepreneurship/how-these-founders-are-creating-the-future-of-c-562a928e59d3)) **This refocused FPG towards advanced solutions their would-be clients were previously trying to create with internal customized development work.  It makes the would-be competition into potential customers by providing a focused and developed "best solution" to their problem with inconsitent crypto trading environments.**

* Which technologies are they currently using, and how are they implementing them? (This may take a little bit of sleuthing–– you may want to search the company’s engineering blog or use sites like Stackshare to find this information.)
**FPG uses Amazon cloud solutions for their infrastructure.  AWS ECS, as a scalable containerized compute platform, is used for ingestion from webapi data streams of historical and realtime market data. S3 is used for object-based storage of ingested data. Athena provides SQL based queryies against S3 stored data in a serverless, highly scalable manner. AWS Lamda automates the compute layer to run FPGs custom event driven application code, and the Data Exchange API manages communication between systems through provider/subscriber-based interaction. This underlying AWS technology is used to collect and distribute FPGs high resolution crypto data. The linked diagram below, from an FPG blow post, illustrates the data ingestion process and related AWS technologies.**
**asdf** ![](https://miro.medium.com/max/1400/0*w8-puTDSGRan86ZG.png) (add citation [here](https://medium.com/floating-point-group/collecting-and-distributing-high-resolution-crypto-market-data-with-ecs-s3-athena-lambda-and-9f0bd5ab3452))



## Landscape:

* What domain of the financial industry is the company in? **Floating Point Group is intrenched in the cyrpto currency FinTech domain. More specifically, they impact the crypto currency asset trading platform aspects of the domain.**

* What have been the major trends and innovations of this domain over the last 5-10 years?  **The crypto currency domain as a whole has exploded into public awareness over the last 5-10 years.  This domain represents the advent and rapid growth of a new class of asset based on distributed and immutable digital transactions in a blockchain. It's continued existence is economically incentivised via consensus protocols that are maturing in increasingly sustainable ways. The evolution to include smart contracts provides transparency and eliminates time and costs related to mistrust between transacting entities. Specific to the exchange trading sub-domain of crypto currency, numerous crypto trading exchanges are available and continue to expand the centralized market places for trading these assets.**

* What are the other major companies in this domain? 
**Specific to the sub-domain related to trading of crypto currencies, the major exchanges include Binance, Bittrex, Coinbase, HitBTC, Gemini, and Poloniex. These groups represent relative high daily trading volumes and have established base of customers.**
**In the more fledgling arena of crypto currency smart order routing, companies in the space include Mainbloq, CoinRoutes, LCX, Bitsian, and Floating Point Group.**


## Results

* What has been the business impact of this company so far?

* What are some of the core metrics that companies in this domain use to measure success? How is your company performing, based on these metrics?

* How is your company performing relative to competitors in the same domain?


## Recommendations

* If you were to advise the company, what products or services would you suggest they offer? (This could be something that a competitor offers, or use your imagination!)

* Why do you think that offering this product or service would benefit the company?

* What technologies would this additional product or service utilize?

* Why are these technologies appropriate for your solution?
