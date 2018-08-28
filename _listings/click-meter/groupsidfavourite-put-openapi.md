---
swagger: "2.0"
x-collection-name: Click Meter
x-complete: 0
info:
  title: Click Meter Fast switch the "favourite" field of a group
  description: Fast switch the "favourite" field of a group.
  contact:
    name: Api Support
    url: http://www.clickmeter.com/api
    email: api@clickmeter.com
  version: v2
host: apiv2.clickmeter.com:80
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /datapoints/{id}/favourite:
    put:
      summary: Fast switch the "favourite" field of a datapoint
      description: Fast switch the "favourite" field of a datapoint.
      operationId: putDatapointsFavourite
      x-api-path-slug: datapointsidfavourite-put
      parameters:
      - in: path
        name: id
        description: Id of the datapoint
      responses:
        200:
          description: OK
      tags:
      - Datapoints
      - Id
      - Favourite
  /groups/{id}/favourite:
    put:
      summary: Fast switch the "favourite" field of a group
      description: Fast switch the "favourite" field of a group.
      operationId: putGroupsFavourite
      x-api-path-slug: groupsidfavourite-put
      parameters:
      - in: path
        name: id
        description: Id of the group
      responses:
        200:
          description: OK
      tags:
      - Groups
      - Id
      - Favourite
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