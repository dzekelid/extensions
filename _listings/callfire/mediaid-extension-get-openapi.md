---
swagger: "2.0"
x-collection-name: CallFire
x-complete: 0
info:
  title: Callfire Download media by extension
  description: 'Download a media file. Available types of files: bmp, gif, jpg, m4a,
    mp3, mp4, png, wav. Content type in response depends on ''extension'' parameter,
    e.g. image/jpeg, image/png, audio/mp3, etc'
  termsOfService: https://www.callfire.com/legal/terms
  contact:
    name: CallFire
    url: https://www.callfire.com
    email: support@callfire.com
  version: 1.0.0
host: www.callfire.com
basePath: /v2
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /media/{id}.{extension}:
    get:
      summary: Download media by extension
      description: 'Download a media file. Available types of files: bmp, gif, jpg,
        m4a, mp3, mp4, png, wav. Content type in response depends on ''extension''
        parameter, e.g. image/jpeg, image/png, audio/mp3, etc'
      operationId: getMediaData
      x-api-path-slug: mediaid-extension-get
      parameters:
      - in: path
        name: extension
        description: Media file type
      - in: path
        name: id
        description: An id of a media resource
      responses:
        200:
          description: OK
      tags:
      - Media
      - Extensions
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