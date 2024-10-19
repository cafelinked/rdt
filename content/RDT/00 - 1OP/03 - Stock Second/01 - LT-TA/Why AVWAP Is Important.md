---
title: <% tp.file.title %>
draft: false
tags:
---

<div class="bg-secondary">
<h1 class="py-5 ms-3 ms-md-4 my-0">Why AVWAP Is Important</h1>
</div>
<div class="d-flex align-items-center flex-wrap text-muted ps-3 ps-md-4 py-3 border-top border-bottom">
<div class="border-end pe-3 me-3">
<span class="badge bg-faded-primary text-primary">
Stock Second </span>
</div>
<div class="fs-sm pe-3 border-end me-3">6 min read</div>
<div class="fs-sm">
2024-04-09 </div>
</div>
<section class="px-3 px-md-4 py-4">
<h4 class="wp-block-heading">The key to VWAP is knowing where to anchor it. There are events where Asset Managers and Traders make allocation decisions and that is where we anchor ours.</h4>
<p>Liquidity is an issue for large institutions. They often use a firm like Citadel to execute the orders and the VWAP is a price they guarantee for the fill. It is not necessarily the intraday VWAP although that is relevant for day trading because it is used for smaller orders. For large orders that could drive the price, they need time to fill the order. The fill price could be a VWAP since a particular date (earnings) that Citadel has to honor, and they will work that order for days or weeks. It is important to know where these price points are and when Asset Managers are likely to make allocation decisions. I have been working with anchored VWAP (AVWAP) that calculates the D1 VWAP from a user defined starting point and here are my observations. <a title="" href="https://www.youtube.com/watch?v=ICW4sR3HOjU" target="_blank" rel="noopener">This 1 hour video will also on AVWAP will also help you to understand it.</a></p>
<p>In addition to large Asset Managers wanting to buy the stock, trading firms are active in their proprietary accounts. They stress discipline, but they do not want to completely handcuff traders. As long as the stock is within 1SD of the AVWAP, the trade is in an acceptable range. This is an industry standard and I have heard it from a few sources. I also don’t know where these firms anchor the VWAP, but I can take an educated guess.</p>
<h2 class="wp-block-heading" id="Anchor_Points">Anchor Points</h2>
<p>The key is finding the right anchor point. Just like VWAP starts at the beginning of the trading session, we need to determine a good starting point for AVWAP. In my experience earnings releases and the end of the quarter are key decision making periods. Earnings announcements allow Asset Managers to gauge current performance and the company’s guidance for the future. This is when they would decide to buy (or sell) a stock. The end of the quarter is also a time when they decide how to allocate funds. This is also when many indices rebalance.</p>
<h2 class="wp-block-heading" id="SD_Lines">SD Lines</h2>
<p>The distance from the AVWAP is important. If Citadel is going to honor an AVWAP price, they will be active when the customer places the order. They have algorithms to execute the trade. Once the stock or index moves away from the AVWAP, it becomes support. Anyone looking to ride that trading will buy at the AVWAP. They might have missed the trade or they might be looking to add to a position so it will act as support. It is important to realize that AVWAP is different from support at a major moving average. Major SMAs are a psychological support level. On the other hand, AVWAP is actual support because firms are allocating funds at that level with real money. Once the stock/index moves substantially away from AVWAP, institutional traders can still enter within 1 standard deviation. If it rises above that level, they will bite at the chance to buy at that level if it dips down to it. Obviously, this is only the case if the stock is strong. Some stocks will just chop around the AVWAP and they are not of great interest to us. Imagine if we had a variable that triggered an alert when the stock rallied above the 1SD AVWAP, back below it and then above it again (we will have it).</p>
<p>So let’s take a minute to talk about the 1 SD lines above and below the AVWAP. We take the current daily value of the 20-day standard deviation for the stock price (not the 20-day standard deviation of the AVWAP) and we add that value to the AVWAP for the upper line, and we subtract that value for the lower line. That gives us our upper and lower bands. </p>
<p>In the first chart, we are going to look at SPY on a quarterly basis. The far left of the chart is the start of Q2 (ignore the lower dark green line). The heavier dark green line is the AVWAP from the start of the quarter. The market spends sometime around the AVWAP and then it runs away from it. Any trader who missed that entry is going to be waiting for a pullback to the AVWAP. Consequently, it becomes support. You can see how the market did not spend much time there before it lifted off. Next, the market rallied above the 1SD level. Traders who were looking to add would be waiting for any dip to the 1SD level and they only had one day to buy there.</p>

                    <div class="gallery w-100 d-md-flex mb-md-4 p-4">
                        <a href="https://oneoption.com/wp-content/uploads/2023/06/spy061523.png" class="gallery-item rounded-3" data-lg-id="03d6feb5-2a68-4872-8e0c-cc76d54a5c58">
                            <img src="https://oneoption.com/wp-content/uploads/2023/06/spy061523.png" alt="Once the market lifted off from the quarterly AVWAP, that level became support and traders were anxious to buy there.">
                        </a>
                        <div class="h6 fst-italic mt-3 mt-md-0 ms-md-4 gallery-caption">Once the market lifted off from the quarterly AVWAP, that level became support and traders were anxious to buy there.</div>
                    </div>
                
<p>The next chart is MSFT and the AVWAP starts the day after the earnings report because it was posted after the close. If Citadel has an order to buy VWAP, they are going to buy heavily on that first day and that is why the stock gaps up. They will continue to add close to the AVWAP and since the stock is rising, they will be able to enter around the AVWAP. They won’t make money honoring every AVWAP order, but they will on the vast majority of them and that is why they make so much money. According to the CEO of Citadel in a Congressional testimony, Citadel touches 35% of all orders and they use VWAP algorithms extensively. Once MSFT drifts away from the earnings AVWAP, the stock rises above the 1SD point. It is out of reach for institutional traders and they pounce on the first pullback to that level. You can see how it acted like a magnet towards the end of the chart.</p>

                    <div class="gallery w-100 d-md-flex mb-md-4 p-4">
                        <a href="https://oneoption.com/wp-content/uploads/2023/06/msft061523.png" class="gallery-item rounded-3" data-lg-id="ef17f55f-9b75-4c1d-ae6c-fd396769f6c8">
                            <img src="https://oneoption.com/wp-content/uploads/2023/06/msft061523.png" alt="The stock does not spend much time at the earnings AVWAP and that is a sign of strength. Traders will even buy at the 1SD for AVWAP if the stock is particularly strong.">
                        </a>
                        <div class="h6 fst-italic mt-3 mt-md-0 ms-md-4 gallery-caption">The stock does not spend much time at the earnings AVWAP and that is a sign of strength. Traders will even buy at the 1SD for AVWAP if the stock is particularly strong.</div>
                    </div>
                
<h2 class="wp-block-heading" id="How_is_This_Useful_">How is This Useful?</h2>
<p>How do we use this information? Knowing where institutions are buying or selling tells us where we can expect support and that helps us with our entry. We want to join them. You will also see in the MSFT chart that when the stock rallies above the 1SD level, there is some resistance. Trading firms will lighten the load at those levels and take gains with the intentions of re-entering when the stock comes back within that range. Knowing this helps us manage the profits on our trades. Here are a few more examples.</p>

                    <div class="gallery w-100 d-md-flex mb-md-4 p-4">
                        <a href="https://oneoption.com/wp-content/uploads/2023/06/meta061523-601x1024.png" class="gallery-item rounded-3" data-lg-id="2577f594-9cb7-44fc-8931-4432b089f2bf">
                            <img src="https://oneoption.com/wp-content/uploads/2023/06/meta061523-601x1024.png" alt="Here you can see how the AVWAP is a magnet. Once the stock moves away from it, the 1 SD line becomes a support level.">
                        </a>
                        <div class="h6 fst-italic mt-3 mt-md-0 ms-md-4 gallery-caption">Here you can see how the AVWAP is a magnet. Once the stock moves away from it, the 1 SD line becomes a support level.</div>
                    </div>
                
<p>This will be a new 1OStudy and you will be able to add it to the charts for Earnings, Monthly and Quarterly anchors. The anchor will start with each new event and end at the start of the next event so that you can scroll back and see how well these price levels performed.</p>
</section>
