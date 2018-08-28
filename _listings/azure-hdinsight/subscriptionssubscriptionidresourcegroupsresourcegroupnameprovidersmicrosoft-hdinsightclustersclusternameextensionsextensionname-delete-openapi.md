---
swagger: "2.0"
x-collection-name: Azure HDInsight
x-complete: 0
info:
  title: Azure HDInsight API Extension Delete
  description: Delete extension for HDInsight cluster.
  version: 1.0.0
host: management.azure.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.HDInsight/clusters/{clusterName}/extensions/{extensionName}
  : put:
      summary: Extension Create
      description: Create HDInsight cluster extension.
      operationId: Extension_Create
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-hdinsightclustersclusternameextensionsextensionname-put
      parameters:
      - in: path
        name: clusterName
        description: The name of the cluster
      - in: path
        name: extensionName
        description: The name of the cluster extension
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: The cluster extensions create request
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      responses:
        200:
          description: OK
      tags:
      - Extension
    get:
      summary: Extension Get
      description: Get extension properties for HDInsight cluster extension.
      operationId: Extension_Get
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-hdinsightclustersclusternameextensionsextensionname-get
      parameters:
      - in: path
        name: clusterName
        description: The name of the cluster
      - in: path
        name: extensionName
        description: The name of the cluster extension
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      responses:
        200:
          description: OK
      tags:
      - Extension
    delete:
      summary: Extension Delete
      description: Delete extension for HDInsight cluster.
      operationId: Extension_Delete
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-hdinsightclustersclusternameextensionsextensionname-delete
      parameters:
      - in: path
        name: clusterName
        description: The name of the cluster
      - in: path
        name: extensionName
        description: The name of the cluster extension
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      responses:
        200:
          description: OK
      tags:
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