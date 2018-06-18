---
swagger: "2.0"
x-collection-name: SoundCloud
x-complete: 0
info:
  title: Sound Cloud Get Me Favorites. Format
  description: Returns a collection of tracks favorited by the logged-in user
  version: 1.0.0
host: api.soundcloud.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /users/{user_id}/favorites.json:
    get:
      summary: Get Users Favorites
      description: Returns a collection of tracks favorited by the user with user
        id
      operationId: getUsersUserFavorites.json
      x-api-path-slug: usersuser-idfavorites-json-get
      parameters:
      - in: query
        name: consumer_key
      responses:
        200:
          description: OK
      tags:
      - Users
      - Favorites
  /users/{user_id}/favorites/{track_id}.json:
    put:
      summary: Put Users Favorites Track
      description: Adds the given track to the given user's list of favorites.
      operationId: putUsersUserFavoritesTrack.json
      x-api-path-slug: usersuser-idfavoritestrack-id-json-put
      responses:
        200:
          description: OK
      tags:
      - Users
      - Favorites
      - Track
    delete:
      summary: Delete Users Favorites Track
      description: Deletes the given track from the given user's list of favorites.
      operationId: deleteUsersUserFavoritesTrack.json
      x-api-path-slug: usersuser-idfavoritestrack-id-json-delete
      responses:
        200:
          description: OK
      tags:
      - Users
      - Favorites
      - Track
  /me/favorites.json:
    get:
      summary: Get Me Favorites
      description: Returns a collection of tracks favorited by the logged-in user
      operationId: getMeFavorites.json
      x-api-path-slug: mefavorites-json-get
      responses:
        200:
          description: OK
      tags:
      - Me
      - Favorites
  /me/favorites/{track_id}.json:
    put:
      summary: Put Me Favorites Track
      description: Adds the given track to the logged-in user's list of favorites.
      operationId: putMeFavoritesTrack.json
      x-api-path-slug: mefavoritestrack-id-json-put
      responses:
        200:
          description: OK
      tags:
      - Me
      - Favorites
      - Track
    delete:
      summary: Delete Me Favorites Track
      description: Deletes the given track from the logged-in user's list of favorites.
      operationId: deleteMeFavoritesTrack.json
      x-api-path-slug: mefavoritestrack-id-json-delete
      responses:
        200:
          description: OK
      tags:
      - Me
      - Favorites
      - Track
  /users/{user_id}/favorites.{format}:
    get:
      summary: Get Users Favorites. Format
      description: Returns a collection of tracks favorited by the user with user
        id
      operationId: getUsersUserFavorites.Format
      x-api-path-slug: usersuser-idfavorites-format-get
      parameters:
      - in: query
        name: consumer_key
        description: Access, host, upload, and comment on audio
      - in: path
        name: user_id
        description: Access, host, upload, and comment on audio
      responses:
        200:
          description: OK
      tags:
      - Users
      - Favorites
      - ""
      - Format
  /users/{user_id}/favorites/{track_id}.{format}:
    put:
      summary: Put Users Favorites Track . Format
      description: Adds the given track to the given user's list of favorites.
      operationId: putUsersUserFavoritesTrack.Format
      x-api-path-slug: usersuser-idfavoritestrack-id-format-put
      parameters:
      - in: path
        name: track_id
        description: Access, host, upload, and comment on audio
      - in: path
        name: user_id
        description: Access, host, upload, and comment on audio
      responses:
        200:
          description: OK
      tags:
      - Users
      - Favorites
      - Track
      - ""
      - ""
      - Format
    delete:
      summary: Delete Users Favorites Track . Format
      description: Deletes the given track from the given user's list of favorites.
      operationId: deleteUsersUserFavoritesTrack.Format
      x-api-path-slug: usersuser-idfavoritestrack-id-format-delete
      parameters:
      - in: path
        name: track_id
        description: Access, host, upload, and comment on audio
      - in: path
        name: user_id
        description: Access, host, upload, and comment on audio
      responses:
        200:
          description: OK
      tags:
      - Users
      - Favorites
      - Track
      - ""
      - ""
      - Format
  /me/favorites.{format}:
    get:
      summary: Get Me Favorites. Format
      description: Returns a collection of tracks favorited by the logged-in user
      operationId: getMeFavorites.Format
      x-api-path-slug: mefavorites-format-get
      responses:
        200:
          description: OK
      tags:
      - Me
      - Favorites
      - ""
      - Format
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