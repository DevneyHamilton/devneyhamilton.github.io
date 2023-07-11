---
layout: post
title:  "Integrating Complex Financial Data"
categories:
---

## QuickBooks Integration on Madeline for Seed Commons
[Seed Commons][seed-commons] is a national network of cooperative loan funds. Madeline was a large, legacy Rails codebase that already supported several complex features like project management and custom forms creation, all governed by a hierarchical organization logic allowing customization. When I joined the Sassafras team working on this, a QuickBooks integration to automate interest transactions and ledger creation, with 2-way data syncing, was  missing features, especially lack of support for legacy data. We addressed these issues together as a team, rotating the tech lead role. What I describe below was possible because of my teammate's leadership before me.

What I did as tech lead:  
- Analyzed and simplified the 2-way data sync flow and ledger calculation process to allow editing data in Madeline, support additional transaction types and attributes, sync missing supporting data types, and fix logic problems that were causing 100s of errors.
- Introduced, planned, and built a read-only mode to reduce risk at initial launch and empower end users to decide when to ‘flip the switch’ to full 2-way syncing.
- Worked closely with end users to understand remaining blockers and get them what they needed.
- Led a shockingly smooth, emergency-free launch that automates interest transactions and ledgers for > $5 million in accounting data for a national network of loan funds.

Results:
- The integration has run smoothly since, with a behind the scenes update to meet new QuickBooks requirements.
- The administrative team at Seed Commons could shift their work from data entry to strategy.

[seed-commons]: https://seedcommons.org
