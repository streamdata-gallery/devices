---
swagger: "2.0"
info:
  title: AWS Identity and Access Management API Delete Virtual M F A Device
  version: 1.0.0
  description: Deletes a virtual MFA device.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=DeleteVirtualMFADevice:
    get:
      summary: ' Delete Virtual M F A Device '
      description: Deletes a virtual MFA device
      operationId: deleteVirtualMFADevice
      parameters:
      - in: query
        name: SerialNumber
        description: The serial number that uniquely identifies the MFA device
        type: string
      responses:
        200:
          description: OK
      tags:
      - virtual mfa devices
definitions: []
x-collection-name: AWS Identity and Access Management
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