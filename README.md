# angular1.6-
angular1.6离线文档


## $scope.$apply()
- 回调函数里执行的方法被不会触发$apply方法。假如当你点击打了比较input select radio等等，触发了模型监控，值也随之更新了。
  此时需要手动调$scope方法，使dom重绘。

