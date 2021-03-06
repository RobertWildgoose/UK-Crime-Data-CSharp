# UK Police Data Library C#

> This library provides content from UKPolice api covering crime over the UK


## Table of Contents

- [Installation](#installation)
- [FAQ](#faq)
- [License](#license)

- **[MIT license](http://opensource.org/licenses/mit-license.php)**

![UK Crime Data](https://github.com/RobertWildgoose/UKCrimeData/workflows/UK%20Crime%20Data/badge.svg?branch=master)
---

## Installation

- Simply pull this repo down and add the project into your projects solution.
- Once included their are several calls you can make  which are shown below.

## FAQ

- **How do I get a every police force**
```c#
var AllPoliceForces = CrimeService.GetAllForces();
```

- **How do I get a more info on a certain police force ie Wiltshire Police**
```c#
var PoliceForce = CrimeService.GetSingleForces("wiltshire");
```

- **How do I get all crimes for a certain date in a certain location**
```c#
var Crimes = CrimeService.GetAllCrimesByPoint("52.9534161", "-1.1492773","2018-10");
```
---

## License

[![License](http://img.shields.io/:license-mit-blue.svg?style=flat-square)](http://badges.mit-license.org)

- **[MIT license](http://opensource.org/licenses/mit-license.php)**
- Copyright 2018 © <a href="http://www.robertwildgoose.co.uk" target="_blank">Robert Wildgoose</a>.
