Node-geolocation
====================

[![NPM](https://nodei.co/npm/node-geolocation.png?downloads=true&downloadRank=true)](https://nodei.co/npm/node-geolocation/)[![NPM](https://nodei.co/npm/node-geolocalisation.png?downloads=true&downloadRank=true)](https://nodei.co/npm/node-geolocalisation/)

How to use google maps knowledge with node.js 
https://www.npmjs.com/package/node-geolocation

## Installation

```
npm install node-geolocation
```
## Usage example

### Minimun to use 
```
var geolocation = require('node-geolocation');
```

### Distance function

```
var distance = geolocation.distanceBetweenTwoCoord('-1,-2','3,4');
```
```
var coord =  geolocation.adressToCoord('Paris, France');
```
```
var distance = geolocation.distanceBetweenTwoAdress('Paris, France','New-York city');
```

## Licence

MIT License. See LICENSE for details.

Enjoy !!!
