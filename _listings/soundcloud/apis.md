---
name: SoundCloud
x-slug: soundcloud
description: SoundCloud is a music and podcast streaming platform that lets you listen
  to millions of songs from around the world, or upload your own. Start listening
  now!
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
x-kinRank: "9"
x-alexaRank: "112"
tags: Favorites
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/favorites/master/_listings/soundcloud/apis.md
specificationVersion: "0.14"
apis:
- name: Sound Cloud Get Users Favorites
  x-api-slug: sound-cloud
  description: Returns a collection of tracks favorited by the user with user id
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////users/{user_id}/favorites.json
  tags: Users,Favorites
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/favorites/master/_listings/soundcloud/usersuser-idfavorites-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/favorites/master/_listings/soundcloud/usersuser-idfavorites-json-get-openapi.md
- name: Sound Cloud Put Users Favorites Track
  x-api-slug: sound-cloud
  description: Adds the given track to the given user's list of favorites.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////users/{user_id}/favorites/{track_id}.json
  tags: Users,Favorites,Track
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/favorites/master/_listings/soundcloud/usersuser-idfavoritestrack-id-json-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/favorites/master/_listings/soundcloud/usersuser-idfavoritestrack-id-json-put-openapi.md
- name: Sound Cloud Delete Users Favorites Track
  x-api-slug: sound-cloud
  description: Deletes the given track from the given user's list of favorites.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////users/{user_id}/favorites/{track_id}.json
  tags: Users,Favorites,Track
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/favorites/master/_listings/soundcloud/usersuser-idfavoritestrack-id-json-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/favorites/master/_listings/soundcloud/usersuser-idfavoritestrack-id-json-delete-openapi.md
- name: Sound Cloud Get Me Favorites
  x-api-slug: sound-cloud
  description: Returns a collection of tracks favorited by the logged-in user
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////me/favorites.json
  tags: Me,Favorites
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/favorites/master/_listings/soundcloud/mefavorites-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/favorites/master/_listings/soundcloud/mefavorites-json-get-openapi.md
- name: Sound Cloud Put Me Favorites Track
  x-api-slug: sound-cloud
  description: Adds the given track to the logged-in user's list of favorites.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////me/favorites/{track_id}.json
  tags: Me,Favorites,Track
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/favorites/master/_listings/soundcloud/mefavoritestrack-id-json-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/favorites/master/_listings/soundcloud/mefavoritestrack-id-json-put-openapi.md
- name: Sound Cloud Delete Me Favorites Track
  x-api-slug: sound-cloud
  description: Deletes the given track from the logged-in user's list of favorites.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////me/favorites/{track_id}.json
  tags: Me,Favorites,Track
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/favorites/master/_listings/soundcloud/mefavoritestrack-id-json-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/favorites/master/_listings/soundcloud/mefavoritestrack-id-json-delete-openapi.md
- name: Sound Cloud Get Users Favorites. Format
  x-api-slug: sound-cloud
  description: Returns a collection of tracks favorited by the user with user id
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////users/{user_id}/favorites.{format}
  tags: Users,Favorites,,Format
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/favorites/master/_listings/soundcloud/usersuser-idfavorites-format-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/favorites/master/_listings/soundcloud/usersuser-idfavorites-format-get-openapi.md
- name: Sound Cloud Put Users Favorites Track . Format
  x-api-slug: sound-cloud
  description: Adds the given track to the given user's list of favorites.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////users/{user_id}/favorites/{track_id}.{format}
  tags: Users,Favorites,Track,,,Format
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/favorites/master/_listings/soundcloud/usersuser-idfavoritestrack-id-format-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/favorites/master/_listings/soundcloud/usersuser-idfavoritestrack-id-format-put-openapi.md
- name: Sound Cloud Delete Users Favorites Track . Format
  x-api-slug: sound-cloud
  description: Deletes the given track from the given user's list of favorites.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////users/{user_id}/favorites/{track_id}.{format}
  tags: Users,Favorites,Track,,,Format
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/favorites/master/_listings/soundcloud/usersuser-idfavoritestrack-id-format-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/favorites/master/_listings/soundcloud/usersuser-idfavoritestrack-id-format-delete-openapi.md
- name: Sound Cloud Get Me Favorites. Format
  x-api-slug: sound-cloud
  description: Returns a collection of tracks favorited by the logged-in user
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////me/favorites.{format}
  tags: Me,Favorites,,Format
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/favorites/master/_listings/soundcloud/mefavorites-format-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/favorites/master/_listings/soundcloud/mefavorites-format-get-openapi.md
- name: Sound Cloud Put Me Favorites Track . Format
  x-api-slug: sound-cloud
  description: Adds the given track to the logged-in user's list of favorites.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////me/favorites/{track_id}.{format}
  tags: Me,Favorites,Track,,,Format
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/favorites/master/_listings/soundcloud/mefavoritestrack-id-format-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/favorites/master/_listings/soundcloud/mefavoritestrack-id-format-put-openapi.md
- name: Sound Cloud Delete Me Favorites Track . Format
  x-api-slug: sound-cloud
  description: Deletes the given track from the logged-in user's list of favorites.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////me/favorites/{track_id}.{format}
  tags: Me,Favorites,Track,,,Format
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/favorites/master/_listings/soundcloud/mefavoritestrack-id-format-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/favorites/master/_listings/soundcloud/mefavoritestrack-id-format-delete-openapi.md
- name: Sound Cloud
  x-api-slug: sound-cloud
  description: SoundCloud is a music and podcast streaming platform that lets you
    listen to millions of songs from around the world, or upload your own. Start listening
    now!
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com//
  tags: Favorites
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/favorites/master/_listings/soundcloud/openapi.md
x-common:
- type: x-base
  url: https://api.soundcloud.com
- type: x-blog
  url: http://blog.soundcloud.com
- type: x-blog-rss
  url: http://blog.soundcloud.com/feed/
- type: x-console
  url: https://developers.soundcloud.com/console
- type: x-crunchbase
  url: https://crunchbase.com/organization/soundcloud
- type: x-crunchbase
  url: http://www.crunchbase.com/company/soundcloud
- type: x-developer
  url: http://developers.soundcloud.com
- type: x-github
  url: https://github.com/soundcloud
- type: x-linkedin
  url: https://www.linkedin.com/company/soundcloud/
- type: x-pricing
  url: https://on.soundcloud.com/
- type: x-privacy
  url: https://soundcloud.com/pages/privacy
- type: x-support
  url: https://soundcloud.com/imprint
- type: x-terms-of-service
  url: https://soundcloud.com/terms-of-use
- type: x-twitter
  url: https://twitter.com/soundcloudapi
- type: x-twitter
  url: https://twitter.com/SoundCloud
- type: x-website
  url: http://soundcloud.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---