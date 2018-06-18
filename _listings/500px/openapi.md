---
swagger: "2.0"
x-collection-name: 500px
x-complete: 1
info:
  title: 500px
  description: 500px-is-a-photo-community-powered-by-creative-people-worldwide-that-lets-you-discover-share-buy-and-sell-inspiring-photographs-
  version: v1
host: api.500px.com
basePath: /v1/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /photos/:id/favorites:
    get:
      summary: Get Photos Favorites
      description: Returns all users that had favorite that photo.
      operationId: getPhotosFavorites
      x-api-path-slug: photosidfavorites-get
      parameters:
      - in: query
        name: page
        description: Return a specific page in the photo stream
      - in: query
        name: rpp
        description: The number of results to return
      responses:
        200:
          description: OK
      tags:
      - Photos
      - Favorites
---