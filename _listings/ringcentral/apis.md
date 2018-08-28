---
name: RingCentral
x-slug: ringcentral
description: 'RingCentral, Inc. (NYSE: RNG) is a global provider of cloud enterprise
  unified communications and collaboration solutions. More flexible and cost-effective
  than legacy on-premise systems, RingCentral empowers today&rsquo;s mobile and distributed
  workforces to be connected anywhere and on any device through voice, video, team
  messaging, collaboration, SMS, conferencing, online meetings, contact center, and
  fax. RingCentral provides an open platform that integrates with today&rsquo;s leading
  business apps while giving customers the flexibility to customize their own workflows.'
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
x-kinRank: "7"
x-alexaRank: "7180"
tags: Extensions
created: "2018-08-27"
modified: "2018-08-27"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/extensions/master/_listings/ringcentral/apis.md
specificationVersion: "0.14"
apis:
- name: RingCentral Connect Platform API Explorer - Get Extensions
  x-api-slug: restapiv1-0accountaccountidextension-get
  description: "Returns the list of extensions created for a particular account. All
    types of extensions are included in this list.\nApp Permission\nReadAccounts\nUser
    Permission\nReadExtensions\nUsage Plan Group\nMedium\nError Codes\n\n \n  \n   HTTP
    Code\n   Error Code\n   Error Message\n   \n \n\n400\nCMN-101\nParameter [status]
    value is invalid\n\n\n401\nCMN-405\nLogin to extension required\n\n\n401\nOAU-151\nAuthorization
    method not supported\n\n\n403\nCMN-401\nIn order to call this API endpoint, application
    needs to have [ReadAccounts] permission\n\n\n404\nCMN-102\nResource for parameter
    [accountId] is not found\n\n\n429\nCMN-301\nRequest rate exceeded"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/extensions/master/_listings/ringcentral/restapiv1-0accountaccountidextension-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Call Recording Extension Settings
  x-api-slug: restapiv1-0accountaccountidcallrecordingextensions-get
  description: |-
    Returns the list of extensions to be recorded.
    App Permission
    ReadAccounts
    User Permission
    ReadCompanyInfo
    Usage Plan Group
    Medium
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/extensions/master/_listings/ringcentral/restapiv1-0accountaccountidcallrecordingextensions-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Extension Phone Number List
  x-api-slug: restapiv1-0accountaccountidextensionextensionidphonenumber-get
  description: "Returns the list of phone numbers that are used by a particular extension,
    and can be filtered by the phone number type. The returned list contains all numbers
    which are directly mapped to a given extension plus the features and also company-level
    numbers which may be used when performing different operations on behalf of this
    extension.\nApp Permission\nReadAccounts\nUser Permission\nReadUserPhoneNumbers\nUsage
    Plan Group\nLight\nError Codes\n\n \n  \n   HTTP Code\n   Error Code\n   Error
    Message\n   \n \n\n400\nCMN-101\nParameter [usageType] value is invalid\n\n\n401\nCMN-405\nLogin
    to extension required\n\n\n401\nOAU-151\nAuthorization method not supported\n\n\n403\nCMN-401\nIn
    order to call this API endpoint, application needs to have [ReadAccounts] permission\n\n\n404\nCMN-102\nResource
    for parameter [extensionId] is not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/extensions/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidphonenumber-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Extension Info
  x-api-slug: restapiv1-0accountaccountidextensionextensionid-get
  description: "Returns basic information about a particular extension of an account.\nApp
    Permission\nReadAccounts\nUser Permission\nReadExtensions\nUsage Plan Group\nLight\nError
    Codes\n\n \n  \n   HTTP Code\n   Error Code\n   Error Message\n   \n \n\n401\nCMN-405\nLogin
    to extension required\n\n\n401\nOAU-129\nAccess token corrupted\n\n\n401\nOAU-151\nAuthorization
    method not supported\n\n\n403\nCMN-401\nIn order to call this API endpoint, application
    needs to have [ReadAccounts] permission\n\n\n404\nCMN-102\nResource for parameter
    [extensionId] is not found\n\n\n429\nCMN-301\nRequest rate exceeded"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/extensions/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/extensions/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionid-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Extension Caller ID
  x-api-slug: restapiv1-0accountaccountidextensionextensionidcallerid-get
  description: |-
    Returns information on an outbound caller ID of an extension.
    App Permission
    ReadAccounts
    User Permission
    ReadCallerIDSettings
    Usage Plan Group
    Light
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/extensions/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidcallerid-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Update Extension Caller ID
  x-api-slug: restapiv1-0accountaccountidextensionextensionidcallerid-put
  description: "Updates outbound caller ID information of an extension.\nApp Permission\nEditExtensions\nUser
    Permission\nEditCallerIDSettings\nUsage Plan Group\nMedium\nError Codes\n\n \n
    \ \n   HTTP Code\n   Error Code\n   Error Message\n   \n \n\n400\nCMN-101\nParameter
    [byFeature.callerId.type] value is invalid\n\n\n400\nCMN-102\nResource for parameter
    [phoneInfo.id] is not found\n\n\n403\nCID-101\nFeature [CommonPhone] is not available
    for current account.\n\n\n403\nCID-102\nContact center phone number cannot be
    set as caller ID: Contact Center is not available for current account.\n\n\n403\nCID-103\nConferencing
    phone number cannot be set as caller ID."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/extensions/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidcallerid-put-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Extension Grants
  x-api-slug: restapiv1-0accountaccountidextensionextensionidgrant-get
  description: "Returns the list of extension grants.\nApp Permission\nReadAccounts\nUser
    Permission\nReadExtensions\nUsage Plan Group\nLight\nError Codes\n\n \n  \n   HTTP
    Code\n   Error Code\n   Error Message\n   \n \n\n401\nCMN-405\nLogin to extension
    required\n\n\n401\nOAU-151\nAuthorization method not supported\n\n\n403\nCMN-408\nIn
    order to call this API endpoint, user needs to have [ReadExtensionGrant] permission
    for requested resource.\n\n\n404\nCMN-102\nResource for parameter [accountId]
    is not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/extensions/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidgrant-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/extensions/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidgrant-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Extension Profile Image (Scaled)
  x-api-slug: restapiv1-0accountaccountidextensionextensionidprofileimagescalesize-get
  description: "Returns profile image of an extension.\nApp Permission\nReadAccounts\nUser
    Permission\nReadExtensions\nUsage Plan Group\nLight\nError Codes\n\n \n  \n   HTTP
    Code\n   Error Code\n   Error Message\n   \n \n\n404\nACT-333\nProfile image is
    not found for scale size [92]"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/extensions/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidprofileimagescalesize-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Call Recording Extension Settings
  x-api-slug: restapiv1-0accountaccountidcallrecordingextensions-get
  description: |-
    Returns the list of extensions to be recorded.
    App Permission
    ReadAccounts
    User Permission
    ReadCompanyInfo
    Usage Plan Group
    Medium
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/extensions/master/_listings/ringcentral/restapiv1-0accountaccountidcallrecordingextensions-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Extension Phone Number List
  x-api-slug: restapiv1-0accountaccountidextensionextensionidphonenumber-get
  description: "Returns the list of phone numbers that are used by a particular extension,
    and can be filtered by the phone number type. The returned list contains all numbers
    which are directly mapped to a given extension plus the features and also company-level
    numbers which may be used when performing different operations on behalf of this
    extension.\nApp Permission\nReadAccounts\nUser Permission\nReadUserPhoneNumbers\nUsage
    Plan Group\nLight\nError Codes\n\n \n  \n   HTTP Code\n   Error Code\n   Error
    Message\n   \n \n\n400\nCMN-101\nParameter [usageType] value is invalid\n\n\n401\nCMN-405\nLogin
    to extension required\n\n\n401\nOAU-151\nAuthorization method not supported\n\n\n403\nCMN-401\nIn
    order to call this API endpoint, application needs to have [ReadAccounts] permission\n\n\n404\nCMN-102\nResource
    for parameter [extensionId] is not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/extensions/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidphonenumber-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Extension Info
  x-api-slug: restapiv1-0accountaccountidextensionextensionid-get
  description: "Returns basic information about a particular extension of an account.\nApp
    Permission\nReadAccounts\nUser Permission\nReadExtensions\nUsage Plan Group\nLight\nError
    Codes\n\n \n  \n   HTTP Code\n   Error Code\n   Error Message\n   \n \n\n401\nCMN-405\nLogin
    to extension required\n\n\n401\nOAU-129\nAccess token corrupted\n\n\n401\nOAU-151\nAuthorization
    method not supported\n\n\n403\nCMN-401\nIn order to call this API endpoint, application
    needs to have [ReadAccounts] permission\n\n\n404\nCMN-102\nResource for parameter
    [extensionId] is not found\n\n\n429\nCMN-301\nRequest rate exceeded"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/extensions/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/extensions/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionid-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Extension Caller ID
  x-api-slug: restapiv1-0accountaccountidextensionextensionidcallerid-get
  description: |-
    Returns information on an outbound caller ID of an extension.
    App Permission
    ReadAccounts
    User Permission
    ReadCallerIDSettings
    Usage Plan Group
    Light
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/extensions/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidcallerid-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Update Extension Caller ID
  x-api-slug: restapiv1-0accountaccountidextensionextensionidcallerid-put
  description: "Updates outbound caller ID information of an extension.\nApp Permission\nEditExtensions\nUser
    Permission\nEditCallerIDSettings\nUsage Plan Group\nMedium\nError Codes\n\n \n
    \ \n   HTTP Code\n   Error Code\n   Error Message\n   \n \n\n400\nCMN-101\nParameter
    [byFeature.callerId.type] value is invalid\n\n\n400\nCMN-102\nResource for parameter
    [phoneInfo.id] is not found\n\n\n403\nCID-101\nFeature [CommonPhone] is not available
    for current account.\n\n\n403\nCID-102\nContact center phone number cannot be
    set as caller ID: Contact Center is not available for current account.\n\n\n403\nCID-103\nConferencing
    phone number cannot be set as caller ID."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/extensions/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidcallerid-put-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Extension Grants
  x-api-slug: restapiv1-0accountaccountidextensionextensionidgrant-get
  description: "Returns the list of extension grants.\nApp Permission\nReadAccounts\nUser
    Permission\nReadExtensions\nUsage Plan Group\nLight\nError Codes\n\n \n  \n   HTTP
    Code\n   Error Code\n   Error Message\n   \n \n\n401\nCMN-405\nLogin to extension
    required\n\n\n401\nOAU-151\nAuthorization method not supported\n\n\n403\nCMN-408\nIn
    order to call this API endpoint, user needs to have [ReadExtensionGrant] permission
    for requested resource.\n\n\n404\nCMN-102\nResource for parameter [accountId]
    is not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/extensions/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidgrant-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/extensions/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidgrant-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Extension Profile Image (Scaled)
  x-api-slug: restapiv1-0accountaccountidextensionextensionidprofileimagescalesize-get
  description: "Returns profile image of an extension.\nApp Permission\nReadAccounts\nUser
    Permission\nReadExtensions\nUsage Plan Group\nLight\nError Codes\n\n \n  \n   HTTP
    Code\n   Error Code\n   Error Message\n   \n \n\n404\nACT-333\nProfile image is
    not found for scale size [92]"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/extensions/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidprofileimagescalesize-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Extension Profile Image (Scaled)
  x-api-slug: restapiv1-0accountaccountidextensionextensionidprofileimagescalesize-get
  description: "Returns profile image of an extension.\nApp Permission\nReadAccounts\nUser
    Permission\nReadExtensions\nUsage Plan Group\nLight\nError Codes\n\n \n  \n   HTTP
    Code\n   Error Code\n   Error Message\n   \n \n\n404\nACT-333\nProfile image is
    not found for scale size [92]"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/extensions/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidprofileimagescalesize-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Extension Grants
  x-api-slug: restapiv1-0accountaccountidextensionextensionidgrant-get
  description: "Returns the list of extension grants.\nApp Permission\nReadAccounts\nUser
    Permission\nReadExtensions\nUsage Plan Group\nLight\nError Codes\n\n \n  \n   HTTP
    Code\n   Error Code\n   Error Message\n   \n \n\n401\nCMN-405\nLogin to extension
    required\n\n\n401\nOAU-151\nAuthorization method not supported\n\n\n403\nCMN-408\nIn
    order to call this API endpoint, user needs to have [ReadExtensionGrant] permission
    for requested resource.\n\n\n404\nCMN-102\nResource for parameter [accountId]
    is not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/extensions/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidgrant-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/extensions/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidgrant-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Update Extension Caller ID
  x-api-slug: restapiv1-0accountaccountidextensionextensionidcallerid-put
  description: "Updates outbound caller ID information of an extension.\nApp Permission\nEditExtensions\nUser
    Permission\nEditCallerIDSettings\nUsage Plan Group\nMedium\nError Codes\n\n \n
    \ \n   HTTP Code\n   Error Code\n   Error Message\n   \n \n\n400\nCMN-101\nParameter
    [byFeature.callerId.type] value is invalid\n\n\n400\nCMN-102\nResource for parameter
    [phoneInfo.id] is not found\n\n\n403\nCID-101\nFeature [CommonPhone] is not available
    for current account.\n\n\n403\nCID-102\nContact center phone number cannot be
    set as caller ID: Contact Center is not available for current account.\n\n\n403\nCID-103\nConferencing
    phone number cannot be set as caller ID."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/extensions/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidcallerid-put-openapi.md
- name: RingCentral Connect Platform API Explorer - Update Extension Caller ID
  x-api-slug: restapiv1-0accountaccountidextensionextensionidcallerid-put
  description: "Updates outbound caller ID information of an extension.\nApp Permission\nEditExtensions\nUser
    Permission\nEditCallerIDSettings\nUsage Plan Group\nMedium\nError Codes\n\n \n
    \ \n   HTTP Code\n   Error Code\n   Error Message\n   \n \n\n400\nCMN-101\nParameter
    [byFeature.callerId.type] value is invalid\n\n\n400\nCMN-102\nResource for parameter
    [phoneInfo.id] is not found\n\n\n403\nCID-101\nFeature [CommonPhone] is not available
    for current account.\n\n\n403\nCID-102\nContact center phone number cannot be
    set as caller ID: Contact Center is not available for current account.\n\n\n403\nCID-103\nConferencing
    phone number cannot be set as caller ID."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/extensions/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidcallerid-put-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Extension Caller ID
  x-api-slug: restapiv1-0accountaccountidextensionextensionidcallerid-get
  description: |-
    Returns information on an outbound caller ID of an extension.
    App Permission
    ReadAccounts
    User Permission
    ReadCallerIDSettings
    Usage Plan Group
    Light
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/extensions/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidcallerid-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Extension Caller ID
  x-api-slug: restapiv1-0accountaccountidextensionextensionidcallerid-get
  description: |-
    Returns information on an outbound caller ID of an extension.
    App Permission
    ReadAccounts
    User Permission
    ReadCallerIDSettings
    Usage Plan Group
    Light
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/extensions/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidcallerid-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Extension Info
  x-api-slug: restapiv1-0accountaccountidextensionextensionid-get
  description: "Returns basic information about a particular extension of an account.\nApp
    Permission\nReadAccounts\nUser Permission\nReadExtensions\nUsage Plan Group\nLight\nError
    Codes\n\n \n  \n   HTTP Code\n   Error Code\n   Error Message\n   \n \n\n401\nCMN-405\nLogin
    to extension required\n\n\n401\nOAU-129\nAccess token corrupted\n\n\n401\nOAU-151\nAuthorization
    method not supported\n\n\n403\nCMN-401\nIn order to call this API endpoint, application
    needs to have [ReadAccounts] permission\n\n\n404\nCMN-102\nResource for parameter
    [extensionId] is not found\n\n\n429\nCMN-301\nRequest rate exceeded"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/extensions/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/extensions/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionid-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Extension Info
  x-api-slug: restapiv1-0accountaccountidextensionextensionid-get
  description: "Returns basic information about a particular extension of an account.\nApp
    Permission\nReadAccounts\nUser Permission\nReadExtensions\nUsage Plan Group\nLight\nError
    Codes\n\n \n  \n   HTTP Code\n   Error Code\n   Error Message\n   \n \n\n401\nCMN-405\nLogin
    to extension required\n\n\n401\nOAU-129\nAccess token corrupted\n\n\n401\nOAU-151\nAuthorization
    method not supported\n\n\n403\nCMN-401\nIn order to call this API endpoint, application
    needs to have [ReadAccounts] permission\n\n\n404\nCMN-102\nResource for parameter
    [extensionId] is not found\n\n\n429\nCMN-301\nRequest rate exceeded"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/extensions/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/extensions/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionid-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Extension Phone Number List
  x-api-slug: restapiv1-0accountaccountidextensionextensionidphonenumber-get
  description: "Returns the list of phone numbers that are used by a particular extension,
    and can be filtered by the phone number type. The returned list contains all numbers
    which are directly mapped to a given extension plus the features and also company-level
    numbers which may be used when performing different operations on behalf of this
    extension.\nApp Permission\nReadAccounts\nUser Permission\nReadUserPhoneNumbers\nUsage
    Plan Group\nLight\nError Codes\n\n \n  \n   HTTP Code\n   Error Code\n   Error
    Message\n   \n \n\n400\nCMN-101\nParameter [usageType] value is invalid\n\n\n401\nCMN-405\nLogin
    to extension required\n\n\n401\nOAU-151\nAuthorization method not supported\n\n\n403\nCMN-401\nIn
    order to call this API endpoint, application needs to have [ReadAccounts] permission\n\n\n404\nCMN-102\nResource
    for parameter [extensionId] is not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/extensions/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidphonenumber-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Extension Phone Number List
  x-api-slug: restapiv1-0accountaccountidextensionextensionidphonenumber-get
  description: "Returns the list of phone numbers that are used by a particular extension,
    and can be filtered by the phone number type. The returned list contains all numbers
    which are directly mapped to a given extension plus the features and also company-level
    numbers which may be used when performing different operations on behalf of this
    extension.\nApp Permission\nReadAccounts\nUser Permission\nReadUserPhoneNumbers\nUsage
    Plan Group\nLight\nError Codes\n\n \n  \n   HTTP Code\n   Error Code\n   Error
    Message\n   \n \n\n400\nCMN-101\nParameter [usageType] value is invalid\n\n\n401\nCMN-405\nLogin
    to extension required\n\n\n401\nOAU-151\nAuthorization method not supported\n\n\n403\nCMN-401\nIn
    order to call this API endpoint, application needs to have [ReadAccounts] permission\n\n\n404\nCMN-102\nResource
    for parameter [extensionId] is not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/extensions/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidphonenumber-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Call Recording Extension Settings
  x-api-slug: restapiv1-0accountaccountidcallrecordingextensions-get
  description: |-
    Returns the list of extensions to be recorded.
    App Permission
    ReadAccounts
    User Permission
    ReadCompanyInfo
    Usage Plan Group
    Medium
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/extensions/master/_listings/ringcentral/restapiv1-0accountaccountidcallrecordingextensions-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Call Recording Extension Settings
  x-api-slug: restapiv1-0accountaccountidcallrecordingextensions-get
  description: |-
    Returns the list of extensions to be recorded.
    App Permission
    ReadAccounts
    User Permission
    ReadCompanyInfo
    Usage Plan Group
    Medium
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/extensions/master/_listings/ringcentral/restapiv1-0accountaccountidcallrecordingextensions-get-openapi.md
x-common:
- type: x-blog
  url: https://medium.com/ringcentral-developers
- type: x-blog-rss
  url: https://medium.com/feed/ringcentral-developers
- type: x-github
  url: https://github.com/ringcentral
- type: x-openapi
  url: https://netstorage.ringcentral.com/dpw/api-explorer/swagger-ring_basic.yml?v=20180816
- type: x-website
  url: http://www.ringcentral.com
- type: x-api-gallery
  url: http://reverb.api.gallery.streamdata.io
- type: x-api-stack
  url: http://ringcentral.stack.network
- type: x-code
  url: https://developer.ringcentral.com/library/sdks.html
- type: x-crunchbase
  url: https://crunchbase.com/organization/ringcentral
- type: x-developer
  url: https://developer.ringcentral.com/
- type: x-documentation
  url: https://developer.ringcentral.com/api-explorer/latest/index.html?_ga=2.259782990.551967760.1534465156-1236351744.1533920460
- type: x-support
  url: https://developer.ringcentral.com/support.html
- type: x-twitter
  url: https://twitter.com/RingCentral
- type: x-website
  url: https://developer.ringcentral.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---