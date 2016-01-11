title: Point of Presence Crawler
date: 2016-01-11 09:43:24
tags:
  - CDN
---
## What
This tool finds and locates points of presence of CDNs only using a single machine.

[Source Code](https://github.com/eaufavor/Point-of-Presence-Crawler)

## How
It leverages EDNS0 options to force DNS servers to give away all possible server client mappings.

Currently support
- Google
- Amazon Cloudfront
- maxCDN
- Edgecast


## Demo

- [Google PoPs](/google-pop.html) using 20% public IPs.

- [Amazon Cloudfront](/cloudfront-pop.html) using 25% public IPs.

Here is the locations of Cloudfront PoPs (lower) compared with the map from [cdnplanet](http://www.cdnplanet.com/cdns/cloudfront/) (upper).

![PoPs](/pop.jpg)
