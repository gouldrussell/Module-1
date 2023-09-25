# RobinHood
## Overview and Origin

### What is the name of the company?  
RobinHood (RH)

When was the company incorporated?
RH was incorporated in April 2013, the founders are Vladimir Tenet Baiju Bhatt

How did the idea for the company (or project) come about?
The founders had previously built high-frequency trading platforms for financial institutions in NYC. The companies mission is to “provide everyone with access to financial markets, not just the wealthy”. The goal was to develop very simple user interfaces that anyone could use and develop commission free trading as well as no minimum balance.

How is the company funded? How much funding have they received?
The firm showcased its first public mobile application in December 2024. In April 2017, the company raised $110 million, followed by $363 million series D in 2018. In May 2020, RH raised an additional $280 million in venture funding at a pre-money evaluation of $8.3 billion led by Sequoia Capital. The company went public on the Nasdaq in 2021 under the stock ticker HOOD.

## Business Activities

What specific financial problem is the company or project trying to solve?
The company provides a simple user interface, commissions free trading, and no minimum balance so that the everyday retail customer can invest. They are providing direct and simple access to the market for non-professional traders).
Who is the company's intended customer? Is there any information about the market size of this set of customers?

The companies customers belong mostly to the millennial demographic and the average customer age ~26. Almost 50% of the users trade daily, and 90% use the app weekly. As of 2022, RH has ~23 million funded accounts and ~16 million month active users.
https://investors.robinhood.com/news/news-details/2023/Robinhood-Markets-Inc.-Reports-January-2023-Operating-Data/default.aspx#:~:text=Equities%20were%20%2446.0%20billion%20(up,the%20end%20of%20December%202022 Links to an external site..

What solution does this company offer that their competitors do not or cannot offer? (What is the unfair advantage they utilize?)
The company most targets millennial consumers with minimal trading experience. The ability to sign up for an account with commission free trading, no-minimal balance, and simple user interface makes this highly attractive to retail consumers. The main source of revenue comes from three main buckets including 1) interest earned on customers ‘cash balance, selling order information to high-frequency traders, and margin lending.

Which technologies are they currently using, and how are they implementing them?
RH data is critical for their business model (i.e. selling order information to high-frequency traders).
“RH data stack is hosted on AWS, and the core technology they use is ELK (Elasticsearch, Logstash, and Cabana). Logstash is responsible for collecting, parsing and transforming logs, before passing them on to Elasticsearch, while data is visualized through Kibana. RH now uses multiple ELK clusters with over 15 TBs of data. Before data goes to ELK clusters, it is buffered in Kafka, as the rates of which documents enter vary significantly between different data sources. Kafka also shields the system from failures and communicates its state with data producers and consumers.”
https://www.integrate.io/blog/how-robinhood-built-their-data-pipeline-with-amazon-redshift/ Links to an external site.

## Landscape

What domain of the financial industry is the company in?
Robinhood Financial LLC (Robinhood), a subsidiary of Robinhood Markets Inc, is a stock brokerage firm, which provides brokerage clearing services. The platform allows buying and selling of US listed companies and exchange traded funds.
https://www.globaldata.com/company-profile/robinhood-financial-llc/#:~:text=Robinhood%20Financial%20LLC%20(Robinhood)%2C,companies%20and%20exchange%20traded%20funds Links to an external site..

What have been the major trends and innovations of this domain over the last 5–10 years?
With the introduction of electronic trading, both trade volume and liquidity has dramatical increased. On the flip side, commission per share has dramatically decreased. This has caused a major shift in business model innovation. “How does a discount broker survive by providing zero commission trading?”
“Brokers earn interest income on the idle balance lying on investors account. Second is Payment for order flow, exchanges’ main source of income is from selling data feed. So, to generate more transactions and better quality data, they offer rebates to brokerage firms to attract order flow. Third is Securities Lending, in the US stocks are held by the brokers which gives them a right to lend them to people looking to short stocks or borrow for various trading strategies.”

Being a completely tech driven company, these brokers can operate with substaintially less overhead.https://pirimidtech.com/how-technology-is-transforming-the-brokerage-industry/ Links to an external site.
What are the other major companies in this domain?
RH, Webull, Charles Schwab, Fidelity Investments, E*TRADE, TD Ameritrade.

## Results
What has been the business impact of this company so far?
Overall, the impact of RH has been highly disruptive. The brokerage app gain millions of users in a very short amount of time through democratized investing and created novel channel of wealth generation for the everyday individual investor. However, the paradox is that the every individual investor is “usually” not prepared for investing into the markets.

What are some of the core metrics that companies in this domain use to measure success? How is your company performing, based on these metrics? https://investors.robinhood.com/news/news-details/2023/Robinhood-Reports-Fourth-Quarter-and-Full-Year-2022-Results/default.aspx Links to an external site.
2022 Full Year Results:

Total net revenues were $1.36 billion. Net loss was $1.03 billion, or EPS -$1.17 per share. Operating expenses were $2.37 billion. Operating expenses prior to SBC were $1.72 billion. Operating expenses prior to SBC, restructuring charges, and Q4 2022 Processing Error were $1.55 billion. Share-based compensation expense was $654 million. Adjusted EBITDA (non-GAAP) was negative $94 million.

How is your company performing relative to competitors in the same domain?
The company growing at faster pace than competition (3 yr CAGR 52% compared to market average 8.7%). However, the market cap is small compared to total market size (~1.7 trillion) but sizable for the E-market 11.78 billion (~10% market share).

https://www.globenewswire.com/news-release/2023/09/15/2744138/0/en/Securities-Brokerages-and-Stock-Exchanges-Market-Size-Growth-Worldwide-Projections-Indicate-USD-3475-Billion-and-an-8-74-CAGR-by-2030.html Links to an external site.

https://www.globenewswire.com/en/news-release/2023/07/05/2699586/0/en/E-Brokerage-Market-to-Reach-31-08-Billion-Globally-by-2032-at-10-6-CAGR-Allied-Market-Research.html Links to an external site.

## Recommendations
If you were to advise the company, what products or services would you suggest they offer? (This could be something that a competitor offers, or use your imagination!)
I would advise the company to offer more transparency around their practices (i.e. selling of data) and provide better support tools for the average retail investor. Their average customer does not have much experience (millennial) and relative low bank account balance (<$3,000). Services such as roboadvising could be one option to increase monthly subscription revenues (outside of RH gold).

Why do you think that offering this product or service would benefit the company?
I think this offering could help build more transparency and trust for RobinHood. This is critical for long term success as more regulations will continue to be developed such as GDPR (data transparency / data protection).

Ironically, the name Robinhood suggest transferring money from the wealthy to the poor, but it’s almost the opposite the way the company has developed its business model. A significant amount of money is made from selling user data to the wealthy and capitalize on customer inexperience.

What technologies would this additional product or service utilize?
Data transparency - Data transparency and protection is difficult to implement. The ability for an individual to decide on whether they want their data to be collected and sold needs to be managed by highly complex tech stacks. For example, RH could offer optional VPN technology for trading such as NordVPN.

Furthermore, individuals can decide on whether they want to delete their data even after collected.
https://hbr.org/2023/02/how-gdpr-changed-european-companies-tech-stacks Links to an external site.

Why are these technologies appropriate for your solution?
Data transparency and roboadvising will continue to be important for long term growth and trust.
