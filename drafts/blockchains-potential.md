<p class="lede">The <a href="https://bitcoin.org/en/">Bitcoin</a> community has long viewed the online payment system as a decentralized digital currency. Yet there remains some debate as to whether Bitcoin is “money”, or just a “payment protocol”, a distinction that has certain legal rammifications. Moreover, some <abbr>VC</abbr>s, including <a href="http://www.avc.com/">Fred Wilson</a> and <a href="http://joel.mn/">Joel Monegro</a> of <a href="http://www.usv.com/">Union Square Ventures</a>, believe that the underlying blockchain protocol that powers Bitcoin may be its most significant contribution to the future of internet applications. More recently, the <a href="http://www.technologyreview.com/">MIT Technology Review</a> published an <a href="http://www.technologyreview.com/news/537246/why-bitcoin-could-be-much-more-than-a-currency/">article</a> detailing the uses of the blockchain outside of pure Bitcoin transactions. Like the partners at Union Square Ventures, I see the blockchain as a potentially more interesting technology than the Bitcoin “payment protocol”, for reasons that I will detail below.</p>

This post will begin with a brief [history](#history) of Bitcoin, progress to a summary of my views on Bitcoin as [money](#money), and conclude with my views on the blockchain as an [enabling protocol](#ep). 

<h2 id="history">A Brief History of Bitcoin</h2>

This history does not aim to be a comprehensive chronology of Bitcoin. Rather, it is my intention to create something of a thematic overview of Bitcoin, covering its origins, some milestones in its development, its price history in U.S. dollars, and some details of the major controversies that have dogged it. 

### Origins 

On August 18, 2008, someone registered the domain name <code>bitcoin.org</code> through [Anonymous Speech](https://www.anonymousspeech.com/), an anonymous domain registrar. This was soon followed by an interesting white paper written by the enigmatic Satoshi Nakamoto,<sup><a href="#fn01" id="fref01">1</a></sup> which set out the basic concept for the Bitcoin payment protocol. This was soon followed in November 2009 by the registration of a Bitcoin project on [SourceForge](http://sourceforge.net/projects/bitcoin/), a software source code repository and collaboration site. On January 9, 2009, Satoshi Nakamoto released version 0.1 of the [Bitcoin software](https://bitcoin.org/en/download) and mined the so-called “Genesis block”, which included the famous line, <q>The Times 03/Jan/2009 Chancellor on brink of second bailout for banks</q>.

### Milestone Transactions 

The first Bitcoin transaction occurred on January 12, 2009, when Satoshi Nakamoto sent ten Bitcoins to Hal Finney, a cryptographic activist and software developer. The first known Bitcoin transaction for a physical good was made on May 22, 2010, when Laszlo Hanyecz bought—indirectly<sup><a href="#fn02" id="fref02">2</a></sup>—a pizza for 10,000 Bitcoins.<sup><a href="#fn03" id="fref03">3</a></sup> 

Bitcoin derivatives began to appear in 2010, with a call option contract sold on December 9, 2010 and a put option contract sold on April 12, 2011. 

It should be noted that most transactions for goods or services involving Bitcoins continue to rely upon the services of middlemen—often [Coinbase](https://www.coinbase.com) or [BitPay](https://bitpay.com)—that accept Bitcoins and convert them into national currencies to pay the providers of goods or services. This reflects the fact that few providers are willing to hold Bitcoins due to their price volatility relative to national currencies.<sup><a href="#fn04" id="fref04">4</a></sup>  

### Prices 

The first exchange rate between Bitcoin and the U.S. dollar was published by the [New Liberty Standard](http://newlibertystandard.wikifoundry.com) on October 5, 2009, at $0.000764 per Bitcoin. On February 6, 2010, the first Bitcoin exchange, the Bitcoin Market, was established, allowing owners of Bitcoins to trade their Bitcoins for national currencies. After being mentioned on [Slashdot](http://slashdot.org), a newsite for science and technology, interest in Bitcoins surged and the exchange rate for Bitcoins increased tenfold to $0.080 per Bitcoin. Since that time, the price of Bitcoins has risen quite dramatically (albeit with significant fluctuations along the way). For an understanding of how rapidly Bitcoin has appreciated, we can draw on price data from [CoinDesk](http://www.coindesk.com/): from approximately $0.0858 per Bitcoin on July 18, 2010, the price of Bitcoins rose to an all time high of $1124.7631 per Bitcoin on November 30, 2013. The price did, of course, collapse thereafter, falling to $239.63 per Bitcoin on May 10, 2015.

<figure class="picture l">
    <img alt="" class="l" id="fig01" src="http://media.lucasktlee.com/files/img/20150511-bitcoin-price-chart-l@2x.png" />
</figure>

### Exploits, Forks, and Hacks 

Bitcoin has been surprisingly free from significant vulnerabilities. Indeed, the only known major exploit of a flaw in the Bitcoin protocol occurred on August 15, 2010, when someone exploited a weakness in the code used to check transactions to create 184 billion Bitcoins and send them to two addresses. This flaw was subsequently patched, and the Bitcoin blockchain updated to eliminate the transaction.

On March 12, 2013, the blockchain split in two and for six hours there were effectively two Bitcoin blockchains, with separate versions of the transaction history for Bitcoins. This split was occasioned by a software upgrade to version 0.8 of the Bitcoin software, which introduced a change from the BerkeleyDB database to the more efficient LevelDB database (to reduce blockchain synchronization time). Because of a difference in the way the two databases handled locks on the database while updating the data, machines running older versions of the software rejected a block of transactions, while machines the newer version 0.8 did not, resulting in two separate blockchains. This was ultimately resolved by downgrading to the older version to maximize backward compatibility.<sup><a href="#fn05" id="fref05">5</a></sup>

While the actual Bitcoin software has been relatively free from significant exploits to date, the same cannot be said of the Bitcoin exchanges, brokers, and other platforms used to transact in Bitcoins. A full list of all the hacks is beyond the scope of this brief history. I will simply note some of the more memorable ones (ordered by amount of Bitcoins affected): 

* MyBitcoin, a Bitcoin payment processor, was hacked in July 2011 and 150,000 Bitcoins stolen.
* Linode, a web hosting provider, was hacked in March 2012 and 46,000 Bitcoins stolen. 
* Bitfloor, the fourth largest Bitcoin exchange was hacked on September 3, 2012 and 24,000 Bitcoins (the majority of its available Bitcoins) stolen.
* Bitcoinica, a Bitcoin exchange, was hacked on May 11, 2012 and 18,000 Bitcoins stolen.
* Bitomat, the third largest Bitcoin exchange, was hacked on July 26, 2011 and 17,000 Bitcoins stolen.

### Controversies

Bitcoin has been mired in its fair share of controversies since its inception in 2009. Most notably, it was the payment protocol of choice at the Silk Road, an illicit marketplace for drugs and other illegal goods on the Deep Web. The anonymity provided by the Bitcoin protocol has made it a potentially useful payment protocol for parties engaging in illicit activities, include transactions in narcotics, weapons, and the financing of terrorism. 

There have also been a number of highly publicized failures of Bitcoin exchanges, including the bankruptcy of the Mt. Gox Bitcoin exchange (which at its height handled some 70% of all Bitcoin transactions) in February 2014. In addition, certain persons involved in Bitcoin related companies have been charged with money laundering and other crimes, notably Charlie Shrem, who was a founding member of the Bitcoin Foundation and a co-founder of BitInstant, a now defunct Bitcoin exchange.

### More Information

For more information, you may wish to refer to the excellent [History of Bitcoin](http://historyofbitcoin.org/), which remains the most comprehensive source of information about the history of Bitcoin. 

<h2 id="money">Bitcoin as Money</h2>

First, let us look at the economic definition of “money”: an item that is generally accepted as payment for goods and services and repayments of debts. It performs three functions: a store of value, a medium of exchange, and a unit of account. Currency, which is sometimes used to describe Bitcoin, is defined as a generally accepted form of money which is issued by a government and circulated within an economy.

There remains a fair amount of disagreement over whether Bitcoin is _money_ or merely an _asset._ Notably, a December 2013 <abbr title="National Bureau of Economic Research">NBER</abbr> working paper by David Yermack at <abbr title="New York University">NYU</abbr> Stern took the view that Bitcoin is not, in its present form, currency. This view was echoed by Stephanie Lo and J. Christina Wang in a policy paper written for the Federal Reserve Bank of Boston in 2014.

The tax authorities of the United States, Australia, Singapore, and Norway have likewise taken the view that Bitcoin is an _asset_ and is taxable as such. This view has been taken by various monetary authorities, including those of Hong Kong and Finland. This view treats Bitcoin transactions for goods and services as a form of _barter._ Despite the claims that Germany and the United Kingdom have recognized Bitcoin as “private money”, it does not have the implication of government recognition of Bitcoin as money that some of its supporters have implied, since this classification relates primarily to the tax treatment accorded to Bitcoin.

In light of all of this, how do I view Bitcoin’s potential as _money?_ 

My view of Bitcoin’s potential as money has not changed much since I first started following news about Bitcoin, back at the beginning of 2014. It is an interesting proof of concept and a very fascinating decentralized peer-to-peer payment protocol. In its present form it is not, in my opinion, viable as _money,_ for the following reasons related to its performance on the three functions of _money_ as defined by economists.

### Price volatility reduces its ability to act as a stable store of value 

We can see from Bitcoin’s [historical price chart](#fig01) that it has experienced substantial price volatility. Moreover, by running a simple statistical analysis on the CoinDesk historical prices dataset, we can obtain a clearer understanding of the annualized daily volatility of price of Bitcoins in U.S. dollars, as shown in [Table 1](#table01).

<div class="responsive-wrapper">
    <table class="striped" id="table01">
        <caption><span>Table 1:</span> Annualized Daily Price Volatility of Bitcoin as of May 10, 2015</caption>
        <tr>
            <th>1-month</th>
            <th>3-month</th>
            <th>6-month</th>
            <th>12-month</th>
        </tr>
        <tr>
            <td>46.4%</td>
            <td>58.5%</td>
            <td>80.4%</td>
            <td>69.4%</td>
        </tr>
    </table>
</div>

By contrast, the annualized daily price volatility of the <abbr title="Pound Sterling">GBP</abbr>–<abbr title="United States dollar">USD</abbr> and <abbr title="Euro">EUR</abbr>–<abbr title="United States dollar">USD</abbr> in 2014 were 3.5% and 3.4% respectively. In 2014, the annualized daily price volatility of Bitcoin was 74.7%. 

The significant volatility of Bitcoin prices compared with established national currencies (and equities and commodities for that matter) renders Bitcoin a poor store of value. One of the principal uses of money is to time-shift consumption, i.e. a person receives money today for work done in the past (or to be done in the future), spends some of it immediately and saves some of it to spend later. For this to work, money must retain its value across time, subject to inflation, i.e. it should exhibit relatively low price volatility. This is a function that Bitcoin in its present form performs poorly; the value of a Bitcoin (in national currencies) and thus its purchasing power may fluctuate substantially from day to day. To understand why this is the case, recall that most merchants obtain their inventory and pay their employees in some national currency. When they price their goods or services in Bitcoin, they will by necessity have to consider what price in Bitcoins will be equivalent to the price they would charge in their national currency, and thus the amount that one Bitcoin will purchase will fluctuate from day to day. Moreoever, most merchants that accept Bitcoins have chosen to minimize the risk of holding Bitcoins by exchanging the Bitcoins they receive for national currencies at the point of sale or on a very frequent basis.

Furthermore, as noted by David Yermack in his working paper for the <abbr>NBER</abbr>, there appears to be little correlation between the fluctuations in Bitcoin’s price and macroeconomic events, which makes it very difficult to use traditional risk management tools to hedge the risks of holding Bitcoins.

### Difficulties with utilizing Bitcoin as a unit of account

In order to function as a unit of account, money must have a consistent value that allows one to compare the prices of goods. At present, this is hardly the case due to the aforementioned price volatility. The second difficulty lies in the relatively high cost of a Bitcoin compared to the typical goods and services demanded by consumers on a day-to-day basis. 

### Limited acceptance of Bitcoin as a medium of exchange 

For Bitcoin to serve as a medium of exchange it must be broadly accepted by merchants of goods and services and by individual consumers. Thus far, it remains to be seen whether Bitcoin will ever achieve the level of broad acceptance currently enjoyed by national currencies. Thus far, at least as of 2014, it remains the case that a significant fraction of Bitcoin transactions involve speculation rather than transactions for goods and services.

### Security of Bitcoin wallets 

Bitcoins are held in digital wallets, which have proven quite vulnerable to theft by determined cyber-criminals. The first known theft of Bitcoins from a digital wallet occurred on June 13, 2011. This was followed by other notable thefts from digital wallets.<sup><a href="#fn06" id="fref06">6</a></sup> Moreover, digital wallets have also proven vulnerable to data corruption, as was the case with Bitomat, then the third largest Bitcoin exchange, which lost its wallet (and 17,000 Bitcoins) when its virtual machine on Amazon Web Services Elastic Cloud Computing was deleted on July 26, 2011.<sup><a href="#fn07" id="fref07">7</a></sup> 

Indeed, the process of [properly securing one’s Bitcoin wallet](https://bitcoin.org/en/secure-your-wallet) is rather more than most common computer users will be likely to be able to follow. I do expect, though, that new startups will emerge that will be in a position to improve this process, so I do not view this as a serious long-term problem. I am more concerned about the long-term ability of defenders to protect Bitcoin wallets from determined attackers. 

<h2 id="ep">The Blockchain as an Enabling Protocol</h2> 

To me, while Bitcoin may not displace national currencies any time in the future, the blockchain protocol that underlies Bitcoin remains fascinating as an enabling protocol, similar to how our modern internet is built upon the <abbr title="Transmission Control Protocol">TCP</abbr>/<abbr title="Internet Protocol">IP</abbr>. It can be seen as the fundamental building block for a new generation of applications that require information to be stored in a—largely<sup><a href="#fn08" id="fref08">8</a></sup>—unchangeable database that is not controlled by any single entity.

These include, without limitation, the use of the blockchain for: 

* 
* 
* 

<div class="footnotes">
    <hr class="w-50" />
    <ol>
        <li id="fn01">This is not the place to speculate on the identity of Satoshi Nakamoto. Enough ink has already been spilled—physically and virtually—on this topic. Suffice it to say, I do believe, based on the evidence so far presented, that Satoshi Nakamoto is either a very talented individual or a team of highly talented individuals working in concert. <a href="#fref01">&#8593;</a></li>
        <li id="fn02">Laszlo paid a person in the United Kingdom the Bitcoins, and that person in turn made an order for two pizzas from Papa John’s. <a href="#fref02">&#8593;</a></li>
        <li id="fn03">At current exchange rates (as of May 11, 2015), that amounts to $2.41 million. I certainly hope the pizzas were tasty. <a href="#fref03">&#8593;</a></li>
        <li id="fn04">See, for example, <cite><a href="http://time.com/money/3658361/dell-microsoft-expedia-bitcoin/">No, Big Companies Aren’t Really Accepting Bitcoin</a></cite> by Jacob Davidson. <a href="#fref04">&#8593;</a></li>
        <li id="fn05">For a more detailed analysis of what happened, see <cite><a href="https://bitcoinmagazine.com/3668/bitcoin-network-shaken-by-blockchain-fork/">Bitcoin Network Shaken by Blockchain Fork</a></cite> by Vitalik Buterin. <a href="#fref05">&#8593;</a></li>
        <li id="fn06">This is not the place to list every Bitcoin theft that has occurred, but a simple Google search will reveal a fairly long list of reported thefts. <a href="#fref06">&#8593;</a></li>
        <li id="fn07">I will note that this appears to have been a case of an entrepreneur using the wrong technical solution for his exchange, i.e. an ephemeral storage solution for what should have been a permanent storage requirement. This highlights the reality that many early—and even very likely some current—Bitcoin entrepreneurs are ill prepared to build appropriate infrastructure for their Bitcoin startups. <a href="#fref07">&#8593;</a></li>
        <li id="fn08">I say “largely” because in principle a party controlling more than 50% of the total computing power used in the network can exclude or modify the ordering of transactions. <a href="#fref08">&#8593;</a></li>
    </ol>
</div>