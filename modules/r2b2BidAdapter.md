# Overview

```
Module Name: R2B2 Bid Adapter
Module Type: Bidder Adapter
Maintainer: dev@r2b2.cz
```

## Description

Module that integrates R2B2 demand sources. To get your bidder configuration reach out to our account team on partner@r2b2.cz



## Test unit

```javascript
  var adUnits = [
    {
      code: 'test-r2b2',
      mediaTypes: {
        banner: {
          sizes: [[300, 250], [300, 600]],
        }
      },
      bids: [{
        bidder: 'r2b2',
        params: {
            pid: 'selfpromo'
        }
      }]
    }
  ];
```
