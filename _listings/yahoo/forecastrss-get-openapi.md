---
swagger: "2.0"
x-collection-name: Yahoo
x-complete: 0
info:
  title: 'Yahoo Weather '
  description: Retrieves weather information for a location.
  version: 1.0.0
host: weather.yahooapis.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /forecastrss:
    get:
      summary: ""
      description: Retrieves weather information for a location.
      operationId: Get_weather.get_
      x-api-path-slug: forecastrss-get
      parameters:
      - in: query
        name: u
        description: Units for temperature (case sensitive)
      - in: query
        name: w
        description: The location for the weather forecast as a WOEID, example is
          Palo Alto, CA
      responses:
        200:
          description: OK
      tags:
      - ""
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---