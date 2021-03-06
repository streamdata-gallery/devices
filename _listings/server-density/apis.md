---
name: Server Density
x-slug: server-density
description: SaaS infrastructure monitoring. Dashboards, graphs and alerts to help
  you improve performance and maintain uptime. Organizer of @humanops
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/475-server-density.jpg
x-kinRank: "7"
x-alexaRank: "209719"
tags: Devices
created: "2018-08-27"
modified: "2018-08-27"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/devices/master/_listings/server-density/apis.md
specificationVersion: "0.14"
apis:
- name: Devices API - Creating a device
  x-api-slug: inventorydevices-
  description: |-
    You can create new devices via the API, useful if you want to automatically provision new devices and start monitoring automatically.
    This API method is used by our Puppet manifest, Chef cookbook and installer shell script to automatically create devices during the agent installation.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/475-server-density.jpg
  humanURL: https://www.serverdensity.com
  baseURL: ://api.serverdensity.io./
  tags: Monitoring, API United Kingdom, SaaS, Technology, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/devices/master/_listings/server-density/inventorydevices--openapi.md
- name: Devices API - Updating a device
  x-api-slug: inventorydevicesdeviceid-
  description: Update a device and the associated metadata.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/475-server-density.jpg
  humanURL: https://www.serverdensity.com
  baseURL: ://api.serverdensity.io./
  tags: Monitoring, API United Kingdom, SaaS, Technology, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/devices/master/_listings/server-density/inventorydevicesdeviceid--openapi.md
- name: Devices API - View device by agent key
  x-api-slug: inventorydevicesagentkeybyagentkey-
  description: View device by agent key.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/475-server-density.jpg
  humanURL: https://www.serverdensity.com
  baseURL: ://api.serverdensity.io./
  tags: Monitoring, API United Kingdom, SaaS, Technology, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/devices/master/_listings/server-density/inventorydevicesagentkeybyagentkey--openapi.md
- name: Service Status API - Listing service alert metrics
  x-api-slug: alertsservice-alerts-json-
  description: Devices and services have different alert metrics which you can configure
    in the ui. The section correspond to the top-level of the alert metric whereas
    field corresponds to the subsection of the given section.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/475-server-density.jpg
  humanURL: https://www.serverdensity.com
  baseURL: ://api.serverdensity.io./
  tags: Monitoring, API United Kingdom, SaaS, Technology, Relative StreamRank, Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/devices/master/_listings/server-density/alertsservice-alerts-json--postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/devices/master/_listings/server-density/alertsservice-alerts-json--openapi.md
- name: Service Status API - Listing service alert metrics
  x-api-slug: alertsservice-alerts-json-
  description: Devices and services have different alert metrics which you can configure
    in the ui. The section correspond to the top-level of the alert metric whereas
    field corresponds to the subsection of the given section.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/475-server-density.jpg
  humanURL: https://www.serverdensity.com
  baseURL: ://api.serverdensity.io./
  tags: Monitoring, API United Kingdom, SaaS, Technology, Relative StreamRank, Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/devices/master/_listings/server-density/alertsservice-alerts-json--postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/devices/master/_listings/server-density/alertsservice-alerts-json--openapi.md
- name: Service Status API - Listing service alert metrics
  x-api-slug: alertsservice-alerts-json-
  description: Devices and services have different alert metrics which you can configure
    in the ui. The section correspond to the top-level of the alert metric whereas
    field corresponds to the subsection of the given section.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/475-server-density.jpg
  humanURL: https://www.serverdensity.com
  baseURL: ://api.serverdensity.io./
  tags: Monitoring, API United Kingdom, SaaS, Technology, Relative StreamRank, Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/devices/master/_listings/server-density/alertsservice-alerts-json--postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/devices/master/_listings/server-density/alertsservice-alerts-json--openapi.md
x-common:
- type: x-website
  url: https://www.serverdensity.com
- type: x-api-gallery
  url: http://sensr.net.api.gallery.streamdata.io
- type: x-api-stack
  url: http://server.density.stack.network
- type: x-blog
  url: http://blog.serverdensity.com/
- type: x-blog-rss
  url: http://feeds.feedburner.com/serverdensity
- type: x-crunchbase
  url: https://crunchbase.com/organization/server-density
- type: x-crunchbase
  url: http://www.crunchbase.com/company/server-density
- type: x-email
  url: hello@serverdensity.com
- type: x-github
  url: https://github.com/serverdensity
- type: x-linkedin
  url: https://www.linkedin.com/company/server-density
- type: x-twitter
  url: https://twitter.com/serverdensity
- type: x-website
  url: http://www.serverdensity.com/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---