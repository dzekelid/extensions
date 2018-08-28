swagger: "2.0"
x-collection-name: Azure HDInsight
x-complete: 1
info:
  title: HDInsightManagementClient
  description: the-hdinsight-management-client-
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