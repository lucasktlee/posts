<p class="lede">Negotiating purchase prices for private equity transactions can be an experience rather similar to being in a boxing ring. They are also often the subject of very lengthy and complex legal language in the acquisition agreement.</p>

The acquisition agreement provisions relating to the purchase price are some of the most complex and heavily negotiated provisions in a private equity acquisition agreement. While almost every private equity transaction will be paid for in cash–thereby obviating the need to negotiate over whether the purchase price will be paid in cash, stock of the purchaser(s), or some combination thereof—the seller(s) and purchaser(s) will nevertheless spend a lot of time negotiating over the quantum and any adjustments thereto, the timing, and the existence of any post-completion earn-outs for the seller(s).

## 1. The Threshold Question: Completion Accounts or Locked Box

There are two principal methods of determining the purchase price in a private equity transaction:

1. **Completion accounts:** An estimate of the cash, debt and closing date working capital on the closing date is made by the seller(s), and the purchase price paid on the closing date is based on this estimate. After the closing date, the purchaser(s) will review the estimate to determine what the _actual_ cash, debt, and closing date working capital on the closing date were, and the final purchase price will be adjusted to take into account any differences between the estimates and the actual amounts.
2. **Locked box:** The purchase price is fixed by reference to a historical balance sheet (often the last audited balance sheet), and there is no subsequent adjustments to the purchase price.

This post will focus on the former, which tends to be more common in the U.S. and Asia. The latter has tended to be more common in Europe, and may eventually become the subject of a separate post. It suffices to note in this post that:

* The economic interest and risk in the target company pass from seller(s) to purchaser(s) at _different_ times for completion accounts and locked box methods.
* The completion account method has historically been viewed as more buyer-friendly, while the locked box method has historically been viewed as more seller-friendly.
* The completion account method frequently results in longer and more complex acquisition agreements when compared to acquisition agreements using the locked box method.
* The completion account method can result in less upfront financial due diligence since there will be an opportunity to adjust the purchase price post-closing when the purchaser(s) have control over of the target company.<sup><a href="#fn01" id="fref01">1</a></sup>

### Economic Interest and Risk in Completion Accounts and Locked Boxes

I’ve had people ask me why economic interest and risk pass from seller(s) to purchaser(s) at different times for completion accounts and locked box methods. Here is the reason.

In a private equity transaction that uses the completion account method, the _final_ purchase price is based on the actual cash, debt, and closing date working capital of the target company on the closing date. In other words, the purchaser(s) pay for the _actual assets and liabilities_ of the target delivered by the seller(s) on the closing date. This means that if there is any increase (decrease) in the actual assets and liabilities of the target, company the purchase price received by the seller(s) is increased (decreased). Therefore, the _economic interest and risk_ remains with the _seller(s)_ until the closing date.

In a private equity transaction that uses the locked box method, the _final_ purchase price is based on a historical balance sheet, which is often, but not always, the last audited balance sheet of the target company. Given that the target company continues to operate its business from that point until the closing date, this valuation is necessarily out of date, and there are no adjustments to the purchase price post-closing. Therefore, any increase (decrease) in the actual assets and liabilities of the target from the date of the historical balance sheet to the closing date does not result in a change to the purchase price. Therefore, the _economic interest and risk_ passes to the _purchaser(s)_ from the date of the historical balance sheet.

## 2. The Purchase Price

I will now turn to the computation of the purchase price.

### The Enterprise Value and Cash-free/Debt-free Value

The most common practice for purchase prices in private equity transactions is to specify that it will be on a “cash-free/debt-free” basis, assuming a normalized level of working capital. The basis for the purchase price is the **“enterprise value”** of the target company, which in private equity transactions is typically computed as a _multiple_ of its <abbr title="Earnings Before Interest, Tax, Depreciation and Amortization">EBITDA</abbr>.<sup><a href="#fn02" id="fref02">2</a></sup> The assumption is that <abbr>EBITDA</abbr> is a reasonable approximation of the cash flows generated by the _operations_ of the target company.

The following [table](#table01) is an example of how one would calculate the enterprise value:

<table id="table01">
    <caption><span>Table 1:</span> Example Enterprise Value Calculation</caption>
    <tr>
        <td><strong>Entry <abbr>EBITDA</abbr> multiple</strong></td>
        <td>7.00x</td>
    </tr>
    <tr>
        <td><strong>2015 <abbr>EBITDA</abbr> ($ millions)</strong></td>
        <td>325</td>
    </tr>
    <tr style="border-top: #333 solid 3px">
        <td><strong>Enterprise Value ($ millions)</strong></td>
        <td><strong>2,275</strong></td>
    </tr>
</table>

The idea behind the rough equivalence of enterprise value and cash-free/debt-free value is that the enterprise value is calculated as a multiple of <abbr>EBITDA</abbr>. By definition, using an <abbr>EBITDA</abbr> multiples values the target company as if it had no debt as interest expense and principal payments are not taken into account. Furthermore, the <abbr>EBITDA</abbr> multiple excludes excess cash. It also excludes the value of other non-operating assets.<sup><a href="#fn03" id="fref03">3</a></sup> (Roughly speaking, the enterprise value generated from an <abbr>EBITDA</abbr> multiple can be thought of as the value of the core operating business of the target company.)

### The Net Debt Adjustment

So, we can think of the enterprise value derived from an <abbr>EBITDA</abbr> multiple as the _core operating business value_ as if the target company was funded entirely by equity and had no excess cash, i.e. the cash-free/debt-free value. In reality, most target companies in private equity transactions _will_ have some measure of short-term and long-term debt on their balance sheets. It will also have items on their balance sheets that we can consider to be “debt-like”. Most target companies will also have some amount of _excess cash_ on their balance sheets. The purchase price therefore needs to be adjusted to take into account the debt and excess cash on the balance sheet of the target company (see [Table 2](#table02)).

<table id="table02">
    <caption><span>Table 2:</span> Example Net Debt Adjustment Calculation</caption>
    <tr>
        <th> </th>
        <th>$ millions</th>
    </tr>
    <tr>
        <td><strong>Enterprise Value</strong></td>
        <td>2,275</td>
    </tr>
    <tr>
        <td>Plus: Cash and cash equivalents</td>
        <td>500</td>
    </tr>
    <tr>
        <td>Less: Debt and debt equivalents</td>
        <td>(1200)</td>
    </tr>
    <tr style="border-top: #333 solid 3px">
        <td><strong>Enterprise Value Adjusted for Net Debt</strong></td>
        <td><strong>1,575</strong></td>
    </tr>
</table>

In principle, as shown above, net debt adjustment results in the purchaser(s) paying the seller(s) for any excess cash left in the target company and reducing the purchase price for any debt that remains on the balance sheet of the company at closing.

(As an aside, I have seen situations where people prefer to split out the “debt equivalents” from the net debt calculation, but I tend to prefer to keep them together, since conceptually they represent liabilities of the business that reduce the purchase price to the extent that they remain on the balance sheet at closing.)

#### Defining Cash and Cash Equivalents

One area that will become quite an area of contention in most private equity transactions is the definition of “cash and cash equivalents”. This can consume a lot of time, because “excess cash” can include a lot of cash that is not actually available to either the seller(s) or purchaser(s). Some examples of this might be cash held in foreign bank accounts, restricted cash used as security for performance bonds, or escrow accounts from asset sales. All of these items need to be considered when determining what “excess cash” means.

#### Defining Debt and Debt Equivalents

Likewise, “debt” can also include a number of “debt equivalents” that might not be so obvious at first, such as accrued but unpaid bonuses, unfunded pension obligations, or letters of credit. All of these items need to be considered when determining what “debt equivalents” means.

### Net Working Capital Adjustment

A target company will have a “normal” level of working capital necessary for it to operate in the normal course of business. Determining this level can be an interesting exercise, especially for companies that experience significant seasonal fluctuations or that have experienced substantial changes in their business or industry, but it is not impossible. Once the normal level of working capital is determined (often called the “target net working capital”), one then has to consider whether the actual net working capital of the target at closing is above or below this target. If it is above the target, the purchase price is adjusted upwards to reflect the excess; if it is below the target, the purchase price is adjusted downward to reflect the shortfall.

<table id="table03">
    <caption><span>Table 3:</span> Example Net Working Capital Adjustment Calculation</caption>
    <tr>
        <th> </th>
        <th>$ millions</th>
    </tr>
    <tr>
        <td><strong>Enterprise Value Adjusted for Net Debt</strong></td>
        <td>1,575</td>
    </tr>
    <tr>
        <td>Plus: Net Working Capital</td>
        <td>60</td>
    </tr>
    <tr>
        <td>Less: Target Net Working Capital</td>
        <td>(30)</td>
    </tr>
    <tr style="border-top: #333 solid 3px">
        <td><strong>Purchase Price (Equity Value)</strong></td>
        <td><strong>1,605</strong></td>
    </tr>
</table>

The net working capital adjustment is normally one of the last adjustments made to bring the enterprise value of the target company to the equity value. The equity value is the amount actually paid to the seller(s) and represents the value of the equity claims the seller(s) have on the target company.

### Other Adjustments

One can imagine, on a case-by-case basis, that there might be other adjustments that need to be made to arrive at the purchase price, for example substantial capex requirements. We will not go into the details of this—it tends to be too abstract without a specific case to analyze—but it is important to note that in certain transactions the “other adjustments” can result in significant changes to the final purchase price.

## 3. Completion Accounts

Now, having arrived at the purchase price, the next step is to think about how the completion accounts works to adjust the purchase price so that it is close to the _actual_ value that the purchaser(s) receive at closing.

### Seller(s)’ Estimated Purchase Price

With a completion account mechanism, the seller(s), at some point prior to closing, will make an _estimate_ of the cash and cash equivalents, the debt and debt equivalents, and the net working capital. Using this, they will compute an _estimated purchase price._ This is the amount that will be paid by the purchaser(s) to the seller(s) at closing. To avoid inconsistencies and subsequent disputes, a good acquisition agreement will specify in some detail exactly what goes into computing each element of the purchase price, for example detailed definitions of what is cash and cash equivalents, what debt equivalents will be included, and what items comprise net working capital.

At closing, the purchaser(s) deliver the purchase price to the seller(s), and control over the target company passes to the purchaser(s).

### Purchaser(s)’ Completion Accounts

After closing, the acquisition agreement will specify that the purchaser(s) will prepare completion accounts within a stipulated time frame,<sup><a href="#fn04" id="fref04">4</a></sup> consisting of an unaudited balance sheet of the target company and an itemized computation of the purchase price. To avoid inconsistencies with the estimated purchase price, a good acquisition agreement will specify that the completion accounts must be prepared on the same basis as the estimated purchase price, using the same definitions and accounting policies, and _excluding_ the effects of any post-closing financing and/or corporate reorganizations made by the purchaser(s).

The seller will, of course, want to be able to review the completion accounts, and will—optimally—negotiate to have access to the working papers, supporting data, and employees of the target company to verify that the completion accounts have been prepared consistently with the methods prescribed in the acquisition agreement and used by the seller(s) in computing the estimated purchase price.

### Dispute Resolution

As a general rule, there are _always_ likely to be disputes over the completion accounts. This is the point at which seller(s) and purchaser(s) are likely to clash over the computation of cash and cash equivalents, debt and debt equivalents, and items of net working capital. Seller(s) will be worried that the purchaser(s) will engage in “price-chipping”, particularly if there is an element of subjectivity (and there almost always is) in the accounting treatment of assets and liabilities used to compute the cash and cash equivalents, debt and debt equivalents, and items of net working capital.

When there is a dispute over the amount of any item in the completion accounts, the usual first step is to _negotiate in good faith_ to resolve such dispute within a stipulated time frame. If the seller(s) and purchaser(s) cannot resolve the dispute through negotiation, then it is time to move the dispute to a third party for resolution.

Rather than engage in—potentially costly and time consuming—litigation, most completion account disputes will be referred to an accounting expert for determination. This expert will usually be the dispute resolution group of a recognized accounting firm (most often one of the “Big Four”). The expert will usually be limited to addressing the dispute at hand, and will also be limited to assigning a value that falls within a range bounded by the estimated value computed by the seller(s) and the value computed by the purchaser(s).

### Settlement of Final Purchase Price

Once a final purchase price has been agreed (and any disputed items settled by negotiation or through the dispute resolution mechanism in the acquisition agreement), if the final purchase price is _greater than_ the estimated purchase price, the purchaser(s) pay the difference to the seller(s). If the final purchase price is _less than_ the estimated purchase price, then the seller(s) pay the difference to the purchaser(s).

## Conclusion

A completion account method of adjusting the purchase price to reflect the actual economic value of the target company tends to require a fairly complex and interrelated set of provisions in the acquisition agreement. It can take a few re-reads to wrap one’s head around it. Given its popularity in the U.S. and Asia, though, it is well worth getting familiar with it.

While I have tried to give sufficient detail to this post, I could, conceivably, write several more posts just on this topic. There are a lot of nuances that can trip the unwary. That being said, the first step to mastering the completion account method is to understand its fundamentals, which this post covers. Only then can one begin to explore the subtleties that can trip the unwary.

## Other Posts in the <abbr>SPA</abbr> Series

* [Stock Purchase Agreement Series — Overview](https://lucasktlee.com/2016/03/25/stock-purchase-agreement-series-overview/)
* Stock Purchase Agreement Series — Purchase Price
* [Stock Purchase Agreement Series — Representations and Warranties](https://lucasktlee.com/2016/04/25/spa-representations-and-warranties/)
* [Stock Purchase Agreement Series — Indemnities](https://lucasktlee.com/2016/05/09/stock-purchase-agreement-series-indemnities/)
* [Stock Purchase Agreement Series — Closing Conditions](https://lucasktlee.com/2016/07/04/spa-closing-conditions/)
* [Stock Purchase Agreement Series — Covenants](https://lucasktlee.com/2016/07/27/spa-covenants/)

<div class="footnotes">
    <hr class="w-50"/>
    <ol>
        <li id="fn01">That being said, in practice a prudent private equity professional will nevertheless be cautious and do as much upfront financial due diligence as time and resources permit. <a href="#fref01">&#8593;</a></li>
        <li id="fn02">For a public company this might not be the case, since one might be using alternative methods to value a public company and in any case one needs to translate the valuation into public market per share equivalents and premiums to the prevailing share price. <a href="#fref02">&#8593;</a></li>
        <li id="fn03">My favorite Wharton finance professor likes to give an example of a company such as a large multinational brewery that may have a substantial number of minority investments in foreign breweries due to foreign direct investment restrictions. The investment income from these minority investments is not captured in <abbr>EBITDA</abbr>, though it is captured—normally—in <abbr title="Earnings Before Taxes">EBT</abbr>. The presence of such minority investments can, in some cases, have a significant impact on valuations. As this post is not a study of valuations, I will say nothing more on this topic here. <a href="#fref03">&#8593;</a></li>
        <li id="fn04">The seller(s), of course, will prefer a shorter time frame; the purchaser(s), a longer time frame. <a href="#fref04">&#8593;</a></li>
    </ol>
</div>
