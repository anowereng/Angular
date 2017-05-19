<script>
    var app = angular.module("myApp", []);
    app.controller("myCntrl", function ($scope, $http) {
        $scope.departments = [];
        $http({
            method: 'GET',
            url: '/Student/GetStudent'
        }).then(function(data) {
            $scope.departments = data.data;
        }, function() {
            alert('Error');
        });
        //For Create a new student (HTTP POST)
        $scope.addStudent = function (aStudent) {
            $http.post("/Student/Create", { aStudent }).error(function (responseData) {
                console.log("Error !" + responseData);
            });
        };

    });
</script>
----------------------------------------- GET And POST View --------------------------------------------------------------
<html>
<head>
    <meta name="viewport" content="width=device-width" />
    <title>AngularStudent</title>
    <script src="~/Scripts/angular.js"></script>
</head>
<body ng-app="myApp">
<div ng-controller="myCntrl">
<div class="row" style="margin-top: 50px;">
    <div class="col-md-5">
            <div class="form-horizontal">
                <div class="form-group">
                    @Html.LabelFor(model => model.firstName, htmlAttributes: new { @class = "control-label col-md-2" })
                    <div class="col-md-10">
                       <input type="text" class="form-control" ng-model="aStudent.firstName"/>
                    </div>
                </div>

                <div class="form-group">
                    @Html.LabelFor(model => model.lastName, htmlAttributes: new { @class = "control-label col-md-2" })
                    <div class="col-md-10">
                        <input type="text" class="form-control" ng-model="aStudent.lastName" />
                    </div>
                </div>

                <div class="form-group">
                    @Html.LabelFor(model => model.fathersName, htmlAttributes: new { @class = "control-label col-md-2" })
                    <div class="col-md-10">
                        <input type="text" class="form-control" ng-model="aStudent.fathersName" />
                    </div>
                </div>

                <div class="form-group">
                    @Html.LabelFor(model => model.dtBirth, htmlAttributes: new { @class = "control-label col-md-2" })
                    <div class="col-md-10">
                        <input type="text" class="form-control" ng-model="aStudent.dtBirth" />
                    </div>
                </div>

                <div class="form-group">
                    @Html.LabelFor(model => model.stuMobile, htmlAttributes: new { @class = "control-label col-md-2" })
                    <div class="col-md-10">
                        <input type="text" class="form-control" ng-model="aStudent.stuMobile" />
                    </div>
                </div>


                <div class="form-group">
                    <div class="col-md-offset-2 col-md-10">
                        <input type="submit" value="Create" ng-click="addStudent(aStudent)"class="btn btn-default" />
                    </div>
                </div>
            </div>
        </div>
    <div class="col-md-5">
        <table class="table-bordered table-hover table-responsive">
            <thead>
            <tr>
                <th>#SL.</th>
                <th>First Name</th>
                <th>Last Name</th>
                <th>Fathers Name</th>
                <th>Birth </th>
                <th>Mobile </th>
            </tr>
            </thead>
            <tbody>
            <tr ng-repeat="department in departments">
                <td>{{$index+1}}</td>
                <td>{{department.firstName}}</td>
                <td>{{department.lastName}}</td>
                <td>{{department.fathersName}}</td>
                <td>{{department.dtBirth}}</td>
                <td>{{department.stuMobile}}</td>
            </tr>
            </tbody>
        </table>
    </div>
</div>
</div>
</body>
</html>
