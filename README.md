<!DOCTYPE html>
<html>
<script src="http://ajax.googleapis.com/ajax/libs/angularjs/1.4.8/angular.min.js"></script>
<body>

<p>What type of Atheist are you?</p>

<div ng-app="myApp" ng-controller="myCtrl">

First Name: <input type="text" ng-model="firstName" placeholder="John"><br>
Last Name: <input type="text" ng-model="lastName" placeholder="Doe"><br>
Years an Atheist: <input type="text" ng-model="years" placeholder="18-65"><br>
Age: <input type="text" ng-model="age"><br>

<label for="singleSelect"> Single select: </label><br>
    <select name="singleSelect" ng-model="data.singleSelect">
      <option value="1">Option 1</option>
      <option value="2">Option 2</option>
    </select><br>





<br>
Full Name: {{firstName + " " + lastName}}

</div>

<script>
var app = angular.module('myApp', []);
app.controller('myCtrl', function($scope) {
    $scope.firstName= "John";
    $scope.lastName= "Doe";
    $scope.years= "years";
    $scope.age= "age";
});
</script>

</body>
</html>
