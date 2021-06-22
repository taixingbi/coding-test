#### Background
As a beta offering for our product, we are trying out a new third-party recommendation service to help suggest a next action for users. We surface those next actions as part of the user's landing page when they sign in – maybe it's sending an important message, checking off an important todo, etc.

You're settling in at your desk after a delicious and energizing team lunch when you receive a performance alert from the monitoring system. Rendering the beta landing page for a user is averaging around 10 seconds, up from the normal average of ~800ms.

About 10% of the users in the beta are even seeing the dreaded 504 Gateway Timeout error. The beta users represent a small subset of the overall traffic, but this is something that we'd like to understand and fix in the next few days.
No changes have been deployed to the frontend that powers the recommendation service in several weeks.

![image](https://github.com/taixingbi/interview-question/blob/master/general/loading%20web%20slowly/2.png)
![image](https://github.com/taixingbi/interview-question/blob/master/general/loading%20web%20slowly/3.png)

#### anwser
* beta landing page for a user is averaging around 10 seconds [2]



#### reference
[1] https://dev.to/yeahch/brainstorm-problem-i-faced-during-technical-interview-3mgf          
[2] https://www.hobo-web.co.uk/your-website-design-should-load-in-4-seconds/
