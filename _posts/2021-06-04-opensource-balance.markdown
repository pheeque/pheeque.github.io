---
layout: post
title:  "Open source and timezone balance"
date:   2021-06-04 19:16 +0100
categories: 
---

I just might have struck the right balance for working on open source alongside my regular daily tasks.
While building an integration for a customer, I looked for but could not find a PHP library that would have made the job significantly easier and faster. So what I did was to use the official API to complete the work to not delay delivery further and afterward extract the core of the work as an API library. 

I tagged the first production release and pushed it to Packagist [PHP’s premier package repository] today so others can benefit from the abstraction. I can't wait to see my package in use by others.

The platform I built an API wrapper offers no free plan and since I do not use it daily, I made that known to the support team and they were kind enough to upgrade me so I could continue building my integrations for my clients on their platform. This is similar to the Developer plan Zendesk offers whereby as a developer you get access to all the features across all tiers on Zendesk but cannot use it as a customer.
Going forward, I plan to create an API library for Go which is currently my favorite language, and one for Rails to show my appreciation for the platform’s support.

I have had a lot of success working with clients in time zones close to mine such as in European countries. What I think I need to work on now is finding a way to introduce those not in my timezone such as in the States to asynchronous collaboration methodologies. Let's see how this plays out over the next few weeks.