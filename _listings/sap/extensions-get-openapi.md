---
swagger: "2.0"
x-collection-name: SAP
x-complete: 0
info:
  title: SAP Manufacturing Network Partner APIs Retrieves all extensions
  description: "Retrieves all the extensions that have been registered with Manufacturing
    Network.  \nThese extensions are developed by Manufacturing Network customers
    or partners to enhance the functionality of the application."
  version: 1.0.0
host: hostname
basePath: /dim/api
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /extensions:
    get:
      summary: Retrieves all extensions
      description: "Retrieves all the extensions that have been registered with Manufacturing
        Network.  \nThese extensions are developed by Manufacturing Network customers
        or partners to enhance the functionality of the application."
      operationId: retrieves-all-the-extensions-that-have-been-registered-with-manufacturing-network--these-extensions-
      x-api-path-slug: extensions-get
      responses:
        200:
          description: Successful response
      tags:
      - Retrieves
      - ""
      - Extensions
  /extensions/available:
    get:
      summary: Retrieves extensions available for use
      description: "Retrieves extensions that can be used during a collaboration.
        \ \nA supplier enables an extension for collaboration by selecting it for
        use in the supplier profile."
      operationId: retrieves-extensions-that-can-be-used-during-a-collaboration--a-supplier-enables-an-extension-for-co
      x-api-path-slug: extensionsavailable-get
      parameters:
      - in: query
        name: organizationIds
        description: The IDs of organizations as collaboration partiesSeparate the
          IDs using commas
      responses:
        200:
          description: Successful response
      tags:
      - Retrieves
      - Extensions
      - Availableuse
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