---
swagger: "2.0"
x-collection-name: Fitbit
x-complete: 0
info:
  title: Fitbit Get User Devices.json
  description: Retrieve the list of Fitbit devices for a user in the format requested.
  version: 1.0.0
host: api.fitbit.com
basePath: /1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /user/-/devices.json:
    get:
      summary: Get User Devices.json
      description: Retrieve the list of Fitbit devices for a user in the format requested.
      operationId: getUserDevices.json
      x-api-path-slug: userdevices-json-get
      responses:
        200:
          description: OK
      tags:
      - User
      - '-'
      - Devices.json
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