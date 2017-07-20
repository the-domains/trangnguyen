---
inFeed: true
description: >-
  A modular framework are made of components that can "live” alone or with other
  components. 
dateModified: '2017-07-20T20:35:54.865Z'
datePublished: '2017-07-20T20:35:55.474Z'
title: Creating Modular Frameworks
author: []
publisher: {}
via: {}
sourcePath: _posts/2017-07-20-creating-modular-frameworks.md
hasPage: true
starred: false
datePublishedOriginal: '2017-07-20T20:13:22.780Z'
url: creating-modular-frameworks/index.html
_type: Article

---
# Creating Modular Frameworks

## What is a modular framework?

A modular framework are made of components that can "live" alone or with other components. 

Popular Examples:

* Lightening UI
* Bootstrap

Many companies opt to create their own modular framework because they find UI frameworks to be too cumbersome and can not be easily extended. Basically, the company picks a framework and find that they need special components and/or designs. They start to override the framework code. Many companies end up with a framework that is a cross between the original framework and their own framework (with overrides, CSS craziness, and so on).

## How to create a Modular Framework?

In this article, I will describe how to create a modular framework from a mock up. Ideally, in an agile environment, you would want a sprint 0\. In the sprint 0, the architects, designers, and PM would determine information architecture which would drive the user flows. The user flows drive the page particles (elements and components) in the layout templates. Once these puzzle pieces are determined, the team can create the framework. 

Like most projects, we never have time or we're in too deep into the sprints and/or project timeline to stop. (If you can do a stop for even a sprint, it would be worth it.) Therefore, I have started on the basic level. You have a mock up. Now what?

## Step 1: The Mock Up

I captured this screenshot from bettycrocker.com, a site I worked on. Let's pretend this is the mock up:
![](https://the-grid-user-content.s3-us-west-2.amazonaws.com/97b176a9-81ca-4306-8fb5-55a9314ff3fd.png)

## Step 2: Finding the "Page Particles"

I often reference SMACSS, BEM, and Atomic Design for this part of the process. It is critical to identify an element, component, and page layout templates. Often these page particles will be re-useable and become the basic building blocks for your framework. When I get a new design:

* I break up what is an element, component, and page layout
* I determine what is unique to this project or can be used on other projects
* I determine page layout templatesPurple = ElementYellow = Component
![](https://the-grid-user-content.s3-us-west-2.amazonaws.com/ea276565-5b43-47c7-9e36-f1b9f40c7e1b.png)