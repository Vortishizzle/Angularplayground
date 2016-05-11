<!DOCTYPE html>
<html lang="en-US">
<script src="http://ajax.googleapis.com/ajax/libs/angularjs/1.4.8/angular.min.js"></script>
<body>

<div ng-app="">
 	<h1>Hello World</h1>
</div>

<div ng-app="">
<p>My first expression: {{ 5 + 5 }}</p>
</div>

<div ng-app="">
 	<p>Name: <input type="text" ng-model="name"></p>
 	<p ng-bind="name"></p>
</div>

<div ng-app="" ng-init="firstName='John'">

<p>The name is <span ng-bind="firstName"></span></p>

</div>

</body>
</html>