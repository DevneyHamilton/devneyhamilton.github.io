---
layout: post
title:  "Sassafras Notes"
categories:
---

At [Sassafras Tech Collective][sassafras], I work on a team of highly skilled technologists who are scrappy as hell. We design and build technology for justice and joy, working with NGOs, academics, artists, and beyond. We've built small miracles on tinier budgets, over and over. ([Work with us][sassafras-contact]!)

More on a few favorite experiences:

## TEXERE
Artist [Indira Allegra][indira-allegra] approached Sassafras with concept designs for [TEXERE][texere], an immersive online experience of weaving. Here, people across time and space would weave grief tapestries together. I scoped the tiniest MVP possible, and wrote up a technical plan that Allegra used to secure starter funding. TEXERE continues to grow with Allegra's leadership and vision. Along the way I have held technical strategy and implementation. Building novel tech with an arts budget has been a beautiful, challenging adventure.

What I did:
- acted as solo engineer on team with a PM+UX designer, in close collaboration with Allegra
- held technical strategy in collaborative efforts that secured initial and expansion funding for a novel software concept
- rapid-prototyped and engineered a consistently visually compelling digital tapestry composition from arbitrary image, text, and sound input
- architected to allow digital tapestries to display in real time on personal devices and on unknown gallery hardware
- communicated technical opportunities, choices, trade-offs, and costs to the client so they could make informed decisions

Results:
- launch at Minnesota Street Project and Ford Foundation led to funding for in-progress expansions in Viverse and additional IRL exhibition spaces
- Indira Allegra regularly reports back the deeply meaningful experiences people have with TEXERE

## Digital Privacy Rights Study for Consumer Reports Digital Lab
Consumer Report's brand new Digital Lab needed a citizen science study on whether companies that are 'data brokers' under California law were following the California Consumer Privacy Act. This law requires companies that collect data allow people to opt out of the sale of their personal information. CR was on a deadline to submit a report to the California Attorney General to influence enforcement guidelines, which meant the citizen science volunteers needed to start in a few weeks. And this was the first major initiative for the Lab - its chance to prove itself to CR at large and to funders.

So we needed to facilitate 100s of volunteers making and reporting back on data rights requests to 100s of companies with disparate, slow, broken, and non-existant processes for fulfilling those requests. In other words, we had to build a consistent, _usable_ user experience on top of many inconsistent, less usable user experiences. At the same time we needed to collect data on their experience for analysis to influence California State digital privacy policy.

What I did:
- led technical strategy, study design, and data analysis with implementation and advising support from two coworkers
- launched to 100s of users in 8 weeks to meet the policy deadline
- architected an MVP using CR’s existing website for volunteer intake, SurveyMonkey for data collection, and a Rails backend to serve emails guiding users through a long, often confusing process
- user input in SurveyMonkey both drove the user’s experience (facilitated by emails) and provided the data we needed to analyze
- wrote an algorithm that randomly assigned test cases such that, with an unknown number of total tests, we maximized the number of companies for which we had 3 samples. This supported the data being analyzable.  

Results:
- CR submitted their [white paper][cr-paper] as planned to influence policy
- my coworker adapted the MVP for use in a water quality study
- the Digital Lab has continued and grown as the Innovation Lab at CR

## QuickBooks Integration on Madeline for Seed Commons
Seed Commons is a national network of cooperative loan funds. Madeline was a large, legacy Rails codebase that already supported several complex features like project management and custom forms creation, all governed by a hierarchical organization logic allowing customization. When I joined, a QuickBooks integration to automate interest transactions and ledger creation, with 2-way data syncing, was  missing features, especially lack of support for legacy data. We addressed these issues together as a team, rotating the tech lead role. What I describe below was possible because of my teammate's leadership before me.

What I did as tech lead:  
- Analyzed and simplified the 2-way data sync flow and ledger calculation process to allow editing data in Madeline, support additional transaction types and attributes, sync missing supporting data types, and fix logic problems that were causing 100s of errors.
- Introduced, planned, and built a read-only mode to reduce risk at initial launch and empower end users to decide when to ‘flip the switch’ to full 2-way syncing.
- Worked closely with end users to understand remaining blockers and get them what they needed.
- Led a shockingly smooth, emergency-free launch that automates interest transactions and ledgers for > $5 million in accounting data for a national network of loan funds.

Results:
- The integration has run smoothly since, with a behind the scenes update to meet new QuickBooks requirements.
- The administrative team at Seed Commons could shift their work from data entry to strategy.

[sassafras]: https://www.sassafras.coop
[sassafras-contact]:https://www.sassafras.coop/contact
[indira-allegra]: https://www.indiraallegra.com
[texere]: https://texere.space
[cr-paper]: https://advocacy.consumerreports.org/wp-content/uploads/2020/09/CR_CCPA-Are-Consumers-Digital-Rights-Protected_092020_vf.pdf
