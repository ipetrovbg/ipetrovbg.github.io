##  Services Usage

```js
;(function(){
  app.controller('MyController', ['notify', function (notify) {
    var msg = "AngularJS is awesome!!!";
    notify.make(msg);
  }]);
}());
```
