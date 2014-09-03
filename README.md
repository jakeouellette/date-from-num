# date-from-num

Return a date from seconds or milliseconds

[![build status](http://img.shields.io/travis/timhudson/date-from-num.svg?style=flat)](http://travis-ci.org/timhudson/date-from-num)

## Example

``` js
var dateFromNum = require('date-from-num')

console.log(dateFromNum(1409759012000))
// Wed Sep 03 2014 08:43:32 GMT-0700 (PDT)

console.log(dateFromNum(1409759012))
// Wed Sep 03 2014 08:43:32 GMT-0700 (PDT)
```

## License

MIT
