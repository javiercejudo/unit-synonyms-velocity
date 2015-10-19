# unit-synonyms-velocity

[![Build Status](https://travis-ci.org/javiercejudo/unit-synonyms-velocity.svg)](https://travis-ci.org/javiercejudo/unit-synonyms-velocity)
[![Coverage Status](https://coveralls.io/repos/javiercejudo/unit-synonyms-velocity/badge.svg?branch=master)](https://coveralls.io/r/javiercejudo/unit-synonyms-velocity?branch=master)
[![Code Climate](https://codeclimate.com/github/javiercejudo/unit-synonyms-velocity/badges/gpa.svg)](https://codeclimate.com/github/javiercejudo/unit-synonyms-velocity)

Velocity units synonyms

## Install

    npm i unit-synonyms-velocity

## Units

- [Metres per second](https://en.wikipedia.org/wiki/Metre_per_second)
- [Miles per hour](https://en.wikipedia.org/wiki/Miles_per_hour)
- [Feet per second](https://en.wikipedia.org/wiki/Foot_per_second)
- [Kilometres per hour](https://en.wikipedia.org/wiki/Kilometres_per_hour)
- [Knot](https://en.wikipedia.org/wiki/Knot_(unit))

## Usage

```js
var synonyms = require('unit-synonyms-velocity').synonyms;

synonyms['㎧']; // => metresSecond
synonyms['mph']; // => milesHour
synonyms['km/h']; // => kilometresHour
```

## Related projects

- [linear-presets](https://github.com/javiercejudo/linear-presets): linear presets for common units.
- [linear-converter](https://github.com/javiercejudo/linear-converter): flexible linear converter.
