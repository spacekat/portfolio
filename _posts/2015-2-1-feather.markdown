---
layout: post
title:  "Feather"
date:   2015-1-1 23:15:42
categories: design, coding
thumbnail: images/feather/thumb-feather.jpg
creation-date: 2015-1-1 23:15:42
short-description: A library of sharable interface components and styleguide
---

Feather is a project that I am very passionate about.

In my department, it may not fit in with my other feature-driven priorities, but it's something that I make time for because I'm so excited by it's impact on the quality work that we can deliver. Spearheaded by my amazing coworker [Ron](https://twitter.com/ronalddevera), and contributed to by a handful of other designers and front-end developers, it now has hundreds of internal consumers.

<img src="{{ site.baseurl}}/images/feather/going-to-feather.gif" alt="visiting feather docs" width="1000">

### Problem

* There were insconsistencies in the way that our app feels to our advertisers. 

* Code was being duplicated or re-created in a time-intensive way. 

* There was no single source of UI truth.

### How we are addressing it

The #feather project is both a styleguide and a distributed set of version-controlled, standardized, and rigorously tested UI components. Each component is made in the lightest way possible, tested and approved by our design team, and then documented and distributed for all of our Ads apps to use. This technique helps us in so many operational ways:

* Designers are able to prototype without having to run heavy dev environments and navigate large code bases.

* Developers are able to quickly grab the right markup for the mockups that they are developing.

* Design updates can be distributed across many different apps.

* Time is saved because people can stop developing the same things from scratch.

* It's easier for CSS to stay organized.

### Examples of feather documentation

One of the hairiest components to build was, of all things, tables. There are many pages with tabular data in our advertiser dashboards, so tables need to be easy to read, display text and monetary content clearly, and also work well with internationalized content.

My coworker Sterling redesigned our existing tables to have these features. Then I set out to write the table code.

<img src="{{ site.baseurl}}/images/feather/table.jpg" alt="table" width="1000">

<img src="{{ site.baseurl}}/images/feather/sortable-table.jpg" alt="sortable table" width="1000">

After testing the code with edge cases and in the apps it will be used in, I refactored exiting tables to use the new markup.

### Table Before

<img src="{{ site.baseurl}}/images/feather/table-before.jpg" alt="before table" width="1000">

### Table After

<img src="{{ site.baseurl}}/images/feather/table-after.jpg" alt="before after" width="1000">

Other small components, like icons, help cues, and labels, have also been refactored.

### Help cue before

<img src="{{ site.baseurl}}/images/feather/help-cue-before.jpg" alt="before help cue" width="503">

### Help cue after

<img src="{{ site.baseurl}}/images/feather/help-cue-after.jpg" alt="after help cue" width="503">
