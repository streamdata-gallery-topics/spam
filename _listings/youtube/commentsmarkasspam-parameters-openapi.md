---
swagger: "2.0"
x-collection-name: YouTube
x-complete: 0
info:
  title: Youtube Parameters Comments Mark as SPAM
  description: Parameters comments markasspam
  termsOfService: https://developers.google.com/terms/
  contact:
    name: Google
    url: https://google.com
  version: 1.0.0
host: www.googleapis.com
basePath: /youtube/v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /comments/markAsSpam:
    parameters:
      summary: Parameters Comments Mark as SPAM
      description: Parameters comments markasspam
      operationId: parametersCommentsMarkasspam
      x-api-path-slug: commentsmarkasspam-parameters
      responses:
        200:
          description: OK
      tags:
      - Comments
      - Markasspam
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