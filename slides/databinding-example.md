###### Controller
```js
angular.module('SimpleApp')
    .controller('SimpleController', SimpleController);

function SimpleController(){
    var vm = this;
    vm.message = "Angular is awesome!!!";
};

```