# Rolling-Spider

A Meteor wrapper for [node-rolling-spider](https://github.com/voodootikigod/node-rolling-spider) 1.5.0

## Installation

```shell
meteor add anthonny:rolling-spider
```

## Usage

For a full documentation, visit the [node-rolling-spider](https://github.com/voodootikigod/node-rolling-spider) project

```javascript
var rollingSpider = new RollingSpider();

rollingSpider.connect(Meteor.bindEnvironment(function () {
  rollingSpider.setup(Meteor.bindEnvironment(function () {
    rollingSpider.flatTrim();
    rollingSpider.startPing();
    rollingSpider.flatTrim();
  })
});
```

## Credits

Thank @voodootikigod https://github.com/voodootikigo for his really cool library.
