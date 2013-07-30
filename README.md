BreezeAPIOnlyKO
===============

##Prerequisites : 
1.  Basic understanding of how Knockout.js Data-binding works
2.	Desire to see how quickly Breeze.js can work with Knockout.js to consume an API

##Overview :

####A sample of how to consume ESPN's free public API with Breeze.js and use Knockout.js for data-binding.

I started this sample to help those looking for help on using Breeze.js with Knockout.js.  At the time of creating this sample application, the Breeze website has a sample of using Breeze.js with Angular.js, and I felt that Knockout.js needed its own sample to make the learning process easier.

##Technologies :

In an effort to see how quickly I could create a working sample I decided to use the Durandal.js Starter Kit project.  By starting with this kit I was able to add Breeze.js and get the sample up and running in Visual Studio 2012 within about 10 minutes, as opposed to starting with a blank project, stripping it, setting up views and routes, and everything else that was required which took quite a bit longer (for me).
My recommendation is that if you choose to follow along with this sample and learn how quickly and efficiently you can consume any API using Breeze and create views using Knockout that you take a look at the key functions in this application (the datacontext.js, model.js, and jsonResultsAdapter.js files) and replicate them using whatever editor or technology that you choose and are most familiar with.  I chose Durandal.js because I feel it is offers an excellent starter kit to add on to and create my own look and feel.  Durandal’s Starter Kit also includes Twitter Bootstrap for front-end design and Sammy.js for routing.  This sample only relies upon those only for presentation.

