---
swagger: "2.0"
x-collection-name: Vinli
x-complete: 0
info:
  title: Vinli List Dummy Devices
  description: List dummy devices.
  version: 1.0.0
host: events.vin.li
basePath: /api/v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /devices/cf217c2d-df3c-41f7-b610-8bc3e11b4b79/vehicles:
    get:
      summary: List a Device's Vehicles
      description: List a device's vehicles.
      operationId: DevicesCf217c2dDf3c41f7B6108bc3e11b4b79VehiclesGet
      x-api-path-slug: devicescf217c2ddf3c41f7b6108bc3e11b4b79vehicles-get
      parameters:
      - in: header
        name: Accept
      responses:
        200:
          description: OK
      tags:
      - List
      - Devices
      - Vehicles
  /devices:
    get:
      summary: List all devices
      description: List all devices.
      operationId: DevicesGet
      x-api-path-slug: devices-get
      responses:
        200:
          description: OK
      tags:
      - List
      - ""
      - Devices
  /devices/821374c0-d6d8-11e3-9c1a-0800200c9a66/vehicles/_latest:
    get:
      summary: Get Device's Latest Vehicle
      description: Get device's latest vehicle.
      operationId: Devices821374c0D6d811e39c1a0800200c9a66VehiclesLatestGet
      x-api-path-slug: devices821374c0d6d811e39c1a0800200c9a66vehicles-latest-get
      parameters:
      - in: header
        name: Accept
      responses:
        200:
          description: OK
      tags:
      - Devices
      - Latest
      - Vehicle
  /dummies:
    get:
      summary: List Dummy Devices
      description: List dummy devices.
      operationId: DummiesGet
      x-api-path-slug: dummies-get
      parameters:
      - in: header
        name: Accept
      responses:
        200:
          description: OK
      tags:
      - List
      - Dummy
      - Devices
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