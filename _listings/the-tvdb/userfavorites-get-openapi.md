---
swagger: "2.0"
x-collection-name: The TVDB
x-complete: 0
info:
  title: The TVDB Get User Favorites
  description: Returns an array of favorite series for a given user, will be a blank
    array if no favorites exist.
  version: 2.1.2
host: api-dev.thetvdb.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /user/favorites:
    get:
      summary: Get User Favorites
      description: Returns an array of favorite series for a given user, will be a
        blank array if no favorites exist.
      operationId: user.favorites.get
      x-api-path-slug: userfavorites-get
      responses:
        200:
          description: OK
      tags:
      - Television
      - User
      - Favorites
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