---
name: Yahoo
x-slug: yahoo
description: News, email and search are just the beginning. Discover more every day.
  Find your yodel.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/201-yahoo.jpg
x-kinRank: "9"
x-alexaRank: "7"
tags: Yahoo
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/yahoo/master/_listings/yahoo/apis.md
specificationVersion: "0.14"
apis:
- name: 'Yahoo Weather '
  x-api-slug: yahoo-weather
  description: Retrieves weather information for a location.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/201-yahoo.jpg
  humanURL: http://www.yahoo.com
  baseURL: https://weather.yahooapis.com////forecastrss
  tags: ~
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/yahoo/master/_listings/yahoo/forecastrss-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/yahoo/master/_listings/yahoo/forecastrss-get-openapi.md
- name: Yahoo Weather
  x-api-slug: yahoo-weather
  description: The Weather RSS feed enables you to get up-to-date weather information
    for your location. You can save this feed in My Yahoo! or your favorite feed aggregator,
    or incorporate the RSS data into your own web site or client application. The
    Weather RSS feed is a dynamically-generated feed based on WOEID.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/201-yahoo.jpg
  humanURL: http://www.yahoo.com
  baseURL: https://weather.yahooapis.com//
  tags: Yahoo
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/yahoo/master/_listings/yahoo/openapi.md
x-common:
- type: x-website
  url: http://www.yahoo.com
- type: x-advertising
  url: https://developer.yahoo.com/everything.html#groupAdvertise
- type: x-application-management
  url: https://developer.apps.yahoo.com/
- type: x-blog
  url: http://yahoodevelopers.tumblr.com/
- type: x-blog-rss
  url: http://yahoodevelopers.tumblr.com/rss
- type: x-crunchbase
  url: http://www.crunchbase.com/company/yahoo
- type: x-crunchbase
  url: https://crunchbase.com/organization/yahoo
- type: x-forum
  url: https://developer.yahoo.com/forums/
- type: x-github
  url: https://github.com/yahoo
- type: x-jobs
  url: http://yhoo.it/1iLIFlr
- type: x-monetization
  url: https://developer.yahoo.com/everything.html#groupEarn
- type: x-privacy
  url: https://info.yahoo.com/privacy/us/yahoo/devel/details.html
- type: x-selfservice-registration
  url: https://login.yahoo.com/config/login?.done=https://developer.yahoo.com/
- type: x-terms-of-service
  url: https://info.yahoo.com/legal/us/yahoo/api/api-2140.html
- type: x-transparency-report
  url: https://transparency.yahoo.com/
- type: x-twitter
  url: https://twitter.com/Yahoo
- type: x-website
  url: https://developer.yahoo.com/
- type: x-website
  url: http://tumblr.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---