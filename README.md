*This repository is a mirror of the [component](http://component.io) module [stagas/injectable](http://github.com/stagas/injectable). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/stagas-injectable`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*

# injectable

dependency injection

## example

```js
var injectable = require('injectable');

var context = {
  foo: 'bar'
, hello: 'world'
};

var inject = injectable(context);

inject(function(foo, hello){
  console.log(foo); // 'bar'
  console.log(hello); // 'world'
});
```

## License

MIT
