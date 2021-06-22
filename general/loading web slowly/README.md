#### Background
As a beta offering for our product, we are trying out a new third-party recommendation service to help suggest a next action for users. We surface those next actions as part of the user's landing page when they sign in – maybe it's sending an important message, checking off an important todo, etc.

You're settling in at your desk after a delicious and energizing team lunch when you receive a performance alert from the monitoring system. Rendering the beta landing page for a user is averaging around 10 seconds, up from the normal average of ~800ms.

About 10% of the users in the beta are even seeing the dreaded 504 Gateway Timeout error. The beta users represent a small subset of the overall traffic, but this is something that we'd like to understand and fix in the next few days.
No changes have been deployed to the frontend that powers the recommendation service in several weeks.

![image](https://github.com/taixingbi/interview-question/blob/master/general/loading%20web%20slowly/2.png)
![image](https://github.com/taixingbi/interview-question/blob/master/general/loading%20web%20slowly/3.png)

#### anwser
* beta landing page for a user is averaging around 10 seconds
1. In short, your website should load as fast as possible!
2. Ideal website load time for mobile sites is 1-2 seconds.
3. 53% of mobile site visits are abandoned if pages take longer than 3 seconds to load.
4. A 2-second delay in load time resulted in abandonment rates of up to 87%.
5. Google itself aims for under half-a-second load time
6. A VERY SLOW SITE can be a NEGATIVE Google Ranking factor.
7. The average load time for mobile sites is **19 seconds over 3G connections**. Models predict that publishers whose mobile sites load in 5 seconds earn up to 2x more 8. mobile ad revenue than those whose sites load in 19 seconds.
9. People would not return to websites that took longer than four seconds to load and formed a “negative perception” of a company with a badly put-together site or 10. would tell their family and friends about their experiences.
11. Slow load times are a primary reason visitors abandon a checkout process.
12. In studies, Page Time Load goes from 1s to 3s – the probability of bounce increases 32%.
13. In studies, Page Time Load goes from 1s to 5s – the probability of bounce increases 90%.
14. In studies, Page Time Load goes from 1s to 6s – the probability of bounce increases 106%.
15. In studies, Page Time Load goes from 1s to 10s – the probability of bounce increases 123%.
16. In a recent study, the average load time for a web page was 3.21s.
17. In a recent study, the average load time for a **mobile web page is 22 seconds**.
18. For every 100ms decrease in homepage load speed, a company’s customer base saw a 1.11% lift in session based conversion
Users read fewer articles each day whilst experiencing delays loading each web page. The speed of the site negatively impacts a user’s session depth, no matter how small the delay.
19. Two thirds of UK consumers (67%) cite slow loading times as the main reason they would abandon an online purchase.
20. 47 percent of consumers expect a web page to load in two seconds or less.
21. 40 percent of consumers will wait no more than three seconds for a web page to render before abandoning the site
22. 52 percent of online shoppers stated that quick page loading is important to their site loyalty.
23. Shoppers often become distracted when made to wait for a page to load. 14 percent will begin shopping at another site, and 23 percent will stop shopping or walk away from their computer.
24. Remember to optimise your images – the most important thing you can do to decrease download times. Load background images via external CSS. Minimise white space, line returns and comment tags. Remove unnecessary META tags and META content. Minimise unnecessary javascript and other client-side scripting.  A technical approach to improving user experience, it seems to me, would begin with site speed.
25. A faster site should improve visitor satisfaction levels and the number of conversions.
Google might crawl your site slower if you have a very slow site (confirmed by Google).
26. Retail and travel sites – 79 percent of online shoppers who experience a dissatisfying visit are less likely to buy from that site again. 64 percent would simply purchase from another online store.
26. Automotive retail sites take on average 6 seconds to load.
27. Customer packaged goods sites take on average 6.1 seconds to load.
28. Finance sites take on average 5.1 seconds to load.
29. Healthcare sites take on average 5.6 seconds to load.
30. Media sites take on average 5.5 seconds to load.
31. Retail sites take on average 6 seconds to load.
32. Technology sites take on average 6.8 seconds to load.
33. Travel sites take on average 6.7 seconds to load.
34. Improving your desktop site speed score in isolation of developing a compelling user experience, will not magically lead to BETTER rankings in Google in the short term.
35. Rankings is a nuanced process and there is over 200 signals, but now speed is one of them. Know that ‘content’ and relevance’ are still primary. Website and page load speed may affect Google rankings, just not as much as high quality links, good titles & content that satisfies a search engine visitors’ intent.



#### reference
[1] https://dev.to/yeahch/brainstorm-problem-i-faced-during-technical-interview-3mgf
[2] https://www.hobo-web.co.uk/your-website-design-should-load-in-4-seconds/
