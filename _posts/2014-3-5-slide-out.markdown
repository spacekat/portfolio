---
layout: post
title:  "Slide out panel"
date:   2014-03-05 23:15:42
categories: design, coding
thumbnail: images/slide-out/thumb-slide.jpg
creation-date: 2014-03-05 23:15:42
short-description: Slide-out panel for managing server details
---


I wanted to create a design pattern that could be used for OS Packages and re-used for cluster configuration elements.

### Idea

On the cluster details page, a slide out effect could display the Crons, OS Packages, and SSL certificates.

<img src="{{ site.baseurl}}/images/slide-out/slide-out-action.gif" alt="slide out action" width=800 />

Since this is in an AngularJS app, I used the built in ng-animate properties to create the animation using pure CSS transitions.
