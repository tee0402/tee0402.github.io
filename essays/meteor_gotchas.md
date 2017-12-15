---
layout: essay
type: essay
title: "Meteor gotchas"
date: 2017-10-19
labels:
  - Software Engineering
  - Meteor
---

The Meteor development tools are extremely slow, especially when the application grows in size and complexity. The automatic reloading that Meteor promises to do when you make a change to your project does not always work correctly, so you often have to reload the project manually. These combine to create a really frustrating experience. The speed of development is much slower than if I simply used a JavaScript framework such as Angular and PHP for server-side code to connect to a database.

The way that Meteor works is also quite convoluted. Not only is it difficult to learn, it is also difficult to use. The idea of imports is nice in theory, but is a logistical nightmare to manage in practice. Even if you miss a single import, the whole application crashes. And it is really easy to miss an import, especially when you have to import every object, function and file that you are using. The index.js files are potential solutions to this problem, but could make matters worse by becoming very confusing to navigate and distinguish, since they all have the same name and the hierarchy between them is unclear.

The applications that you could make in Meteor are simply not worth the amount of effort and time that you spend to get Meteor working properly and to use it. You can get much better bang for your buck elsewhere. I would not use Meteor for future development unless the Meteor developers at least fix the performance issues.
