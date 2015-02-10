---
layout: post
title:  "Target Behaviors"
date:   2014-12-16 23:15:42
categories: design
thumbnail: images/behavior-targeting/thumb-behavior-targeting.jpg
creation-date: 2014-12-16 23:15:42
short-description: A reusable component for selecting from a tree
---

I created a new component to use for tree selection in Twitter ads.

### Problem

Twitter Ads wanted to provide the ability for advertisers to target lists of people based on shopping behavior and demographic information. This type of data came from third party sources, and existing workflow for using it was extremenly complicated. 

### Existing workflow

Advertisers had to talk to a representative from a data collection service, establish a relationship with them, and have them submit their desired audience to their Twitter account via an API. The process often took several days.

### My goal

Provide a way for advertisers to target a list of people (provided by a partner) in our app as they set up their campaign.

### How I went about solving this

<span>1. Researched behavior targeting.</span>

What patterns and terms are advertisers familiar with in this space? How do partners organize these lists? How many behaviors we going to show?

<span>2. Evaluated our current UI patterns for tree selection.</span>

Realizing our current UI's limitations, I sketched some possible solutions on the whiteboard.

<span>3. Prototyped a UI for deep tree selection.</span>

Mocked up a click-through of static screens to show how the new selector would behave.

<span>4. Discusses pro's and con's of different solutions with my team.</span>

I didn't want to over-design this feature, and also didn't want to dismiss a solution that would require less engineering. 

<span>5. Created and beta-tested the effectiveness of the solution.</span>

<span>6. Identified ways to improve it and reuse the component.</span>