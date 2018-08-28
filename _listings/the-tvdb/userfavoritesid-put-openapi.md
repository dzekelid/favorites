---
swagger: "2.0"
x-collection-name: The TVDB
x-complete: 0
info:
  title: The TVDB Put User Favorites
  description: Adds the supplied series ID to the user???s favorite???s list and returns
    the updated list.
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
  /user/favorites/{id}:
    delete:
      summary: Delete User Favorites
      description: Deletes the given series ID from the user???s favorite???s list
        and returns the updated list.
      operationId: user.favorites.id.delete
      x-api-path-slug: userfavoritesid-delete
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Television
      - User
      - Favorites
    put:
      summary: Put User Favorites
      description: Adds the supplied series ID to the user???s favorite???s list and
        returns the updated list.
      operationId: user.favorites.id.put
      x-api-path-slug: userfavoritesid-put
      parameters:
      - in: query
        name: No Name
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