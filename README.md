*This repository is a mirror of the [component](http://component.io) module [lvivier/meters](http://github.com/lvivier/meters). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/lvivier-meters`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*

# meters

Converts string distances into meters.

```js
var m = require('meters')
m('1 mile')
// 1609.34
m('5nm')
// 9260
m('1,200 yds')
// 1097.28
m('10cm')
// 0.1
m('6\'8"')
// 2.032
```

## Install

With [component][1] or [npm][2]:

```
$ component install lvivier/meters

$ npm install meters
```

## Usage

### m(str)

Attempts to convert `str` into meters from common units.

[1]:http://github.com/component/component
[2]:http://npmjs.org/
