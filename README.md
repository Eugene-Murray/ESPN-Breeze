ESPN + Breeze
===============
[Patrick Walter](https://github.com/PWKad/)built a "Not My Server" style application that shows Breeze using data from a 3rd party service.

##Prerequisites
1.  Bootsrap.js
2.	Breeze.js
3.	Durandal (jQuery.js, Knockout.js, Require.js) 
4.	q.js
5.	Sammy.js
6.	Toastr.js

##Overview

####A simple app that consumes ESPN's free public API using Breeze.js for client-caching and using Knockout.js for data-binding.

Patrick started this sample to help those looking for help on using Breeze.js with Knockout.js.  The Breeze website has sample using the [Edmunds API and Angular.js](http://www.breezejs.com/samples/edmunds), and Patrick felt that Knockout.js needed its own 3rd-party data sample to make the learning process easier. Durandal’s Starter Kit also includes Twitter Bootstrap for front-end design and Sammy.js for routing. 

##Technologies

In an effort to see how quickly Patrick could create a working sample, he used the [Durandal.js Starter Kit](http://durandaljs.com/pages/downloads/) project.  By starting with this kit he was able to add Breeze.js and get the sample up and running in Visual Studio 2012 in about 10 minutes, as opposed to starting with a blank project, stripping it, setting up views and routes, and everything else that can take additional time.

Key functions in this application include datacontext.js, model.js, and jsonResultsAdapter.js files.  

##What to look for

There are a few cool Breeze things going on in this project I wanted to point out: 

1. Inside App/services/model.js you will find how to add entity types without using MetaData
2. Inside App/services/datacontext.js you will find a few 'gems' -
- How to use 'toType' in your Breeze queries
- How to add parameters onto your queries to an API
- How to add a custom JSON results adapter
3. Inside App/services/jsonResultsAdapter.js you will find a few 'stones' -
- How to create a basic results adapter that Breeze uses when data is returned (when 'toType' isn't enough)
- How to map new properties on top of the data

In addition, there are a few cool Knockout things going on: 

1. The background color for each team is dynamically evaluated
2. The accordion is dynamically created
