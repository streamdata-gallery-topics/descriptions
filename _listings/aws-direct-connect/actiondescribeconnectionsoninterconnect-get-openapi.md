---
swagger: "2.0"
x-collection-name: AWS Direct Connect
x-complete: 0
info:
  title: AWS Direct Connect API Describe Connections On Interconnect
  version: 1.0.0
  description: Return a list of connections that have been provisioned on the given
    interconnect.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=DescribeConnectionLoa:
    get:
      summary: Describe Connection Loa
      description: Returns the LOA-CFA for a Connection.
      operationId: describeConnectionLoa
      x-api-path-slug: actiondescribeconnectionloa-get
      parameters:
      - in: query
        name: connectionId
        description: ID of the connection
        type: string
      - in: query
        name: loaContentType
        description: A standard media type indicating the content type of the LOA-CFA
          document
        type: string
      - in: query
        name: providerName
        description: The name of the APN partner or service provider who establishes
          connectivity on your behalf
        type: string
      responses:
        200:
          description: OK
      tags:
      - Connections
  /?Action=DescribeConnections:
    get:
      summary: Describe Connections
      description: Displays all connections in this region.
      operationId: describeConnections
      x-api-path-slug: actiondescribeconnections-get
      parameters:
      - in: query
        name: connectionId
        description: ID of the connection
        type: string
      responses:
        200:
          description: OK
      tags:
      - Connections
  /?Action=DescribeConnectionsOnInterconnect:
    get:
      summary: Describe Connections On Interconnect
      description: Return a list of connections that have been provisioned on the
        given interconnect.
      operationId: describeConnectionsOnInterconnect
      x-api-path-slug: actiondescribeconnectionsoninterconnect-get
      parameters:
      - in: query
        name: interconnectId
        description: ID of the interconnect on which a list of connection is provisioned
        type: string
      responses:
        200:
          description: OK
      tags:
      - Connections
  /?Action=DescribeInterconnectLoa:
    get:
      summary: Describe Interconnect Loa
      description: Returns the LOA-CFA for an Interconnect.
      operationId: describeInterconnectLoa
      x-api-path-slug: actiondescribeinterconnectloa-get
      parameters:
      - in: query
        name: interconnectId
        description: The ID of the interconnect
        type: string
      - in: query
        name: loaContentType
        description: A standard media type indicating the content type of the LOA-CFA
          document
        type: string
      - in: query
        name: providerName
        description: The name of the service provider who establishes connectivity
          on your behalf
        type: string
      responses:
        200:
          description: OK
      tags:
      - Interconnects
  /?Action=DescribeInterconnects:
    get:
      summary: Describe Interconnects
      description: Returns a list of interconnects owned by the AWS account.
      operationId: describeInterconnects
      x-api-path-slug: actiondescribeinterconnects-get
      parameters:
      - in: query
        name: interconnectId
        description: The ID of the interconnect
        type: string
      responses:
        200:
          description: OK
      tags:
      - Interconnects
  /?Action=DescribeLocations:
    get:
      summary: Describe Locations
      description: Returns the list of AWS Direct Connect locations in the current
        AWS region.
      operationId: describeLocations
      x-api-path-slug: actiondescribelocations-get
      parameters:
      - in: query
        name: locations
        description: A list of colocation hubs where network providers have equipment
        type: string
      responses:
        200:
          description: OK
      tags:
      - Locations
  /?Action=DescribeTags:
    get:
      summary: Describe Tags
      description: Describes the tags associated with the specified Direct Connect
        resources.
      operationId: describeTags
      x-api-path-slug: actiondescribetags-get
      parameters:
      - in: query
        name: resourceArns
        description: The Amazon Resource Names (ARNs) of the Direct Connect resources
        type: string
      responses:
        200:
          description: OK
      tags:
      - Tags
  /?Action=DescribeVirtualGateways:
    get:
      summary: Describe Virtual Gateways
      description: Returns a list of virtual private gateways owned by the AWS account.
      operationId: describeVirtualGateways
      x-api-path-slug: actiondescribevirtualgateways-get
      parameters:
      - in: query
        name: virtualGateways
        description: A list of virtual private gateways
        type: string
      responses:
        200:
          description: OK
      tags:
      - Virtual Gateways
  /?Action=DescribeVirtualInterfaces:
    get:
      summary: Describe Virtual Interfaces
      description: Displays all virtual interfaces for an AWS account.
      operationId: describeVirtualInterfaces
      x-api-path-slug: actiondescribevirtualinterfaces-get
      parameters:
      - in: query
        name: connectionId
        description: ID of the connection
        type: string
      - in: query
        name: virtualInterfaceId
        description: ID of the virtual interface
        type: string
      responses:
        200:
          description: OK
      tags:
      - Private Virtual Interfaces
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