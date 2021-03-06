swagger: "2.0"
x-collection-name: AWS Snowball
x-complete: 1
info:
  title: AWS Snowball API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=DescribeAddress:
    get:
      summary: Describe Address
      description: |-
        Takes an AddressId and returns specific details about that address in the
              form of an Address object.
      operationId: describeAddress
      x-api-path-slug: actiondescribeaddress-get
      parameters:
      - in: query
        name: AddressId
        description: The automatically generated ID for a specific address
        type: string
      responses:
        200:
          description: OK
      tags:
      - Addresses
  /?Action=DescribeAddresses:
    get:
      summary: Describe Addresses
      description: Returns a specified number of ADDRESS objects.
      operationId: describeAddresses
      x-api-path-slug: actiondescribeaddresses-get
      parameters:
      - in: query
        name: MaxResults
        description: The number of ADDRESS objects to return
        type: string
      - in: query
        name: NextToken
        description: HTTP requests are stateless
        type: string
      responses:
        200:
          description: OK
      tags:
      - Addresses
  /?Action=DescribeCluster:
    get:
      summary: Describe Cluster
      description: |-
        Returns information about a specific cluster including shipping information, cluster
              status, and other important metadata.
      operationId: describeCluster
      x-api-path-slug: actiondescribecluster-get
      parameters:
      - in: query
        name: ClusterId
        description: The automatically generated ID for a cluster
        type: string
      responses:
        200:
          description: OK
      tags:
      - Clusters
  /?Action=DescribeJob:
    get:
      summary: Describe Job
      description: |-
        Returns information about a specific job including shipping information, job status,
              and other important metadata.
      operationId: describeJob
      x-api-path-slug: actiondescribejob-get
      parameters:
      - in: query
        name: JobId
        description: The automatically generated ID for a job, for example        JID123e4567-e89b-12d3-a456-426655440000
        type: string
      responses:
        200:
          description: OK
      tags:
      - Jobs