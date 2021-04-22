### [Wordpress: Treat FLoC like a security concern](https://make.wordpress.org/core/2021/04/18/proposal-treat-floc-as-a-security-concern/)
Contrary to headlines, "WordPress" hasn't made any decisions or changes yet with regards to #FLoC. It is more correct to say there is a proposal from a WP contributor to block FLoC by default. [via Matt Mullenweg author of WP](https://twitter.com/photomatt/status/1384197185219170305)

### [Incorrect information about FLoC #Thread](https://twitter.com/Log3overLog2/status/1384337637763387394) 
Wow there is a lot of incorrect information about FLoC out there today!  Many people complaining that it's based on scooping up your data on all sites, which is extremely not true. [more here](https://twitter.com/Log3overLog2/status/1384337637763387394)

### [Short explanation on FLoC Origin Trial](https://twitter.com/rowan_m/status/1383372223017209857)
"A short explanation and link to context for those of you who want the technical details on the FLoC Origin Trial". Also you should follow [Rowan Merewood](https://twitter.com/rowan_m) and [Michael Kleber](https://twitter.com/Log3overLog2)

### [How can FLoC (in Origin Trial now) enable a path off third-party cookies?](https://twitter.com/rowan_m/status/1382720868208500742)
Goals: stop 1:1 tracking, keep personalisation, minimise site disruption. How: drop 1:1 user id cookie Cookie  add 1:many cohort from a FLoC Bird. Result: individual profile not needed, customise to a FLoC instead!

### [EFF: Am I FLoCed?](https://amifloced.org/)
> If you have been assigned a FLoC ID, it means that your browser has processed your browsing history and assigned you to a group of “a few thousand” similar users. The FLoC ID is the label for your behavioral group. This numeric label is not meaningful on its own. However, large advertisers (like Google) and websites (like… Google) will be able to analyze traffic from millions of users to figure out what the members of a particular FLoC have in common. Those actors may use your FLoC ID to infer your interests, demographics, or past behavior.

> To get more technical: your browser uses an algorithm called SimHash to calculate your FLoC ID. The system currently uses the list of domains you’ve visited in the past 7 days as input, and recalculates the FLoC ID once a week. The current version of the trial places each user into one of over 33,000 behavioral groups. You can view the code for the FLoC component here. Google has said that it intends to experiment with different grouping algorithms, and different parameters, throughout the trial.


### [How to fight back against Google FLoC](https://plausible.io/blog/google-floc)
> “All sites with publicly routable IP addresses that the user visits when not in incognito mode will be included in the POC cohort calculation.” Every website and every Chrome user will be opted into FLoC by default without any say in that choice. That is a decision Google has made for us all. There are ways to opt-out for those aware of this issue but we know that defaults matter and that most sites and users will never change the defaults. GDPR is an opt-in law so people need to opt into this type of tracking for advertising purposes and it would be great if Google makes FLoC opt-in rather than opt-out by default.



### [Opting your Website out of Google's FLoC Network (#HowToStepByStep)](https://paramdeo.com/blog/opting-your-website-out-of-googles-floc-network)
> The primary way an end-user can avoid being FLoC’d is to simply not use Chrome, and instead choose a privacy-respecting browser such as Mozilla Firefox. But website owners can also ensure that their web servers are not participating in this massive network by opting-out of FLoC.

### [Your cohorts are just ethnic affinity groups. Change my mind](https://blog.zgp.org/floc-affinity/)

> If we do have an issue where racially specific targeting is incidentally created by the ML system what happens when advertisers target for or against it and who ends up responsible?

> "Your probabilistic ID is just fingerprinting. Change my mind." [(source)](https://twitter.com/slayser8/status/1354485102571614217)


### [Use the DuckDuckGo Extension to Block FLoC, Google’s New Tracking Method in Chrome](https://spreadprivacy.com/block-floc-with-duckduckgo/)

> With FLoC, by simply browsing the web, you are automatically placed into a group based on your browsing history (“cohort”). Websites you visit will immediately be able to access this group FLoC ID and use it to target ads or content at you. It's like walking into a store where they already know all about you! In addition, while FLoC is purported to be more private because it is a group, combined with your IP address (which also gets automatically sent to websites) you can continue to be tracked easily as an individual.

### [Who is sharing data with Google's FLoC ad algorithm?](https://adalytics.io/blog/google-chrome-floc)
"99.99% of websites are not opting out of FLoC. This study analyzed the 100,000 most popular domains according to the Tranco list, which ranks the most popular sites on the internet. Each domain was examined for the presence of a Permission-Policy header. If a domain included such a header, the header contents were checked for the presence of the “interest-cohort=()” flag. The analysis of 100,000 different domains, found that only 10 websites have chosen to opt-out of FLoC via the Permissions-Policy header (as of April 7th, 2021)." more on: 


### [Measuring Sensitivity of Cohorts Generated by the FLoC API](https://docs.google.com/a/google.com/viewer?a=v&pid=sites&srcid=Y2hyb21pdW0ub3JnfGRldnxneDo1Mzg4MjYzOWI2MzU2NDgw)
> It has been shown that the FLoC API allows ad tech companies to enable interest-based advertising without generating fine-grained browsing profiles of users. The FLoC API achieves this by generating k-anonymous cohorts. That is, the API returns a cohort number shared by at least k users. This id can be used as an anonymous replacement of a third-party cookie, allowing ad tech companies to build cohort interest profiles without knowing the identity of a user. While k-anonymity, especially for large values of k, protects users from reidentification, it is well known in the privacy community that this privacy notion can be vulnerable to so-called homogeneity attacks. In the context of the FLoC API, a homogeneity attack corresponds to a scenario where all users that share a cohort number also share a sensitive attribute. For instance, a cohort that consists only of users who visited a website about a rare medical condition. By revealing the cohort of a user, the FLoC API may inadvertently also reveal that a user has investigated that rare medical condition. At a very high level, we want to make sure that no company, including Google, can correlate a
particular cohort with any sensitive attribute.

### [More on Google FLoC](https://www.linkedin.com/posts/eftimiesilviudaniel_silviu-daniel-eftimie-on-linkedin-floc-activity-6784826674560163840-heiC)
[![image01](/floc/images/floc01.png?raw=true)](https://www.linkedin.com/posts/eftimiesilviudaniel_silviu-daniel-eftimie-on-linkedin-floc-activity-6784826674560163840-heiC)

### [I've just gave #FLoC (from The Privacy Sandbox) a spin in Europe.](https://www.linkedin.com/posts/eftimiesilviudaniel_floc-canary-google-activity-6783359006619521024-PGLT))
[![image02](/floc/images/floc02.png?raw=true)](https://www.linkedin.com/posts/eftimiesilviudaniel_floc-canary-google-activity-6783359006619521024-PGLT)

### [Federated Learning (FL)](https://www.linkedin.com/posts/eftimiesilviudaniel_google-privacysandbox-floc-activity-6782994620751085568-C09d)

> Third-party cookies track your activity to match id with relevant content and ads. Let's explore a better way. 

> An approach where you're grouped with thousands of others who browse similar sites. Websites can show you relevant content and ads based on the group's interests, without needing to know the individuals. The group is large enough so you blend in the crowd. Your browsing history doesn't leave your browser or device.

> We call it Federated Learning of Cohorts

[![image03](/floc/images/floc03.png?raw=true)](https://www.linkedin.com/posts/eftimiesilviudaniel_google-privacysandbox-floc-activity-6782994620751085568-C09d)

### [The technology will avoid the privacy risks of third-party cookies, but it will create new ones in the process](https://www.linkedin.com/posts/eftimiesilviudaniel_googles-floc-is-a-terrible-idea-activity-6773259449709682688-DkE5)

[![image04](/floc/images/floc04.png?raw=true)](https://www.linkedin.com/posts/eftimiesilviudaniel_googles-floc-is-a-terrible-idea-activity-6773259449709682688-DkE5)


### [We will not build alternate identifiers to track individuals as they browse across the web](https://www.linkedin.com/posts/eftimiesilviudaniel_charting-a-course-towards-a-more-privacy-first-activity-6772918016297447425-6kDI)
[![image05](/floc/images/floc05.png?raw=true)](https://www.linkedin.com/posts/eftimiesilviudaniel_charting-a-course-towards-a-more-privacy-first-activity-6772918016297447425-6kDI)

### [Competition and Markets Authority to investigate Google’s ‘Privacy Sandbox’ browser changes](https://www.gov.uk/government/news/cma-to-investigate-google-s-privacy-sandbox-browser-changes)

The Competition and Markets Authority in the UK has opened an investigation into FLoC to assess whether it could cause “advertising spend to become even more concentrated on Google’s ecosystem at the expense of its competitors”.
