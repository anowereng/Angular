<script>
    var app = angular.module("myApp", []);
    app.controller("myCntrl", function ($scope, $http) {
        $scope.departments = [];
        $http({
            method: 'GET',
            url: '/Student/GetStudent'
        }).then(function(data) {
            //$scope.Employees = data.data;
            $scope.departments = data.data;
        }, function() {
            alert('Error');
        });
    });
</script>
