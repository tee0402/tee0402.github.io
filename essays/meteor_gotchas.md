---
layout: essay
type: essay
title: "Meteor gotchas"
date: 2017-10-19
labels:
  - Software Engineering
  - Meteor
---

The Meteor development tools are extremely slow, especially when the application grows in size and complexity. The automatic reloading that Meteor promises to do when you make a change to your project does not always work correctly, so you have to reload the project manually. All this combine to create a really frustrating Meteor experience. The speed of development is much slower than if I simply used a JavaScript framework such as Angular and PHP for server-side code to connect to a database.

The way that Meteor works is also quite convoluted. Not only is it difficult to learn, it is difficult to use. The ideas of imports are nice in theory, but a logistical nightmare to manage in practice. If you miss a single import, the whole application crashes. And it is really easy to miss an import, especially when you have to import every object, function and file that you use. The index.js files are potential solutions to this problem but could make matters worse by becoming very confusing to navigate and distinguish, since they all have the same name and the hierarchy is unclear.
