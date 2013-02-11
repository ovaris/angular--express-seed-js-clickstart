# Welcome to AngularJS on CloudBees

This is a "ClickStart" that gets you going with the AngularJS "seed" project starting point. You can launch it here: 

<a href="https://grandcentral.cloudbees.com/?CB_clickstart=https://raw.github.com/CloudBees-community/angular-js-clickstart/master/clickstart.json"><img src="https://d3ko533tu1ozfq.cloudfront.net/clickstart/deployInstantly.png"/></a>

This will setup a continuous deployment pipeline - a Jenkins build running the test suite (on each commit) with Chrome and Firefox.
Should it pass the tests, this seed app is deployed served up from a tiny node.js server (you 
can then clone and mess with it, or change the backend to what you need). 

AngularJS home page is [Here](http://angularjs.org/)

The Angular-seed project is [here](https://github.com/angular/angular-seed)

When you run this clickstart - you will have the latest version of the seed project running. You can then clone the repo that CloudBees creates for you, make your changes, and when you push back to git it will run the test suite, and deploy the app if all tests pass.

