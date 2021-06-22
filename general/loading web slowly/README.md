#### Background
As a beta offering for our product, we are trying out a new third-party recommendation service to help suggest a next action for users. We surface those next actions as part of the user's landing page when they sign in – maybe it's sending an important message, checking off an important todo, etc.

You're settling in at your desk after a delicious and energizing team lunch when you receive a performance alert from the monitoring system. Rendering the beta landing page for a user is averaging around 10 seconds, up from the normal average of ~800ms.

About 10% of the users in the beta are even seeing the dreaded 504 Gateway Timeout error. The beta users represent a small subset of the overall traffic, but this is something that we'd like to understand and fix in the next few days.
No changes have been deployed to the frontend that powers the recommendation service in several weeks.

![image](https://github.com/taixingbi/interview-question/blob/master/general/loading%20web%20slowly/2.png)
![image](https://github.com/taixingbi/interview-question/blob/master/general/loading%20web%20slowly/3.png)

#### anwser
* beta landing page for a user is averaging around 10 seconds [2][3]
1. Unoptimized Images. A **large volume of unoptimized images** is usually the most common reason behind website slowness. High-resolution images can consume lots of bandwidth while loading. Uploading larger sized images and then scaling them down can unnecessarily increase the size of your web page – causing your website to load slowly.  
* Check the file size of your images, anything **above 1MB** is really unacceptable.
* Use **JPEG instead of PNG**, especially for larger images. Icons are ok.
* Use **waterfall tests** to easily scan image sizes and take corrective action.
* Unoptimized images can cost you money in form of **bandwidth overage**.

2. JavaScript Issues
The availability of JavaScript/jQuery plugins has made it really convenient to add dynamic content to websites. However, if implemented incorrectly, JavaScript can cripple your website’s page load speed.
It takes time for jQuery & JavaScript to be loaded, interpreted and executed. So if you are using **multiple API calls** to render JavaScript/jQuery data, it can result in significant delay while loading the web pages.


3. Too Much Flash Content
Although Flash is a great tool for adding interactivity to your website, it is highly likely contributing to your slow page load speed. Flash content is usually **bulky in size and the bigger the file size** is, the slower your pages will load.

* Flash is very **bulky** and is not good for performance.
* Flash used to be cool. It’s not anymore.
* Look for **HTML5 replacements**.

4. Excessive HTTP Requests
Having loads of JavaScript, CSS, and image files can lead to too many HTTP requests. When a user visits your web page, the browser performs several requests to load each of these files – which can significantly reduce the page load speed.

* Use Sprites to reduce HTTP requests.
* Reduce the number of files on your pages where possible. Includes CSS, images, javascript.
* Minify your CSS and Javascript files reduces # of total files users will have to download.

5. Not Making Use of Caching Techniques
Caching is known to improve the performance of websites by leaps and bounds. If you’re not caching, you’re missing out. It’s a technique that let’s you store frequently used data points in the ‘cached memory’.

* Caching drastically improves performance.
* You can cache a bunch of things from HTTP, Database Queries, to images.
* If you can cache something, do it. But do it carefully so you don’t mess something up. It can be tricky.

6. Unclean Code
Another common culprit for website slowness is unclean coding. When you make your website, excessive white spaces, inline stylings, empty new lines and unnecessary comments can make the website stylesheet grow larger in size.
* Attention to detail matters.
* Don’t be lazy and use **inline CSS**
* Try not to create **multiple CSS stylesheets** when you can use a single one.
Minify!



#### reference
[1] https://dev.to/yeahch/brainstorm-problem-i-faced-during-technical-interview-3mgf          
[2] https://www.hobo-web.co.uk/your-website-design-should-load-in-4-seconds/      
**[3] https://www.eurovps.com/blog/reasons-for-slow-website-loading/#:~:text=A%20large%20volume%20of%20unoptimized,your%20website%20to%20load%20slowly.**
