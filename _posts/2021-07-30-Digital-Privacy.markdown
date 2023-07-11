---
layout: post
title:  "Launching a Citizen Science Platform in 8 Weeks"
categories:
---

## Privacy Rights Study for Consumer Reports Digital Lab
Consumer Report's brand new Digital Lab needed a citizen science study on whether companies that are 'data brokers' under California law were following the California Consumer Privacy Act. This law requires companies that collect data allow people to opt out of the sale of their personal information. CR was on a deadline to submit a report to the California Attorney General to influence enforcement guidelines, which meant the citizen science volunteers needed to start in a few weeks. And this was the first major initiative for the Lab - its chance to prove itself to CR at large and to funders.

So we needed to facilitate 100s of volunteers making and reporting back on data rights requests to 100s of companies with disparate, slow, broken, and non-existant processes for fulfilling those requests. In other words, we had to build a consistent, _usable_ user experience on top of many inconsistent, less usable user experiences. At the same time we needed to collect data on their experience for analysis to influence California State digital privacy policy.

What I did:
- led technical strategy, study design, and data analysis with implementation and advising support from two coworkers at Sassafras
- launched to 100s of users in 8 weeks to meet the policy deadline
- architected an MVP using CR’s existing website for volunteer intake, SurveyMonkey for data collection, and a Rails backend to serve emails guiding users through a long, often confusing process
- user input in SurveyMonkey both drove the user’s experience (facilitated by emails) and provided the data we needed to analyze
- wrote an algorithm that randomly assigned test cases such that, with an unknown number of total tests, we maximized the number of companies for which we had 3 samples. This supported the data being analyzable.  

Results:
- CR submitted their [white paper][cr-paper] as planned to influence policy
- my coworker adapted the MVP for use in a water quality study
- the Digital Lab has continued and grown as the Innovation Lab at CR


[sassafras]: https://www.sassafras.coop
[sassafras-contact]:https://www.sassafras.coop/contact
[indira-allegra]: https://www.indiraallegra.com
[texere]: https://texere.space
[cr-paper]: https://advocacy.consumerreports.org/wp-content/uploads/2020/09/CR_CCPA-Are-Consumers-Digital-Rights-Protected_092020_vf.pdf
[seed-commons]: https://seedcommons.org
