---
layout: post
title: "Age, expertise, and gender noticeably affect sentiment"
date: 2013-05-20 08:00:00 -0600
categories: [data analytics]
tags: [data analytics, ratings and reviews]
---

If you’ve ever been chided by your grandfather for not finishing your supper, using the computer too much, or listening to rock ‘n roll, you may have internalized the stereotype that the elderly are grumpy and cantankerous. Despite our subjective experiences, psychological research exists that counters this, and instead proposes that <a href="http://www.economist.com/node/17722567" target="_blank">positive emotions increase with age</a>.

### Positive sentiment increases with age

A study by Arthur Stone, PhD illustrates that self-reported well-being dips during the younger adult years then increases sharply from age 50, with females being slightly more positive than males. Recently, the Social Analytics team dove deep into our ocean of review data and discovered strikingly similar trends in product ratings.

![The U-bend](/images/AA1.gif)

The visualization below represents our analysis of 12,000 reviews on brands that sell beauty products at department stores. Here we can see a similar bend in average rating by age group that Stone shows with subjective well-being. Ages 25-34 and 35-44 are the most negative, while the older age groups are most positive – beginning in the 45-54 age bracket.

![Average Rating by Age Group](/images/AA2.jpg)

Curious to see whether this pattern holds in other industries, we replicated the analysis on 275,000 hotel reviews and produced a markedly similar chart. In fact, we are seeing this trend across the entire network, and I expect to see it in future investigations.

Brands and retailers targeting Millennials need not fear the critical opinions of these young and middle-aged adults. Their feedback contains valuable product improvement insights. Knowing what’s wrong reveals what should improve in the next iteration.

### Women are more positive than men

Stone shows a heightened positivity in females across the board, which also coincides with our analyses. In our <a href="http://media2.bazaarvoice.com/documents/Conversation_Index_Bazaarvoice_20111010b.pdf" target="_blank">Conversation Index Vol. 1</a>, we found that the average rating for female-written reviews was 4.43 stars, compared to the male average of 4.32 stars. This can also be seen in this more recent industry-level example from a sample of office supplier data in 2012:

![Average Rating by Gender](/images/AA3.jpg)

Despite the lack of an experimental design, it’s fascinating to see how quantifiable, _external_ judgments – like product ratings – can be an extension of _internal_ cognitive judgments – like perception of happiness. Although some say that <a href="https://www.linkedin.com/pulse/20130515123717-284615-the-big-hole-in-big-data" target="_blank">data lacks emotion</a>, let’s not forget about the insights that can be achieved by tying consumer demographic data to raw emotional data itself.

### With great contextual data come great customer insights

Sure, demographics like age and gender are bread and butter, but if you want the “full meal deal,” you need to be collecting as much **contextual data** as you can about your customer base. As an appetizer, we explored 75,000 reviews on five of our top hardware retailers who ask their customers about skill level.

We discovered that customers who deem themselves **experts** give, on average, 13% lower ratings when compared to **beginners**. Similarly, customers using products as trade professionals rate 6% lower than the casual “DIY-er.” This may seem pretty intuitive, but now we can **prove it** using data.


![Rating by expertise in hardware](/images/AA4.jpg)

![Rating by customer type in hardware](/images/AA5.jpg)

Retailers are able to **hear** their customers with reviews, but they need to truly **listen** by digging into the text. Even though these highly-skilled customers give less positive reviews, their knowledge is a key to gaining awareness of what products could use improvement.

We ran these reviews through a sentiment analysis engine to breakout the top themes, frequently used phrases, and their associated sentiment scores. Here we can see that these experienced customers are still happy with things like **value**, **price**, and **ease of use**, but are scrutinizing qualities like **fit**, **size**, and **design**. Indicated by negative sentiment (red), specific product categories are called out, like shower heads, ceiling fans, and light fixtures that should be more closely examined.

![Word cloud of hardware review text](/images/AA6.jpg)
At the end of the day, star ratings and demographics are just the surface. Break through and actively listen to the voice of your customer by asking relevant questions. Then, read between the lines with sentiment analysis to gain a deeper understanding.

<a href="http://blog.bazaarvoice.com/2013/05/20/age-expertise-and-gender-noticably-affect-sentiment/" target="_blank" title="Bazaarvoice Blog">Originally published on the Bazaarvoice Blog</a>
