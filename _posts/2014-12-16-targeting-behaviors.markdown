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

<img src="{{ site.baseurl}}/images/behavior-targeting/behavior-targeting.gif" alt="finishedproduct" width="1000">

### Problem

Twitter Ads wanted to provide the ability for advertisers to target lists of people based on shopping behavior and demographic information. This type of data came from third party sources, and existing workflow for using it was extremenly complicated. 

### Existing workflow

Advertisers had to talk to a representative from a data collection service, establish a relationship with them, and have them submit their desired audience to their Twitter account via an API. The process often took several days.

### My goal

Provide a way for advertisers to target a list of people (provided by a partner) in our app as they set up their campaign.

### How I went about solving this

<span>1. Researched behavior targeting.</span>

What patterns and terms are advertisers familiar with in this space? How do partners organize these lists? How many behaviors we going to show? (A: hundreds!)

<span>2. Evaluated our current UI patterns for tree selection.</span>

![Tree in a modal]({{ site.baseurl}}/images/behavior-targeting/existing-modal-tree.png)

Realizing our current UI's limitations (only has 2 levels, when the lists are long there will be a lot of scrolling), I sketched some possible solutions on the whiteboard.

<span>3. Prototyped a UI for deep tree selection.</span>

Mocked up a click-through of static screens to show how the new selector would behave.

<img src="{{ site.baseurl}}/images/behavior-targeting/tree-in-sheet-flow.jpg" alt="tree in a sheet" width="800">

Due diligence: This is what our existing modal would look like filled with this large tree.

![mocked up 3 level tree]({{ site.baseurl}}/images/behavior-targeting/selection-tree.png)

<span>4. Discussed pro's and con's of different solutions with my team.</span>

I didn't want to over-design this feature, and also didn't want to dismiss a solution that would require less engineering. So sharing them mockups of the tree-in-a-modal solution and also the tree-in-a-sheet solution, I outlined these pro's and con's.

<img src="{{ site.baseurl}}/images/behavior-targeting/prosandcons.png" alt="Pros and Cons" width="800">

<span>5. Created and beta-tested the effectiveness of the solution.</span>

Measured product adoption, gathered empirical feedback, and evaluated the performance of campaigns that used behavior targeting.

<span>6. Identified ways to improve it and reuse the component, and also developed ongoing questions.</span>

As we planned to adding more partners, I shared several options for how this selector could accomodate it.

<img src="{{ site.baseurl}}/images/behavior-targeting/possibility1.png" alt="possibility 1" width="800">
<img src="{{ site.baseurl}}/images/behavior-targeting/possibility2.png" alt="possibility 2" width="800">
<img src="{{ site.baseurl}}/images/behavior-targeting/possibility3.png" alt="possibility 3	" width="800">
<img src="{{ site.baseurl}}/images/behavior-targeting/adding-more-partners.png" alt="adding more partners" width="800">

* One of the things I want to address is how do we encourage adoption for advertisers that are unfamiliar with this type of data?

* My current project, installed app catgegory targeting, will use the same UI componet. Here are the mockups.

<img src="{{ site.baseurl}}/images/behavior-targeting/app-cat-2.png" alt="app cat targeting" width="800">

<img src="{{ site.baseurl}}/images/behavior-targeting/app-cat-3.png" alt="app cat targeting" width="800">

I also want to improve the interactions and empty states.

<img src="{{ site.baseurl}}/images/behavior-targeting/future-plans.jpg" alt="Future plans" width="800">