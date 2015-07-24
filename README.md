# featureservice

A little module that extracts every feature from an Esri "geo-service". The real power in this module is it is designed to page over service and extract every single feature no matter what Server version the data are hosted on.

## Installation

```
npm install featureservice
```

## Usage 

```javascript
  var FeatureService = require('featureservice')
  
  // a url to a feature service
  var url = 'http://....../FeatureServer/0'

  var service = new FeatureService(url, options)
```

## Methods

## Todo

* Expose a stream of feature instead of page chuncks
