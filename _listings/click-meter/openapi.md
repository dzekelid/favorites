swagger: "2.0"
x-collection-name: Click Meter
x-complete: 1
info:
  title: Click Meter
  description: api-dashboard-for-clickmeter-api
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