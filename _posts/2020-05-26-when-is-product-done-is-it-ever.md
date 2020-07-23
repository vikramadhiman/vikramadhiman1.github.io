---
layout: post
title:  "Product Development | When is a Product Done"
author: vikramadhiman
categories: [ Product Management, Product Development ]
image: assets/images/posts/definition-of-done.jpeg
featured: true
---
Most software engineers, product designers, and product managers have a strong desire to iterate to perfection, often clashing with other obvious benefits like urgent business priorities like a new product line. Questions on the lines of are we prioritizing correctly, should we block time to spend on improvements, if we are doing too many things and if we are leaving products in an unfinished state, start being asked. Sometimes, you’ll be asked (like the title of this post): <strong>When is a Product Done?</strong>

Let’s start with a common word in product development these days — MVP. Minimum VIABLE Product.

<img src="/assets/images/product-done-mvp.jpeg" alt="Minimum Viable Product" title="Minimum Viable Product" />
<em>via: <a href="idk.dev" target="_blank">idk.dev</a></em>

None of the three words — minimum, viable, product — are quantifiable or easy agreed upon individually or when put together. The original intent of MVP was to ship a version of software to see if it can get any traction and get feedback to iterate and improve. The choice of the word ‘software’ is deliberate here. MVP is mostly used in software context and for good reasons too. In no other industry can we analyze and incorporate customer feedback this easily and this quickly.

```
MVPs were originally designed to combat knowledge scarcity. 
Now, they are now also used to counter people or patience scarcity.
```
MVPs being a quick way to get to market can create two issues: technical debt and experience debt. One can argue that until you have paid all the technical debt and experience debt, the product is not complete. This means not stopping with MVP and doing v2, v3 of the product immediately after the MVP. However, this does not always happen for two reasons: there is something deemed more important to work on than iterating on the feature or we are waiting to get traction/ data/ research on the MVP so next iterations.
The features are revisited (v2 and other iterations) technically or from experience perspective only when we have strong reasons to do so: research or data has pointed something out, there are technical outages, competition launches a dramatic improvement, someone points out usability flaws or bandwidth frees up.

```
All this seems like a good plan but things rarely go as per plan.
```
When the feedback and urgent priorities come, they usually clash. Some products get preferential treatment while others languish. This leads to confusion, arguments, low morale, and backdoor lobbying. Not an ideal situation. Given this, it may be useful to ask one more question with the title of the post that is, when is the product done. When is it ok to leave a product left undone? (I want to shout — Never — but perhaps useful to dig deeper).

It is perhaps important to define what do we mean by ‘product’ here. Product in this post means both, features as well as a collection of features (eg: emergency assistance as well as safety toolkit containing emergency assistance).

```
‘A successful product is never done or perfect.’
- Geoff Teehan, Product Design Director at Facebook
```

While the answer from Facebook’s Product Design Director is simple and nuanced — it does not give practical advice. There is plenty of advice going around though — from taking all the time you need to make a quality product (like the recent <a href="https://medium.com/the-year-of-the-looking-glass/how-to-make-things-high-quality-f466f875227d" target="_blank">TTBQT</a>one from Julie Zhuo) to <a href="https://twitter.com/naval/status/1158964119023652864" target="_blank">shipping speed being paramount</a> to <a href="https://www.amazon.in/Planning-Extreme-Programming-Kent-Beck/dp/0201710919/ref=sr_1_fkmr0_1?keywords=martin+fowler+xp+exp%3Bained&qid=1565360344&s=books&sr=1-1-fkmr0" target="_blank">ship at a regular cadence</a> and improve. There are other examples of products being extremely frugal in experience improvements like say a Google home page adding just a Search button and a copyright text being enough to make it <a href="https://www.huffingtonpost.in/2012/03/27/google-design-sergey-brin_n_1384074.html" target="_blank">complete</a> (a true MVP even before the term was made popular). In another case, Facebook newsfeed went from good to great to bloatware as they continued to iterate. On the other hand, Tiktok took the LIVE video feature from social media apps (including the one in FB) and added a killer automatic swipe discovery (a bit like stories) to make it a truly usable product for a section of the audience. New features don’t necessarily corrupt. Smartphones have added cameras and machine learning to increase the quality of photos significantly.

<em>All of the above examples show that different iterations produce dramatically different results. So, when to iterate and when not to?</em>

It may be useful to plot this:

<img src="https://vikramadhiman.github.io/assets/images/product-done-diagram.png" alt="Product Development Diagram" title="Product Development Diagram" />

Let’s start with point B, the first goal post (refer diagram above).

<strong>
In a nutshell, when exponential or dramatic bets are down, risky or plain delusional and you are about 90 percent of your originally stated goals, you’ve likely reached point B.
</strong>

If you can’t invest in reaching even point B, then you should seriously question if we need that product. Here is a collection of criteria (from discussions with some product, engineering, and design leaders) that can indicate if you’ve reached point B. Here we go:

<ul>
	<li>Customers complaints are significantly low and don’t impact business metrics like NPS, completed orders, net revenue</li>
	<li>Next iterations of the product start having sections like ‘too much complexity’, ‘too much clutter’, ‘why are we ruining this’</li>
	<li>The product meets the internal benchmarks of quality:</li>
	<li>There is data logging to measure the customer experience</li>
	<li>There is research to explain customer behavior</li>
	<li>The tech debt is fully cleaned or settled for the features</li>
	<li>The next product tasks start moving from must have to should have to could have</li>
	<li>You’ve done at least one (possibly multiple) UX design overhaul of the product (the next redesign prototype makes it look like the first design) and the next UX redesign doesn’t seem imminent</li>
</ul>

The ideal strategy to get to point B is dramatic and exponential bets via a dedicated cross-functional team. The effort-to-return ratio should be significantly high. If that is not the case, you are doing it wrong. You can have ‘significant’ effort projects too — but they should then also have outsized returns as well. An example of a bet is redesign. Another example is targeting a new set of customers or problems. Yet another is redoing the technology architecture to support scaling or problem-solving approach. A useful thought process is to think of getting to point B as a product-market fit and crossing the chasm problem combined into one on the <a href="https://en.wikipedia.org/wiki/Crossing_the_Chasm" target="_blank">technology adoption curve</a>.

Post point B you get to the second milestone: point C. This is also perhaps the most interesting section of the above diagram is the 2nd phase (between points B and C).

<em>
From point B to C, you have a lot of incremental effort for largely incremental and sometimes exponential returns i.e. a lot of iterations for relatively small improvements in product metrics and experience.
</em>

The ideal strategy at this phase is small incremental progress via small experiments (example: Booking.com) — transitioning from 0–1 to 1-n mindset. This needs largely a non-matrix structure i.e. specialized teams. The number of stakeholders increases significantly. While experiments and steps may be small, the effort and number of teams involved may be high. For instance, past point B, you will need a lot of specialized folks to decide just the copy of the blurb that shows terms and conditions opt-in check-box to customers. Within that phase, as you progress, the improvement becomes harder. Why is that so? A lot more variables need to be analyzed and factored into consideration — hence, research and experiments are both slow.

<img src="{{ site.baseurl }}/assets/images/product-done-stakeholders.png" alt="Product Management Stakeholders" title="Product Development Stakeholders" />

While small incremental progress with sometimes big returns is one strategy, this is also the time to think of disruption (building your own Tiktok or iPhone before the competition does — this is Hard as the second phase can go on for a long time). A company that is trying this is Uber (they are not afraid to break their current moat of ride-hailing to venture into micro-mobility/ public transportation/ SuperApp). One could argue that they never really reached point B though esp on product-market-business fit.

<strong>
Just because your product is moving slowly does not mean it has reached point B. It could very well be you, your imagination and your rigor as well as a misreading of the situation that needs a more adventurous strategy (redesign, retargeting, segmentation) than an incremental strategy.
</strong>

After point C, you get to a declining phase. From C to D can be a gradual, slow decline that is sometimes not even noticed internally (noticed externally though, one classic sign — early adopters leaving). From point C to D, the product has a slow decline i.e. it still has a lot of usages (and market share/ profit). Some of the incremental experiments and work results in good progress as well. This does not mean zero work. On the contrary, this may mean a lot of work on maintenance, upgrades, integrations, net revenue. What makes this phase tricky is that as you cross point C for a customer segment, you could be entering point B for a new segment — new markets for instance. This is also not a point of no return and there is a chance for rejuvenation.

Let us look at this with an example of the iPod, which had a declining phase for most of its models, ever since the iPhone launched. Active product development continued till 2015 when iPod shuffle was launched (sales did not spike up though). All models of iPod were discontinued in 2017 except iPod touch which <a href="https://www.t3.com/news/ipod-isnt-dead-after-all-apple-will-unleash-an-iphone-x-style-redesign-for-ipod-touch" target="_blank">expects a redesign in 2019</a>.

The example of the iPod also shows how redesigning and relaunching may be one strategy to avoid falling C to D trap. This is a different approach from the small incremental progress one that we observed before. Which approach is best for you depends on the market innovation curve as well. Travel planning vs new phones, as discussed in this post, is a classic example.

Once you do have fallen to a point D (Myspace in ~2010, Evernote now?), the next logical steps are either complete reinvention or likely, retiring a feature. Given that even retiring a product or a feature into oblivion needs work, we will never reach a ‘done’ product as long as it is LIVE and used. Some things — usually parameters of quality like ‘speed’ and ‘tech debt’ — would continuously be worked on. There will also be maintenance, upgrades, unintended consequences on new things that need work. Also, not every product can be retired immediately. For instance, even though the usage of safety features declines with better operations in a ride-hailing app, you’ll still keep them. Some others may have their backend components used by several other products (monoliths while moving to a Microservices architecture can remain for years). The strategy to follow in this case is good QA automation and minimizing dependency for new launches. This can take a while and that is fine. Once a feature reaches a low enough (say 10%) usage of its peak, you should seriously consider taking time out for a proper burial. 

Modern products, especially Internet products, have a more involved flow than a sequential flow from what has been discussed in this post (example of that was in the iPod discussion a few paragraphs above). A product on a stage of B to C can quickly go to finding B (phones -> smartphones, chips -> quantum computing). In other cases, there can intentional hastening of products from B to C to D (Windows). Also, we might not have the capacity to design, research, analyze, develop all the products thoroughly. Feedback cycles and the availability of people to work on something can be mismatched. What should we do in such cases? Interesting times and questions, and this perhaps need another post.