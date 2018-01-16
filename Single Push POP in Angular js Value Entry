 @foreach (DataRow drV in InvVoucherList.Rows)
                    {
                       
                        <tr>
                            <td class="col-md-1">
                            @if (drV["IsPosted"].ToString() == "1")
                            {
                                <span class="checkbox-custom checkbox-text-dark">
                                       
                                    @*<input type="checkbox" id="isSelect4" name="VoucherList[{{$index}}].isSelect" value="@drV["VoucherId"])"/>*@
                                    <input type="checkbox" value="@drV["VoucherId"]" id="@InvVoucherList.Rows.IndexOf(drV)isSelect4" ng-model="select[@InvVoucherList.Rows.IndexOf(drV)]"  ng-checked="concateVoucher(@drV["VoucherId"],select[@InvVoucherList.Rows.IndexOf(drV)])" name="chkSelect">
                                    <label for="isSelect4"></label>
                                </span>
                                
                            }
}




------- script Code-------

  $scope.VIdList = [];
        $scope.moneyRecpt = function (model) {
            $http.post("../AcmVoucher/RptMoneyReceipt", { chkSelect: $scope.VIdList }).then(function (data) {
               
            });
        }

        $scope.concateVoucher = function (vId, modelName) {
            
            if (modelName == true) {
                if ($scope.VIdList.indexOf(vId) == -1) {
                    $scope.VIdList.push(vId);
                }
            }
            else {
                $scope.VIdList.pop(vId);
            }
           
        }
        
        
