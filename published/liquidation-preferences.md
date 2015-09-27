<p class="lede">Today, reflecting the fact that I am spending an inordinate amount of time at <a href="http://www.wharton.upenn.edu/">Wharton</a> thinking about venture capital and startups (due in part to what I’m studying this semester and in part due to the fact that I’ve become more active in certain entrepreneurial circles), I’ve decided to take some time to talk about liquidation preferences and how they can affect the payouts to investors, management, and/or founders. (Besides, I must note that I was having a small liquidity event of my own, involving a classic Macallan 12-year single malt scotch.)</p>

First, it is important to note that the liquidation preference is not just a tool of venture capitalists. It shows up in growth capital private equity as well. There are a number of good resources that have described the liquidation preference, including a [blog post](http://www.feld.com/archives/2005/01/term-sheet-liquidation-preference.html) by [Brad Feld](http://www.feld.com/), a [post](http://venturebeat.com/2010/08/16/beware-the-trappings-of-liquidation-preference/) on [Venture Beat](http://venturebeat.com/), and a [blog post](http://startuplawyer.com/preferred-stock/what-is-a-liquidation-preference) by Ryan Roberts at [Startup Lawyer](http://startuplawyer.com/). I will therefore not go into excessive detail about the mechanics of the liquidation preference. 

It suffices to note that liquidation preferences in growth <abbr title="private equity">PE</abbr> and <abbr title="venture capital">VC</abbr> ensure that when a “liquidation” event occurs, the liquidation proceeds will first be applied to repay the investors the amount paid on their investment in the preferred shares before any liquidation proceeds are distributed to management and/or founders, who will typically hold common shares. This is the “preference”. It can be a simple return of the amount paid on the investment (a 1.0x liquidation preference) or it can be a “super” liquidation preference, which returns a multiple of the amount paid on the investment (e.g. a 2.0x or 3.0x liquidation preference). For obvious reasons, most investors will prefer a “super” liquidation preference, while founders will want a simple liquidation preference. 

Just as a quick by the way, a “liquidation” event does not simply refer to a winding up of the company. It is usually defined as a liquidation, asset sale, merger, consolidation, or _any other reorganization that results in a change of control of the startup._ In other words, pretty much anything except an initial public offering.<sup><a href="#fn01" id="fref01">1</a></sup>

Next, we look at whether the liquidation preference has a “participation” element. The participation element of a liquidation preferences can be classified into three main types, which deal with whether the investors will receive any share of the liquidation proceeds _after_ receiving their preference:

* **Fully participating liquidation preferences:** The investors receive the “preference” defined above, and then share pro rata with the holders of common shares in any excess amounts above the preference. 
* **Capped participating liquidation preferences:** The investors receive the “preference” defined above, and then share pro rata with the holders of common shares in any excess amounts above the preference, up to a defined cap.
* **Non-participating liquidation preferences:** The investors receive the “preference” defined above, and has no share in any excess amounts above the preference. 

Needless to say, the fully participating liquidation preference is very favorable to the investors, while the non-participating liquidation preference is very favorable to management and/or founders. 

Let’s look at a simple example: 

<div class="example">
    <p>Assume that Avengers Inc., a high tech startup, has received an investment of $9 million by Stark Investments I, LP, a <abbr>VC</abbr> fund in 2010 at a pre-money valuation of $18 million. In 2015, Avengers Inc. receives an offer from Shield Technologies to buy them for $60 million.</p>
    <p>Avengers Inc. has the following cap table as of the date of the offer from Shield Technologies:</p>
    <table class="condensed">
        <caption>Cap Table for Avengers Inc. as of 2015</caption>
        <tr>
            <th class="center">Class of Shares</th>
            <th class="center">No. of Shares</th>
            <th class="center">Percentage Ownership</th>
        </tr>
        <tr>
            <td>Common Shares - Founders</td>
            <td class="right">4,000,000</td>
            <td class="right">44.44%</td>
        </tr>
        <tr>
            <td>Options - Issued</td>
            <td class="right">2,000,000</td>
            <td class="right">22.22%</td>
        </tr>
        <tr>
            <td>Options - Reserved</td>
            <td class="right">0</td>
            <td class="right">0.00%</td>
        </tr>
        <tr>
            <td>Series A Preferred - Stark Investments</td>
            <td class="right">3,000,000</td>
            <td class="right">33.33%</td>
        </tr>
    </table>
    <p>For simplicity, we will assume that the options are all out of the money, and thus will not be exercised, so the split is purely between the founders and Stark Investments.</p>
    <p>We have three scenarios, which illustrate each of the three types of participation elements described above:</p>
    <ol>
        <li>Scenario 1 — Fully participating liquidation preference, 1.0x preference</li>
        <li>Scenario 2 — Capped participating liquidation preference, 1.0x preference, participation capped at 2.0x</li>
        <li>Scenario 3 — Non-participating liquidation preference, 1.0x preference</li>
    </ol> 
    <p><strong>Scenario 1:</strong> Stark Investments receives $9 million from the $60 million liquidation proceeds, and then participates in the excess proceeds ($51 million) pro rata to its percentage stake 42.86% (because the 2,000,000 options are not exercised and thus the denominator is 7,000,000 shares rather than 9,000,000 shares, for a total of $30.86 million (48.57% of the liquidation proceeds).</p>
    <p><strong>Scenario 2:</strong> Stark Investments has to decide here whether it will avail itself of the capped liquidation preferences or convert to common shares and participate pro rata. If it avails itself of the liquidation preference, it will receive $9 million in preference and $9 million of the excess proceeds (amounting to $18 million, or 2.0x its original investment). If it converts to common, it will have a percentage stake of 42.86% since the options are not exercised, and obtain $25.71 million. It will therefore choose to convert to common.</p>
    <p><strong>Scenario 3:</strong> Stark Investments will make the same decision as in Secnario 2 and convert to common rather than claim only the $9 million preference.</p>
</div>

The liquidation preference is often considered to be the second most important economic term negotiated by a growth <abbr>PE</abbr> or <abbr>VC</abbr> firm. When I was learning the craft of <abbr>PE</abbr> a long time ago in a distant galaxy, one of the first lessons I learned—and subsequently drummed into others—was the importance of downside protection. Before considering the potential gain from an investment, a shrewd investor ought to first consider the potential for permanent loss of some or all of the capital invested in such investment. The liquidation preference is meant, like some other common investment terms, to provide a measure of downside protection. It does so by ensuring that in the event of a “liquidation” event, the investors will be repaid their initial investment _before_ any proceeds are paid to management and/or the founders. 

One example of how liquidation preferences across multiple <abbr>VC</abbr> financing rounds could affect management or founders in a liquidation event can be seen by looking at the cap table of [Palantir Technologies Inc.](https://www.palantir.com/), a company that currently has a $20 billion valuation as of its last financing round in July 2015: 

<div class="responsive-wrapper">
    <table class="condensed">
        <caption><span>Table 1:</span> <abbr>VC</abbr> financing for Palantir Technologies Inc. (Source: <a href="http://pitchbook.com/">Pitchbook</a>)</caption>
        <tr>
            <th class="center">Stock</th>
            <th class="center">No. of Shares Authorized</th>
            <th class="center">Original Issue Price</th>
            <th class="center">Liquidation Price</th>
            <th class="center">Liquidation Preference</th>
        </tr>
        <tr>
            <td>Series K</td>
            <td class="right">61,511,424</td>
            <td class="right">$11.38</td>
            <td class="right">$11.38</td>
            <td class="right">1.0x</td>
        </tr>
        <tr>
            <td>Series J</td>
            <td class="right">44,994,376</td>
            <td class="right">$8.89</td>
            <td class="right">$8.89</td>
            <td class="right">1.0x</td>
        </tr>
        <tr>
            <td>Series I</td>
            <td class="right">103,705,430</td>
            <td class="right">$6.13</td>
            <td class="right">$6.13</td>
            <td class="right">1.0x</td>
        </tr>
        <tr>
            <td>Series H1</td>
            <td class="right">42,735,043</td>
            <td class="right">$3.51</td>
            <td class="right">$3.51</td>
            <td class="right">1.0x</td>
        </tr>
        <tr>
            <td>Series H</td>
            <td class="right">35,002,700</td>
            <td class="right">$3.51</td>
            <td class="right">$3.51</td>
            <td class="right">1.0x</td>
        </tr>
        <tr>
            <td>Series G</td>
            <td class="right">58,189,543</td>
            <td class="right">$3.06</td>
            <td class="right">$3.06</td>
            <td class="right">1.0x</td>
        </tr>
        <tr>
            <td>Series F</td>
            <td class="right">44,595,912</td>
            <td class="right">$1.98</td>
            <td class="right">$1.98</td>
            <td class="right">1.0x</td>
        </tr>
        <tr>
            <td>Series E</td>
            <td class="right">117,886,772</td>
            <td class="right">$1.37</td>
            <td class="right">$1.37</td>
            <td class="right">1.0x</td>
        </tr>
        <tr>
            <td>Series D</td>
            <td class="right">121,750,000</td>
            <td class="right">$0.80</td>
            <td class="right">$0.80</td>
            <td class="right">1.0x</td>
        </tr>
        <tr>
            <td>Series C</td>
            <td class="right">78,814,194</td>
            <td class="right">$0.58</td>
            <td class="right">$0.58</td>
            <td class="right">1.0x</td>
        </tr>
        <tr>
            <td>Series B</td>
            <td class="right">171,078,560</td>
            <td class="right">$0.06</td>
            <td class="right">$0.06</td>
            <td class="right">1.0x</td>
        </tr>
        <tr>
            <td>Series A</td>
            <td class="right">1,425,000</td>
            <td class="right">$0.10</td>
            <td class="right">$0.10</td>
            <td class="right">1.0x</td>
        </tr>             
    </table>
</div>

Making some simplifying assumptions, we can compute a back of the envelope total for all the liquidation preferences in this capital structure at: $2.59 billion. In other words, the liquidation proceeds from any liquidation event involving Palantir would have to return at least $2.59 billion to satisfy all the 1.0x liquidation preferences to date, assuming: 

* Each series chooses to avail themselves of their liquidation preferences and not convert to common shares<sup><a href="#fn02" id="fref02">2</a>
</sup>
* The liquidation preferences are not participating and no series has negotiated for seniority<sup><a href="#fn03" id="fref03">3</a></sup>, i.e. the series are _pari passu_ with one another
* There are no dividends<sup><a href="#fn04" id="fref04">4</a></sup> covered by the liquidation preference or adjustments to the conversion ratios

In other words, Palantir would have to sell for significantly more than $2.6 billion for the founders to see any portion of the liquidation proceeds. Moreover, it requires the founders to aim for a very large payout to get an appreciable portion of the payout for themselves, i.e. aim to be one of the <abbr>VC</abbr>’s homeruns.  

I will make one finally brief note about liquidation preferences in connection with preferred shares received by convertible noteholders in a situation where there is a valuation cap (pretty much every convertible note commonly found in the industry), which I researched in connection with some of my work at [Polymath Ventures](http://polymathv.com/) over the summer of 2015. Founders of startups that have taken convertible note financings should be very careful about the way that such notes convert into preferred shares, as they can grant noteholders effectively a “super” liquidation preference due to the number of preferred shares issued to such noteholders at the date of the priced preferred equity round. This is not the place to go into too much detail on that—I will discuss it in a subsequent post—but in the interim one can read [Mark Suster](https://twitter.com/msuster) on this [topic](http://www.bothsidesofthetable.com/2012/09/05/the-truth-about-convertible-debt-at-startups-and-the-hidden-terms-you-didnt-understand/). 

To sum up, a growth capital <abbr>PE</abbr> or <abbr>VC</abbr> investor that does not adequately negotiate a liquidation preference to obtain downside protection is an idiot. A founder that does not carefully understand what a liquidation preference is and understand its potential impact on their payouts in a liquidation event is an idiot. 

The consequence of these two observations is that the liquidation preference is extremely heavily negotiated. A responsible investor will aim to obtain a fair liquidation preference to protect its downside, but recognizing the demoralizing effect of excessive liquidation preferences (a “liquidation preference overhang”), will not gouge the company by seeking excessive liquidation preferences except in a down round. 

<div class="footnotes">
    <hr class="w-50" />
    <ol>
        <li id="fn01">I have encountered some people who insist that an <abbr title="initial public offering">IPO</abbr> should be treated as a liquidity event for the liquidation preference. They’re very often lawyers who do not have any business working on <abbr>PE</abbr> or <abbr>VC</abbr> transactions. <a href="#fref01">&#8593;</a></li>
        <li id="fn02">This assumption is probably unrealistic as some of the early financing rounds will likely find it more profitable to convert to common given the low per-share liquidation preference. <a href="#fref02">&#8593;</a></li>
        <li id="fn03">This may not be entirely justified given that the Series B round appears to be a down round. <a href="#fref03">&#8593;</a></li>
        <li id="fn04">There are dividend rights attached to the preferred shares but for simplicity I have assumed them away to avoid having to calculate dividends, especially without knowing the terms of each financing round. <a href="#fref04">&#8593;</a></li>
    </ol>
</div>