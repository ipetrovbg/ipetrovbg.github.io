##  Services Definition

```js
angular.module('myServiceModule', [])
  .factory('notify', notify);

  notify.$inject = ['$window'];

  function notify( win ){
    var service = {
      make: makeNotify
    };

    function makeNotify(msg) {
        win.alert(msg);
      }
    };
    return service;

  }]);
```
