<p class="lede">The <a href="https://bitcoin.org/en/">Bitcoin</a> community has long viewed the online payment system as a decentralized digital currency. Yet there remains some debate as to whether Bitcoin is “money”, or just a “payment protocol”, a distinction that has certain legal rammifications. Moreover, some <abbr>VC</abbr>s, including <a href="http://www.avc.com/">Fred Wilson</a> and <a href="http://joel.mn/">Joel Monegro</a> of <a href="http://www.usv.com/">Union Square Ventures</a>, believe that the underlying blockchain protocol that powers Bitcoin may be its most significant contribution to the future of internet applications. More recently, the <a href="http://www.technologyreview.com/">MIT Technology Review</a> published an <a href="http://www.technologyreview.com/news/537246/why-bitcoin-could-be-much-more-than-a-currency/">article</a> detailing the uses of the blockchain outside of pure Bitcoin transactions. Like the partners at Union Square Ventures, I see the blockchain as a potentially more interesting technology than the Bitcoin “payment protocol”, for reasons that I will detail below.</p>

This post will begin with a brief [history](#history) of Bitcoin, progress to a summary of my views on Bitcoin as [money](#money), and conclude with my views on the blockchain as an [enabling protocol](#ep). 

<h2 id="history">A Brief History of Bitcoin</h2>

This history does not aim to be a comprehensive chronology of Bitcoin. Rather, it is my intention to create something of a thematic overview of Bitcoin, covering its origins, some milestones in its development, its price history in U.S. dollars, and some details of the major controversies that have dogged it. 

### Origins 

On August 18, 2008, someone registered the domain name <code>bitcoin.org</code> through [Anonymous Speech](https://www.anonymousspeech.com/), an anonymous domain registrar. This was soon followed by an interesting white paper written by the enigmatic Satoshi Nakamoto,<sup><a href="#fn01" id="fref01">1</a></sup> which set out the basic concept for the Bitcoin payment protocol. This was soon followed in November 2009 by the registration of a Bitcoin project on [SourceForge](http://sourceforge.net/projects/bitcoin/), a software source code repository and collaboration site. On January 9, 2009, Satoshi Nakamoto released version 0.1 of the [Bitcoin software](https://bitcoin.org/en/download) and mined the so-called “Genesis block”, which included the famous line, <q>The Times 03/Jan/2009 Chancellor on brink of second bailout for banks</q>.

### Milestone Transactions 

The first Bitcoin transaction occurred on January 12, 2009, when Satoshi Nakamoto sent ten bitcoins to Hal Finney, a cryptographic activist and software developer. The first known Bitcoin transaction for a physical good was made on May 22, 2010, when Laszlo Hanyecz bought—indirectly<sup><a href="#fn02" id="fref02">2</a></sup>—a pizza for 10,000 bitcoins.<sup><a href="#fn03" id="fref03">3</a></sup> 

Bitcoin derivatives began to appear in 2010, with a call option contract sold on December 9, 2010 and a put option contract sold on April 12, 2011. 

It should be noted that most transactions for goods or services involving bitcoins continue to rely upon the services of middlemen—often [Coinbase](https://www.coinbase.com) or [BitPay](https://bitpay.com)—that accept bitcoins and convert them into national currencies to pay the providers of goods or services. This reflects the fact that few providers are willing to hold bitcoins due to their price volatility relative to national currencies.<sup><a href="#fn04" id="fref04">4</a></sup>  

### Prices 

The first exchange rate between Bitcoin and the U.S. dollar was published by the [New Liberty Standard](http://newlibertystandard.wikifoundry.com) on October 5, 2009, at $0.000764 per bitcoin. On February 6, 2010, the first Bitcoin exchange, the Bitcoin Market, was established, allowing owners of bitcoins to trade their bitcoins for national currencies. After being mentioned on [Slashdot](http://slashdot.org), a newsite for science and technology, interest in bitcoins surged and the exchange rate for bitcoins increased tenfold to $0.080 per bitcoin. Since that time, the price of bitcoins has risen quite dramatically (albeit with significant fluctuations along the way). For an understanding of how rapidly bitcoin prices has appreciated, we can draw on price data from [CoinDesk](http://www.coindesk.com/): from approximately $0.0858 per bitcoin on July 18, 2010, the price of bitcoins rose to an all time high of $1124.7631 per bitcoin on November 30, 2013. The price did, of course, collapse thereafter, falling to $239.63 per bitcoin on May 10, 2015.

<figure class="picture l">
    <img alt="" class="l" id="fig01" src="http://media.lucasktlee.com/files/img/20150511-bitcoin-price-chart-l@2x.png" />
</figure>

### Exploits, Forks, and Hacks 

Bitcoin has been surprisingly free from significant vulnerabilities. Indeed, the only known major exploit of a flaw in the Bitcoin protocol occurred on August 15, 2010, when someone exploited a weakness in the code used to check transactions to create 184 billion bitcoins and send them to two addresses. This flaw was subsequently patched, and the Bitcoin blockchain updated to eliminate the transaction.

On March 12, 2013, the blockchain split in two and for six hours there were effectively two Bitcoin blockchains, with separate versions of the transaction history for bitcoins. This split was occasioned by a software upgrade to version 0.8 of the Bitcoin software, which introduced a change from the BerkeleyDB database to the more efficient LevelDB database (to reduce blockchain synchronization time). Because of a difference in the way the two databases handled locks on the database while updating the data, machines running older versions of the software rejected a block of transactions, while machines the newer version 0.8 did not, resulting in two separate blockchains. This was ultimately resolved by downgrading to the older version to maximize backward compatibility.<sup><a href="#fn05" id="fref05">5</a></sup>

While the actual Bitcoin software has been relatively free from significant exploits to date, the same cannot be said of the Bitcoin exchanges, brokers, and other platforms used to transact in bitcoins. A full list of all the hacks is beyond the scope of this brief history. I will simply note some of the more memorable ones (ordered by amount of bitcoins affected): 

* MyBitcoin, a Bitcoin payment processor, was hacked in July 2011 and 150,000 bitcoins stolen.
* Linode, a web hosting provider, was hacked in March 2012 and 46,000 bitcoins stolen. 
* Bitfloor, the fourth largest Bitcoin exchange was hacked on September 3, 2012 and 24,000 bitcoins (the majority of its available bitcoins) stolen.
* Bitcoinica, a Bitcoin exchange, was hacked on May 11, 2012 and 18,000 bitcoins stolen.
* Bitomat, the third largest Bitcoin exchange, was hacked on July 26, 2011 and 17,000 bitcoins stolen.

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

We can see from Bitcoin’s [historical price chart](#fig01) that it has experienced substantial price volatility. Moreover, by running a simple statistical analysis on the CoinDesk historical prices dataset, we can obtain a clearer understanding of the annualized daily volatility of price of bitcoins in U.S. dollars, as shown in [Table 1](#table01).

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

The significant volatility of Bitcoin prices compared with established national currencies (and equities and commodities for that matter) renders Bitcoin a poor store of value. One of the principal uses of money is to time-shift consumption, i.e. a person receives money today for work done in the past (or to be done in the future), spends some of it immediately and saves some of it to spend later. For this to work, money must retain its value across time, subject to inflation, i.e. it should exhibit relatively low price volatility. This is a function that Bitcoin in its present form performs poorly; the value of a Bitcoin (in national currencies) and thus its purchasing power may fluctuate substantially from day to day. To understand why this is the case, recall that most merchants obtain their inventory and pay their employees in some national currency. When they price their goods or services in Bitcoin, they will by necessity have to consider what price in bitcoins will be equivalent to the price they would charge in their national currency, and thus the amount that one Bitcoin will purchase will fluctuate from day to day. Moreoever, most merchants that accept bitcoins have chosen to minimize the risk of holding bitcoins by exchanging the bitcoins they receive for national currencies at the point of sale or on a very frequent basis.

Furthermore, as noted by David Yermack in his working paper for the <abbr>NBER</abbr>, there appears to be little correlation between the fluctuations in Bitcoin’s price and macroeconomic events, which makes it very difficult to use traditional risk management tools to hedge the risks of holding bitcoins.

### Difficulties with utilizing Bitcoin as a unit of account

In order to function as a unit of account, money must have a consistent value that allows one to compare the prices of goods. As an example, one would be correct in assuming that a book that costs $10 is twice as expensive as a book that costs $5. Moreover, the value of money ought to be consistent over time, such that when a customer visits a cafe for a coffee, the price stays the same from day-to-day. In the case of Bitcoin, due to the aforementioned price volatility, this is not the case. Merchants accepting bitcoins will necessarily have to recalculate their prices frequently, with the result that one cannot know in advance what one Bitcoin will buy.

The second difficulty lies in the relatively high cost of a bitcoin compared to the typical goods and services demanded by consumers on a day-to-day basis. This requires items with prices denominated in bitcoins to be quoted in more than two decimal places, e.g. 0.0010<abbr title="Bitcoin">BTC</abbr> (approximately $0.24 at the exchange rate on May 10, 2015). While there are some national currencies that have unusually high denominations, including without limitation the Indonesian rupiah, the Japanese yen, and the Korean won, it is often easier for people to deal with large denominations by simply cutting off the extra zeros than it is for people to deal with decimal places. For example, a cup of coffee in Japan may cost around 400&#165;, which amounts to approximately $3.35 as at the exchange rate on May 10, 2015. Consumers have generally taken the approach of ignoring the two zeroes at the end of the figure, which is admittedly much easier than trying to infer the approximate value of 0.0010<abbr>BTC</abbr> or compare it with another value like 0.0340<abbr>BTC</abbr>.

### Limited acceptance of Bitcoin as a medium of exchange 

For Bitcoin to serve as a medium of exchange it must be broadly accepted by merchants of goods and services and by individual consumers. Thus far, it remains to be seen whether Bitcoin will ever achieve the level of broad acceptance currently enjoyed by national currencies. At least as of 2014, while hard statistical data is hard to come by, anecdotal evidence suggests that it remains the case that a significant fraction of Bitcoin transactions involve speculation rather than transactions for goods and services.<sup><a href="#fn06" id="fref06">6</a></sup>

Even the most optimistic supporters of Bitcoin ought to acknowledge that the number of bona fide Bitcoin transactions for goods and services are at best a rounding error compared to the number of transactions for goods and services done in various national currencies, and that the majority of merchants that do accept bitcoins do not hold bitcoins for long, preferring to convert it into more readily accepted national currencies for their own transactions. This speaks volumes about the ability of Bitcoin, in its present form, to serve as a medium of exchange.

### Security of Bitcoin wallets 

Bitcoins are held in digital wallets, which have proven quite vulnerable to theft by determined cyber-criminals. The first known theft of bitcoins from a digital wallet occurred on June 13, 2011. This was followed by other notable thefts from digital wallets.<sup><a href="#fn07" id="fref07">7</a></sup> Moreover, digital wallets have also proven vulnerable to data corruption, as was the case with Bitomat, then the third largest Bitcoin exchange, which lost its wallet (and 17,000 bitcoins) when its virtual machine on Amazon Web Services Elastic Cloud Computing was deleted on July 26, 2011.<sup><a href="#fn08" id="fref08">8</a></sup> 

Indeed, the process of [properly securing one’s Bitcoin wallet](https://bitcoin.org/en/secure-your-wallet) is rather more than most common computer users will be likely to be able to follow. I do expect, though, that new startups will emerge that will improve this process, so I do not view this as a serious long-term problem. I am more concerned about the long-term ability of defenders to protect Bitcoin wallets from determined attackers. 

In general, my view is that Bitcoin until securing Bitcoin wallets is intuitive and relatively painless for _ordinary users,_ it will remain an esoteric technology used mostly by technologically savvy users.

### Incentives to continue computing the blockchain 

Verification of Bitcoin transactions depends upon miners to verify transactions. Thus far, miners are incentivized to verify Bitcoin transactions because they have the ability to earn an amount of bitcoins for being the first miner to successfully solve a computational puzzle derived from recent Bitcoin transactions and add the solved block to the blockchain. The reward for successfully solving the puzzle and adding a block to the blockchain is designed to halve every 210,000 blocks, or approximately once every four years. Currently, the reward is 25 bitcoins. 

At some point, the amount of bitcoins earned from solving and adding a block to the blockchain will likely fall below the level where it is sufficient to incentivize miners to continue verifying transactions, which could be a major threat to the viability of Bitcoin as a payment protocol. It should also be noted that the difficulty level of the problems that must be solved to add a block to the blockchain is also designed to increase progressively to match the computational power being deployed by miners, which has the effect of increasing the cost of earning bitcoins to miners. 

While Bitcoin miners can also be incentivized through transaction fees, as described briefly in the original white paper by Satoshi Nakamoto, it will be necessary to determine a fee schedule that is sufficient to incentivize enough miners to continue to verify transactions even when the amount of bitcoins distributed to miners for successfully solving the block is below their breakeven value. This transition to transaction fees may well be several years or even a decade in the future, but it _is_ a pressing problem that needs to be addressed when considering Bitcoin’s long-term potential. 

This is one area that could do with more rigorous academic and quantitative research: what level of transaction fees would be sufficient to incentivize people to expend computational resources to verify transactions once the incentive of new bitcoins is no longer present. Alternatively, one might consider whether an update to the Bitcoin core software might increase the 21 million bitcoin limit to continue to incentivize miners to verify transactions.

<h2 id="ep">The Blockchain as an Enabling Protocol</h2> 

While Bitcoin may not displace national currencies any time in the future, it is the blockchain protocol that underlies Bitcoin that is fascinating to me as an enabling protocol for future applications, similar to how our modern internet is built upon the <abbr title="Transmission Control Protocol">TCP</abbr>/<abbr title="Internet Protocol">IP</abbr>. It can be seen as the fundamental building block for a new generation of applications that require information to be stored in a—largely<sup><a href="#fn09" id="fref09">9</a></sup>—unchangeable database that is not controlled by any single entity.

My interest in the blockchain as a building block for future applications is by no means unique; a good number of <abbr>VC</abbr>s and entrepreneurs have expressed similar views, including: 

* **Joel Monegro (<abbr>VC</abbr> at Union Square Ventures):** [<cite>The Blockchain Application Stack</cite>](http://joel.mn/post/103546215249/the-blockchain-application-stack), [<cite>The Shared Data Layer of the Blockchain Application Stack</cite>](http://joel.mn/post/104755282493/the-shared-data-layer-of-the-blockchain), and [<cite>How Bitcoin is like <abbr>SMTP</abbr></cite>](http://joel.mn/post/117060535583/how-bitcoin-is-like-smtp)
* **Adam Ludwin (founder of [Chain](https://chain.com)):** [<cite>Wall Street, Meet Block Chain — Investing 2.0</cite>](https://medium.com/@adamludwin/wall-street-meet-block-chain-b2747909eb90) 
* **Marc Andreessen (<abbr>VC</abbr> at [Andreessen Horowitz](http://a16z.com/)):** [Some Thoughts on the State of Bitcoin, Blockchain, Cryptocurrencies for the Start of 2015](http://a16z.com/2015/01/05/pmarca-tweetstorm-bitcoin-2015/) and [Why Bitcoin Matters](http://dealbook.nytimes.com/2014/01/21/why-bitcoin-matters/?_r=0) 
* **Balaji Srinivasan (co-founder of [21.co](https://21.co/)):** [Bitcoin and blockchain](http://a16z.com/2015/01/22/bitcoin-and-blockchain/)
* **Boris Wertz (<abbr>VC</abbr> at [versionone](http://versionone.vc/)):** [Bitcoin: its future as a platform and protocol](http://versionone.vc/bitcoin-observations-thoughts/)

To understand why I think the blockchain is interesting as an enabling protocol, it is necessary to first identify with some precision what the blockchain means.<sup><a href="#fn10" id="fref10">10</a></sup> Second, we need to construct an understanding of what applications might arise—directly or indirectly—from the use of the blockchain. Finally, we need to understand some of the current applications that have been built with Bitcoin and the blockchain. 

### What is the “blockchain”? 

The blockchain is the beating heart of Bitcoin. It is the tamper-proof “ledger” that records each and every transaction that any given Bitcoin in circulation has been involved in since it was created. That’s all very well, but how does it actually work in practice?

First, let us begin with a simplified “thought experiment” that shows how a digital currency might work, and that shows why Bitcoin is called a “cryptocurrency”. Assume that two people, Jennifer and Mary want to transfer a digital “coin” in exchange for something of value, say, a pair of gorgeous Louboutin shoes. This digital coin is essentially a series of digital bits that represents a unique signature that says that this coin is currently owned by Jennifer. To signify ownership of the coin, Jennifer will use a form of public-key cryptography to sign the coin.<sup><a href="#fn11" id="fref11">11</a></sup> Mary can verify that the signature was created by Jennifer’s private key by using Jennifer’s corresponding public key.<sup><a href="#fn12" id="fref12">12</a></sup> (By way of background, the “coin” is simply a chain of digital signatures signifying ownership, no more, and no less, and each “coin” is unique because the chain of signatures will be unique. This is essentially how Bitcoin works: each bitcoin is a chain of unique digital signatures from the persons that have owned the bitcoin.)

So, Mary can see that Jennifer owns the coin, but there is one problem that she will still face. She has no way, at this stage, of verifying that Jennifer has not already transferred ownership of this coin to someone else, say, Karen, for a new Apple MacBook. There are two ways that Mary can verify that Jennifer has not already spent the coin: 

* Check with a trusted authority that has knowledge of transactions made with the coin
* Check with a decentralized, tamper-proof public ledger of transactions that has knowledge of transactions made with the coin

The trusted authority is one fairly elegant solution, provided that the authority is trustworthy and not prone to corruption. Human nature being what it is, this is not necessarily always true. The other solution, a decentralized tamper-proof public ledger of transactions, is the _blockchain,_ the ingeneous idea that makes Bitcoin possible. 

We will now look at how the blockchain works, using once again our trio of characters, Jennifer, Mary, and Karen, and the Louboutin shoes. When we left our trio, Mary and Karen knew that Jennifer currently owns the coin, but they have no way of determining whether Jennifer has already used the coin for a transaction with the other person or a third party. 

Instead of having one trusted third party authority, e.g. a central bank or intermediary like [PayPal](https://paypal.com/), the blockchain relies upon each participant—typically a miner with significant computational and storage resources—having a complete record of all Bitcoin transactions to date.<sup><a href="#fn13" id="fref13">13</a></sup> We will call each complete record of all the transactions in our thought experiment a “blockchain”. So, before accepting Jennifer’s coin, Mary will check her copy of the blockchain (or, in practice, a trusted server with a complete copy of the blockchain) to determine whether Jennifer has already spent that coin and no longer owns it.  

### What can you build with the blockchain?



### What has been built with the blockchain to date?



<div class="footnotes">
    <hr class="w-50" />
    <ol>
        <li id="fn01">This is not the place to speculate on the identity of Satoshi Nakamoto. Enough ink has already been spilled—physically and virtually—on this topic. Suffice it to say, I do believe, based on the evidence so far presented, that Satoshi Nakamoto is either a very talented individual or a team of highly talented individuals working in concert. <a href="#fref01">&#8593;</a></li>
        <li id="fn02">Laszlo paid a person in the United Kingdom the bitcoins, and that person in turn made an order for two pizzas from Papa John’s. <a href="#fref02">&#8593;</a></li>
        <li id="fn03">At current exchange rates (as of May 11, 2015), that amounts to $2.41 million. I certainly hope the pizzas were tasty. <a href="#fref03">&#8593;</a></li>
        <li id="fn04">See, for example, <cite><a href="http://time.com/money/3658361/dell-microsoft-expedia-bitcoin/">No, Big Companies Aren’t Really Accepting Bitcoin</a></cite> by Jacob Davidson. <a href="#fref04">&#8593;</a></li>
        <li id="fn05">For a more detailed analysis of what happened, see <cite><a href="https://bitcoinmagazine.com/3668/bitcoin-network-shaken-by-blockchain-fork/">Bitcoin Network Shaken by Blockchain Fork</a></cite> by Vitalik Buterin. <a href="#fref05">&#8593;</a></li>
        <li id="fn06">Fred Ehrsam, co-founder of Coinbase, estimated in a Goldman Sachs Investment Research interview in March 2014 that 80% of the Bitcoin transactions on Coinbase were related to speculative activities. See, Goldman Sachs Investment Research, <cite>”Interview with Fred Ehrsam”, <span class="title">Top of Mind</span></cite> 21, March 11, 2014, 8. <a href="#fref06">&#8593;</a></li>
        <li id="fn07">This is not the place to list every Bitcoin theft that has occurred, but a simple Google search will reveal a fairly long list of reported thefts. <a href="#fref07">&#8593;</a></li>
        <li id="fn08">I will note that this appears to have been a case of an entrepreneur using the wrong technical solution for his exchange, i.e. an ephemeral storage solution for what should have been a permanent storage requirement. This highlights the reality that many early—and even very likely some current—Bitcoin entrepreneurs are ill prepared to build appropriate infrastructure for their Bitcoin startups. <a href="#fref08">&#8593;</a></li>
        <li id="fn09">I say “largely” because in principle a party controlling more than 50% of the total computing power of the network can exclude or modify the ordering of transactions. <a href="#fref09">&#8593;</a></li>
        <li id="fn10">A merely superficial understanding of the technologies that underpin Bitcoin and the blockchain is dangerous for any investor. Thoughtful technology investing requires a thorough understanding of the technology and the direct and indirect implications arising therefrom. <a href="#fref10">&#8593;</a></li>
        <li id="fn11">Jennifer does this by using her private key to create a unique digital signature and appending it to the coin. <a href="#fref11">&#8593;</a></li>
        <li id="fn12">If this brief example of public-key cryptography is confusing, you may find it useful to read <a href="http://en.wikipedia.org/wiki/Public-key_cryptography">this Wikipedia entry</a>. <a href="#fref12">&#8593;</a></li>
        <li id="fn13">The current size of the blockchain is approximately 34<abbr>GB</abbr>, with so far a fairly <a href="https://blockchain.info/charts/blocks-size">linear growth pattern</a>. This may change, however, if Bitcoin becomes more commonly used. <a href="#fref13">&#8593;</a></li>
    </ol>
</div>