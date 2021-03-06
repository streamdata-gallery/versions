---
swagger: "2.0"
info:
  title: Akamai API Update a Property Version&#8217;s Rule Tree
  description: Update a Property Version&#8217;s Rule Tree
  version: 1.0.0
host: developer.akamai.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /papi/v0/properties/{propertyId}/versions/{propertyVersion}/rules/:
    put:
      summary: Update a Property Version&#8217;s Rule Tree
      description: Update a Property Version&#8217;s Rule Tree
      operationId: papiv0propertiespropertyidversionspropertyversionrulescontractidgroupid
      parameters:
      - in: query
        name: contractId
        description: Unique identifier for the contract
        type: string
      - in: query
        name: groupId
        description: Unique identifier for the group
        type: string
      - in: query
        name: propertyId
        description: Unique identifier for the property
        type: string
      - in: query
        name: propertyVersion
        description: Property&#8217;s incremental version number
        type: string
      responses:
        200:
          description: OK
      tags:
      - papi
      - v0
      - properties
      - property
      - versions
      - propertyversion
      - rules
      - contract
      - group
definitions: []
x-collection-name: Akamai
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