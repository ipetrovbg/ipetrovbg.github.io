##  Controller Definition

```js
angular.module('SimpleApp', [])
    .controller('SimpleController', SimpleController);

    SimpleController.$inject = [];
    function SimpleController(){
        var vm = this;
        vm.message = 'AngularJS is awesome!!!';
    };
```
