
### Hi there 👋 I'm Chris! Here are some of my projects!
#### 📫 How to reach me: https://www.linkedin.com/in/chris-nakamura/
#### 😄 Pronouns: He/Him
 
[NurseScheduler](https://github.com/chnakamura/NurseScheduler) 
---
Nurse scheduling is a significant pain-point for hospitals. This project implements a generic two-phase stochastic variable neighborhood algorithm developed by researchers at the University of Western Greece to find a near-optimal solution in quadratic time.

You should try forking the repo and customizing  the cost function! I think there could be some interesting results!

**Vaccine Tracker**
---
I noticed my parents were having a lot of trouble finding vaccine appointments, so I created a bot that would text them whenever one was available! I built it using AWS Eventbridge to trigger a Lambda function every minute which makes a request to a local vaccinations site's REST API. Then, if there are appointments available, it triggers an SNS notification that sends them a text message!

[Covid Tracker Tracker](http://covid-tracker-tracker.chrisnakamura.com) 
---
A webapp that tracks how many COVID-19 trackers that are public on Github. 
- A serverless React.js app deployed using AWS S3, API Gateway and Lambda. 
- Uses AWS EventBridge and Lambda to query the Github API once per day, caching the results in a DynamoDB database in order to display results quickly and avoid rate-limiting. 

[PicQuery](https://github.com/chnakamura/picquery) 
---
A webapp that stores and automatically tags users photos for their contents using machine learning with Amazon’s Rekognition engine.
- Deployed to AWS using S3, Lambda, RDS and EC2.

[StegChris](https://github.com/chnakamura/stegchris) 
---
A stenography engine that I implemented without doing any resarch on stenography. 
- This was a very fun challenge!



<!--
**chnakamura/chnakamura** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
