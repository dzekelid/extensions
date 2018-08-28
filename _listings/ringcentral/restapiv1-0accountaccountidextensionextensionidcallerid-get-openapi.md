---
swagger: "2.0"
x-collection-name: RingCentral
x-complete: 0
info:
  title: RingCentral Get Extension Caller ID
  description: |-
    Returns information on an outbound caller ID of an extension.
    App Permission
    ReadAccounts
    User Permission
    ReadCallerIDSettings
    Usage Plan Group
    Light
  version: 1.0.0
host: platform.ringcentral.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /restapi/v1.0/account/{accountId}/extension:
    get:
      summary: Get Extensions
      description: "Returns the list of extensions created for a particular account.
        All types of extensions are included in this list.\nApp Permission\nReadAccounts\nUser
        Permission\nReadExtensions\nUsage Plan Group\nMedium\nError Codes\n\n \n  \n
        \  HTTP Code\n   Error Code\n   Error Message\n   \n \n\n400\nCMN-101\nParameter
        [status] value is invalid\n\n\n401\nCMN-405\nLogin to extension required\n\n\n401\nOAU-151\nAuthorization
        method not supported\n\n\n403\nCMN-401\nIn order to call this API endpoint,
        application needs to have [ReadAccounts] permission\n\n\n404\nCMN-102\nResource
        for parameter [accountId] is not found\n\n\n429\nCMN-301\nRequest rate exceeded"
      operationId: listExtensions
      x-api-path-slug: restapiv1-0accountaccountidextension-get
      parameters:
      - in: path
        name: accountId
        description: Internal identifier of a RingCentral account or tilde (~) to
          indicate the account logged-in within the current session
      - in: query
        name: page
        description: Indicates the page number to retrieve
      - in: query
        name: perPage
        description: Indicates the page size (number of items)
      - in: query
        name: status
        description: Extension current state
      - in: query
        name: type
        description: Extension type
      responses:
        200:
          description: OK
      tags:
      - Extensions
  /restapi/v1.0/account/{accountId}/call-recording/extensions:
    get:
      summary: Get Call Recording Extension Settings
      description: |-
        Returns the list of extensions to be recorded.
        App Permission
        ReadAccounts
        User Permission
        ReadCompanyInfo
        Usage Plan Group
        Medium
      operationId: listCallRecordingExtensionSettings
      x-api-path-slug: restapiv1-0accountaccountidcallrecordingextensions-get
      parameters:
      - in: path
        name: accountId
      responses:
        200:
          description: OK
      tags:
      - Call
      - Recording
      - Extension
      - Settings
  /restapi/v1.0/account/{accountId}/extension/{extensionId}/phone-number:
    get:
      summary: Get Extension Phone Number List
      description: "Returns the list of phone numbers that are used by a particular
        extension, and can be filtered by the phone number type. The returned list
        contains all numbers which are directly mapped to a given extension plus the
        features and also company-level numbers which may be used when performing
        different operations on behalf of this extension.\nApp Permission\nReadAccounts\nUser
        Permission\nReadUserPhoneNumbers\nUsage Plan Group\nLight\nError Codes\n\n
        \n  \n   HTTP Code\n   Error Code\n   Error Message\n   \n \n\n400\nCMN-101\nParameter
        [usageType] value is invalid\n\n\n401\nCMN-405\nLogin to extension required\n\n\n401\nOAU-151\nAuthorization
        method not supported\n\n\n403\nCMN-401\nIn order to call this API endpoint,
        application needs to have [ReadAccounts] permission\n\n\n404\nCMN-102\nResource
        for parameter [extensionId] is not found"
      operationId: listExtensionPhoneNumbers
      x-api-path-slug: restapiv1-0accountaccountidextensionextensionidphonenumber-get
      parameters:
      - in: path
        name: accountId
        description: Internal identifier of a RingCentral account or tilde (~) to
          indicate the account logged-in within the current session
      - in: path
        name: extensionId
        description: Internal identifier of an extension or tilde (~) to indicate
          the extension assigned to the account logged-in within the current session
      - in: query
        name: page
        description: Indicates the page number to retrieve
      - in: query
        name: perPage
        description: Indicates the page size (number of items)
      - in: query
        name: usageType
        description: Usage type of a phone number
      responses:
        200:
          description: OK
      tags:
      - Extension
      - Phone
      - Number
      - List
  /restapi/v1.0/account/{accountId}/extension/{extensionId}:
    get:
      summary: Get Extension Info
      description: "Returns basic information about a particular extension of an account.\nApp
        Permission\nReadAccounts\nUser Permission\nReadExtensions\nUsage Plan Group\nLight\nError
        Codes\n\n \n  \n   HTTP Code\n   Error Code\n   Error Message\n   \n \n\n401\nCMN-405\nLogin
        to extension required\n\n\n401\nOAU-129\nAccess token corrupted\n\n\n401\nOAU-151\nAuthorization
        method not supported\n\n\n403\nCMN-401\nIn order to call this API endpoint,
        application needs to have [ReadAccounts] permission\n\n\n404\nCMN-102\nResource
        for parameter [extensionId] is not found\n\n\n429\nCMN-301\nRequest rate exceeded"
      operationId: loadExtensionInfo
      x-api-path-slug: restapiv1-0accountaccountidextensionextensionid-get
      parameters:
      - in: path
        name: accountId
        description: Internal identifier of a RingCentral account or tilde (~) to
          indicate the account logged-in within the current session
      - in: path
        name: extensionId
        description: Internal identifier of an extension or tilde (~) to indicate
          the extension assigned to the account logged-in within the current session
      responses:
        200:
          description: OK
      tags:
      - Extension
      - Info
  /restapi/v1.0/account/{accountId}/extension/{extensionId}/caller-id:
    get:
      summary: Get Extension Caller ID
      description: |-
        Returns information on an outbound caller ID of an extension.
        App Permission
        ReadAccounts
        User Permission
        ReadCallerIDSettings
        Usage Plan Group
        Light
      operationId: loadExtensionCallerId
      x-api-path-slug: restapiv1-0accountaccountidextensionextensionidcallerid-get
      parameters:
      - in: path
        name: accountId
        description: Internal identifier of a RingCentral account or tilde (~) to
          indicate the account logged-in within the current session
      - in: path
        name: extensionId
        description: Internal identifier of an extension or tilde (~) to indicate
          the extension assigned to the account logged-in within the current session
      responses:
        200:
          description: OK
      tags:
      - Extension
      - Caller
      - ID
    put:
      summary: Update Extension Caller ID
      description: "Updates outbound caller ID information of an extension.\nApp Permission\nEditExtensions\nUser
        Permission\nEditCallerIDSettings\nUsage Plan Group\nMedium\nError Codes\n\n
        \n  \n   HTTP Code\n   Error Code\n   Error Message\n   \n \n\n400\nCMN-101\nParameter
        [byFeature.callerId.type] value is invalid\n\n\n400\nCMN-102\nResource for
        parameter [phoneInfo.id] is not found\n\n\n403\nCID-101\nFeature [CommonPhone]
        is not available for current account.\n\n\n403\nCID-102\nContact center phone
        number cannot be set as caller ID: Contact Center is not available for current
        account.\n\n\n403\nCID-103\nConferencing phone number cannot be set as caller
        ID."
      operationId: updateExtensionCallerId
      x-api-path-slug: restapiv1-0accountaccountidextensionextensionidcallerid-put
      parameters:
      - in: path
        name: accountId
        description: Internal identifier of a RingCentral account or tilde (~) to
          indicate the account logged-in within the current session
      - in: body
        name: body
        description: JSON body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: extensionId
        description: Internal identifier of an extension or tilde (~) to indicate
          the extension assigned to the account logged-in within the current session
      responses:
        200:
          description: OK
      tags:
      - Extension
      - Caller
      - ID
  /restapi/v1.0/account/{accountId}/extension/{extensionId}/grant:
    get:
      summary: Get Extension Grants
      description: "Returns the list of extension grants.\nApp Permission\nReadAccounts\nUser
        Permission\nReadExtensions\nUsage Plan Group\nLight\nError Codes\n\n \n  \n
        \  HTTP Code\n   Error Code\n   Error Message\n   \n \n\n401\nCMN-405\nLogin
        to extension required\n\n\n401\nOAU-151\nAuthorization method not supported\n\n\n403\nCMN-408\nIn
        order to call this API endpoint, user needs to have [ReadExtensionGrant] permission
        for requested resource.\n\n\n404\nCMN-102\nResource for parameter [accountId]
        is not found"
      operationId: listExtensionGrants
      x-api-path-slug: restapiv1-0accountaccountidextensionextensionidgrant-get
      parameters:
      - in: path
        name: accountId
        description: Internal identifier of a RingCentral account or tilde (~) to
          indicate the account logged-in within the current session
      - in: path
        name: extensionId
        description: Internal identifier of an extension or tilde (~) to indicate
          the extension assigned to the account logged-in within the current session
      - in: query
        name: page
      - in: query
        name: perPage
      responses:
        200:
          description: OK
      tags:
      - Extension
      - Grants
  /restapi/v1.0/account/{accountId}/extension/{extensionId}/profile-image/{scaleSize}:
    get:
      summary: Get Extension Profile Image (Scaled)
      description: "Returns profile image of an extension.\nApp Permission\nReadAccounts\nUser
        Permission\nReadExtensions\nUsage Plan Group\nLight\nError Codes\n\n \n  \n
        \  HTTP Code\n   Error Code\n   Error Message\n   \n \n\n404\nACT-333\nProfile
        image is not found for scale size [92]"
      operationId: loadExtensionProfileImage
      x-api-path-slug: restapiv1-0accountaccountidextensionextensionidprofileimagescalesize-get
      parameters:
      - in: path
        name: accountId
        description: Internal identifier of a RingCentral account or tilde (~) to
          indicate the account logged-in within the current session
      - in: path
        name: extensionId
        description: Internal identifier of an extension or tilde (~) to indicate
          the extension assigned to the account logged-in within the current session
      - in: path
        name: scaleSize
        description: Dimensions of a profile image which will be returned in response
      responses:
        200:
          description: OK
      tags:
      - Extension
      - Profile
      - Image
      - (Scaled)
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