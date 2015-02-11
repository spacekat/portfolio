---
layout: post
title:  "Tailored Audiences"
date:   2014-12-8 23:15:42
categories: design
thumbnail: images/twitter-ta-lists/thumb-ta.jpg
creation-date: 2014-12-8 23:15:42
short-description: A way that advertisers can target their own users
---

One of the most effective ways for advertisers to run campaigns on Twitter is by using "tailored audiences".

Over the past 6 months, I have helped add new self-serve features to make tailored audiences more accessible for small and medium sized businesses, found ways to give more feedback about their status to our advertisers, and helped update the documentation for better support of the features.

This is the workflow for uploading your own list of people to target in an ad. This project was initiated by my coworker [Charles](https://twitter.com/martucci) before I joined the team, but I helped make adjustments and refinements to make the feature more complete. This included updates to form copy, adding file upload validation, adding empty states with product education, adding a save-as-draft exit point from the new campaign form, and adding email notifications to the file upload flow.

<img src="{{ site.baseurl}}/images/twitter-ta-lists/new-ta-list.gif" alt="tailored audience list" width="800">

Here are some sketches from planning the flow of adding a new tailored audience.

<img src="{{ site.baseurl}}/images/twitter-ta-lists/email-flow.jpg" alt="email flow sketch" width="800">

### Empty state

When an advertiser didn't have a tailored audience to target, I explored ways to explain the feature. As one design option, I borrowed the dotted-arrow style that our marketing team uses for product education in our Ads blog posts:

<img src="{{ site.baseurl}}/images/twitter-ta-lists/empty-state.png" alt="empty state blog look" width="800">

But what we ended up using was a more simple option. I created icons to illustrate the three types of tailored audiences. I worked with product marketing to standardize a more natural way to describe the tailored audience types, "tailored audiences from web", "tailored audiences from lists", and "tailored audiences from mobile apps".

<img src="{{ site.baseurl}}/images/twitter-ta-lists/01-campaign-form-ta.png" alt="empty state blog look" width="800">

Because creating a new tailored audience would take an advertiser out of their campaign creation flow, I worked with an engineer to implement "save as draft" when someone left to make their first.

<img src="{{ site.baseurl}}/images/twitter-ta-lists/01-campaign-form-ta-modal.png" alt="save as draft" width="800">

After a new tailored audience from a list is uploaded, it takes Twitter several hours to process it and find matches. I put a message about this in the modal while the file is uploading, as well as on the audience manager page, which advertisers see immediately after uploading a list.

<img src="{{ site.baseurl}}/images/twitter-ta-lists/email-notification.png" alt="wait for your email" width="800">

In the Advertiser Help Center, I worked with a product specialist to write [tailored audience documentation](https://support.twitter.com/groups/58-advertising/topics/254-targeting/articles/20172017-tailored-audiences) to clarify each type of tailored audience and how to use them.

I continue to support tailored audience projects at Twitter by meeting with sales specialists, researchers, and product managers to discuss product usage and adoption and campaign performance impact.