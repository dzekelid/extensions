swagger: "2.0"
x-collection-name: SAP
x-complete: 1
info:
  title: SAP Translation Hub
  description: to-provide-users-of-software-in-a-global-market-with-texts-in-their-own-language-translations-are-required--sap-translation-hub-enables-you-to-draw-on-saps-translation-experience-across-multiple-products-and-languages-to-propose-translations-for-short-texts-
  contact:
    name: SAP Translation Hub team
    email: translationhub@sap.com
  version: 1.0.0
host: sandbox.api.sap.com
basePath: /translationhub/api/v1
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