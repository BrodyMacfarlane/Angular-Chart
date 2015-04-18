#Angular Chart
=====

#This is intended to be a helpful resource for those in DevMountain Immersive 3.  
It would be very much appreciated if you all could help make changes! 

If you would like to make changes to the chart, please make a pull request and write them below, and I will get to adding your requests.

Eventually, I plan to add more features to this chart, when needed, so if there are any requests for things I should add, let me know.  I will make this chart as big as needed.


#Sample list of things needed right now (there's so much more):
* A proper explanation of $http and $q,
* how to set up modules,
* how to set up functions,
* when to use $scope,
* how to connect all of your script with angular,
* how to retrieve data from an API,
* a solid explanation of promises and how their callbacks work,




###Attention: 
I do not claim that all of the information I have on the chart is correct.  If you see something wrong, or that could be phrased more clearly, please report it to the issues section, and I will get to fixing that.  


I hope this chart comes to be a useful tool in our early Angular Development life, and wish you all the best of luck in your applications!






##Make changes below:


####The View:

With Angular, our HTML can do new tricks.  We can communicate with the $scope through
directives that we add to our HTML tags.

see [this site](goo.gl/k7lGdt) for a list of directives.

i.e. ng-click(”funcName()”)
where funcName has been defined on $scope in 
the controller.

Make sure you link your view up with Angular and your controller
ng-app=’’ and ng-controller=’’

Remember to display the data here.

====




####The $scope:

Things are defined here from the controller using $scope.

It is Angulars way of
communicating from the
controller to the view.

We don’t typically touch this since it is already written for us.

====



####The Controller:

The controller is basically 
the bridge 
between the service and $scope (essentially the view).

Here we can define variables that contain content we would like to see in the view.


Be sure to connect your
controller to your service by putting your service’s name in your function’s parameters.

Every time you want to call something from that service, use serviceName.(name of item in service)

Connect your service’s content to your $scope.

====




####The Service:

no info here

====



####API:

no info here

====





###Other stuff you would want in here:












====================