---
swagger: "2.0"
x-collection-name: Microsoft Graph
x-complete: 0
info:
  title: Microsoft Graph Update Open Extension
  description: 'Update open extension Update an open extension (openTypeExtension
    object) with the properties in the request body:'
  version: 1.0.0
host: graph.microsoft.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /users/{id|userPrincipalName}/contacts/{id}/extensions/{extensionId}:
    delete:
      summary: Delete Open Extension
      description: Delete open extension Delete an open extension (openTypeExtension
        object) from the specified instance of a resource.
      operationId: DeleteOpenExtension
      x-api-path-slug: usersiduserprincipalnamecontactsidextensionsextensionid-delete
      parameters:
      - in: header
        name: Authorization
        description: Bearer %token%
      - in: path
        name: extensionId
        type: string
      - in: path
        name: id
        type: string
      - in: path
        name: id|userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Open
      - Extension
    patch:
      summary: Update Open Extension
      description: 'Update open extension Update an open extension (openTypeExtension
        object) with the properties in the request body:'
      operationId: UpdateOpenExtension
      x-api-path-slug: usersiduserprincipalnamecontactsidextensionsextensionid-patch
      parameters:
      - in: header
        name: Authorization
        description: Bearer %token%
      - in: header
        name: Content-Type
        description: application/json
      - in: path
        name: extensionId
        type: string
      - in: path
        name: id
        type: string
      - in: path
        name: id|userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Open
      - Extension
  /users/{id|userPrincipalName}/events/{id}/extensions/{extensionId}:
    delete:
      summary: Delete Open Extension
      description: Delete open extension Delete an open extension (openTypeExtension
        object) from the specified instance of a resource.
      operationId: DeleteOpenExtension
      x-api-path-slug: usersiduserprincipalnameeventsidextensionsextensionid-delete
      parameters:
      - in: header
        name: Authorization
        description: Bearer %token%
      - in: path
        name: extensionId
        type: string
      - in: path
        name: id
        type: string
      - in: path
        name: id|userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Open
      - Extension
    patch:
      summary: Update Open Extension
      description: 'Update open extension Update an open extension (openTypeExtension
        object) with the properties in the request body:'
      operationId: UpdateOpenExtension
      x-api-path-slug: usersiduserprincipalnameeventsidextensionsextensionid-patch
      parameters:
      - in: header
        name: Authorization
        description: Bearer %token%
      - in: header
        name: Content-Type
        description: application/json
      - in: path
        name: extensionId
        type: string
      - in: path
        name: id
        type: string
      - in: path
        name: id|userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Open
      - Extension
  /users/{id|userPrincipalName}/messages/{id}/extensions/{extensionId}:
    delete:
      summary: Delete Open Extension
      description: Delete open extension Delete an open extension (openTypeExtension
        object) from the specified instance of a resource.
      operationId: DeleteOpenExtension
      x-api-path-slug: usersiduserprincipalnamemessagesidextensionsextensionid-delete
      parameters:
      - in: header
        name: Authorization
        description: Bearer %token%
      - in: path
        name: extensionId
        type: string
      - in: path
        name: id
        type: string
      - in: path
        name: id|userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Open
      - Extension
    patch:
      summary: Update Open Extension
      description: 'Update open extension Update an open extension (openTypeExtension
        object) with the properties in the request body:'
      operationId: UpdateOpenExtension
      x-api-path-slug: usersiduserprincipalnamemessagesidextensionsextensionid-patch
      parameters:
      - in: header
        name: Authorization
        description: Bearer %token%
      - in: header
        name: Content-Type
        description: application/json
      - in: path
        name: extensionId
        type: string
      - in: path
        name: id
        type: string
      - in: path
        name: id|userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Open
      - Extension
  /groups/{id}/events/{id}/extensions/{extensionId}:
    delete:
      summary: Delete Open Extension
      description: Delete open extension Delete an open extension (openTypeExtension
        object) from the specified instance of a resource.
      operationId: DeleteOpenExtension
      x-api-path-slug: groupsideventsidextensionsextensionid-delete
      parameters:
      - in: header
        name: Authorization
        description: Bearer %token%
      - in: path
        name: extensionId
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Open
      - Extension
    patch:
      summary: Update Open Extension
      description: 'Update open extension Update an open extension (openTypeExtension
        object) with the properties in the request body:'
      operationId: UpdateOpenExtension
      x-api-path-slug: groupsideventsidextensionsextensionid-patch
      parameters:
      - in: header
        name: Authorization
        description: Bearer %token%
      - in: header
        name: Content-Type
        description: application/json
      - in: path
        name: extensionId
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Open
      - Extension
  /groups/{id}/threads/{id}/posts/{id}/extensions/{extensionId}:
    delete:
      summary: Delete Open Extension
      description: Delete open extension Delete an open extension (openTypeExtension
        object) from the specified instance of a resource.
      operationId: DeleteOpenExtension
      x-api-path-slug: groupsidthreadsidpostsidextensionsextensionid-delete
      parameters:
      - in: header
        name: Authorization
        description: Bearer %token%
      - in: path
        name: extensionId
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Open
      - Extension
    patch:
      summary: Update Open Extension
      description: 'Update open extension Update an open extension (openTypeExtension
        object) with the properties in the request body:'
      operationId: UpdateOpenExtension
      x-api-path-slug: groupsidthreadsidpostsidextensionsextensionid-patch
      parameters:
      - in: header
        name: Authorization
        description: Bearer %token%
      - in: header
        name: Content-Type
        description: application/json
      - in: path
        name: extensionId
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Open
      - Extension
  /users/{Id|userPrincipalName}/messages/{Id}/extensions/{extensionId}:
    get:
      summary: Get Open Extension
      description: Get open extension Get an open extension (openTypeExtension object)
        identified by name or fully qualified name.
      operationId: GetOpenExtension
      x-api-path-slug: usersiduserprincipalnamemessagesidextensionsextensionid-get
      parameters:
      - in: header
        name: Authorization
        description: Bearer %token%
      - in: path
        name: extensionId
        type: string
      - in: path
        name: Id
        type: string
      - in: path
        name: Id|userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Open
      - Extension
  /users/{Id|userPrincipalName}/events/{Id}/extensions/{extensionId}:
    get:
      summary: Get Open Extension
      description: Get open extension Get an open extension (openTypeExtension object)
        identified by name or fully qualified name.
      operationId: GetOpenExtension
      x-api-path-slug: usersiduserprincipalnameeventsidextensionsextensionid-get
      parameters:
      - in: header
        name: Authorization
        description: Bearer %token%
      - in: path
        name: extensionId
        type: string
      - in: path
        name: Id
        type: string
      - in: path
        name: Id|userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Open
      - Extension
  /users/{Id|userPrincipalName}/contacts/{Id}/extensions/{extensionId}:
    get:
      summary: Get Open Extension
      description: Get open extension Get an open extension (openTypeExtension object)
        identified by name or fully qualified name.
      operationId: GetOpenExtension
      x-api-path-slug: usersiduserprincipalnamecontactsidextensionsextensionid-get
      parameters:
      - in: header
        name: Authorization
        description: Bearer %token%
      - in: path
        name: extensionId
        type: string
      - in: path
        name: Id
        type: string
      - in: path
        name: Id|userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Open
      - Extension
  /groups/{Id}/events/{Id}/extensions/{extensionId}:
    get:
      summary: Get Open Extension
      description: Get open extension Get an open extension (openTypeExtension object)
        identified by name or fully qualified name.
      operationId: GetOpenExtension
      x-api-path-slug: groupsideventsidextensionsextensionid-get
      parameters:
      - in: header
        name: Authorization
        description: Bearer %token%
      - in: path
        name: extensionId
        type: string
      - in: path
        name: Id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Open
      - Extension
  /groups/{Id}/threads/{Id}/posts/{Id}/extensions/{extensionId}:
    get:
      summary: Get Open Extension
      description: Get open extension Get an open extension (openTypeExtension object)
        identified by name or fully qualified name.
      operationId: GetOpenExtension
      x-api-path-slug: groupsidthreadsidpostsidextensionsextensionid-get
      parameters:
      - in: header
        name: Authorization
        description: Bearer %token%
      - in: path
        name: extensionId
        type: string
      - in: path
        name: Id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Open
      - Extension
  /users/{Id|userPrincipalName}/messages:
    get:
      summary: Get Open Extension
      description: Get open extension Get an open extension (openTypeExtension object)
        identified by name or fully qualified name.
      operationId: GetOpenExtension
      x-api-path-slug: usersiduserprincipalnamemessages-get
      parameters:
      - in: query
        name: $expand
        type: string
      - in: query
        name: $filter
        type: string
      - in: header
        name: Authorization
        description: Bearer
      - in: path
        name: id|userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Open
      - Extension
  /users/{Id|userPrincipalName}/events:
    get:
      summary: Get Open Extension
      description: Get open extension Get an open extension (openTypeExtension object)
        identified by name or fully qualified name.
      operationId: GetOpenExtension
      x-api-path-slug: usersiduserprincipalnameevents-get
      parameters:
      - in: query
        name: $expand
        type: string
      - in: query
        name: $filter
        type: string
      - in: header
        name: Authorization
        description: Bearer
      - in: path
        name: id|userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Open
      - Extension
  /users/{Id|userPrincipalName}/contacts:
    get:
      summary: Get Open Extension
      description: Get open extension Get an open extension (openTypeExtension object)
        identified by name or fully qualified name.
      operationId: GetOpenExtension
      x-api-path-slug: usersiduserprincipalnamecontacts-get
      parameters:
      - in: query
        name: $expand
        type: string
      - in: query
        name: $filter
        type: string
      - in: header
        name: Authorization
        description: Bearer
      - in: path
        name: id|userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Open
      - Extension
  /users/{id|userPrincipalName}/contacts/{id}/extensions:
    post:
      summary: Create Open Extension
      description: Create open extension Create an open extension (openTypeExtension
        object) and add custom properties in a new or existing instance of a resource.
      operationId: CreateOpenExtension
      x-api-path-slug: usersiduserprincipalnamecontactsidextensions-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer %token%
      - in: header
        name: Content-Type
        description: application/json
      - in: path
        name: id
        type: string
      - in: path
        name: id|userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Open
      - Extension
  /users/{id|userPrincipalName}/events/{id}/extensions:
    post:
      summary: Create Open Extension
      description: Create open extension Create an open extension (openTypeExtension
        object) and add custom properties in a new or existing instance of a resource.
      operationId: CreateOpenExtension
      x-api-path-slug: usersiduserprincipalnameeventsidextensions-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer %token%
      - in: header
        name: Content-Type
        description: application/json
      - in: path
        name: id
        type: string
      - in: path
        name: id|userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Open
      - Extension
  /users/{id|userPrincipalName}/messages/{id}/extensions:
    post:
      summary: Create Open Extension
      description: Create open extension Create an open extension (openTypeExtension
        object) and add custom properties in a new or existing instance of a resource.
      operationId: CreateOpenExtension
      x-api-path-slug: usersiduserprincipalnamemessagesidextensions-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer %token%
      - in: header
        name: Content-Type
        description: application/json
      - in: path
        name: id
        type: string
      - in: path
        name: id|userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Open
      - Extension
  /groups/{id}/events/{id}/extensions:
    post:
      summary: Create Open Extension
      description: Create open extension Create an open extension (openTypeExtension
        object) and add custom properties in a new or existing instance of a resource.
      operationId: CreateOpenExtension
      x-api-path-slug: groupsideventsidextensions-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer %token%
      - in: header
        name: Content-Type
        description: application/json
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Open
      - Extension
  /groups/{id}/threads/{id}/posts/{id}/extensions:
    post:
      summary: Create Open Extension
      description: Create open extension Create an open extension (openTypeExtension
        object) and add custom properties in a new or existing instance of a resource.
      operationId: CreateOpenExtension
      x-api-path-slug: groupsidthreadsidpostsidextensions-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer %token%
      - in: header
        name: Content-Type
        description: application/json
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Open
      - Extension
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