---
swagger: "2.0"
x-collection-name: AWS Kinesis
x-complete: 0
info:
  title: AWS Kinesis Firehose API Describe Delivery Stream
  version: 1.0.0
  description: describes the specified delivery stream and gets the status.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=DescribeDeliveryStream:
    get:
      summary: Describe Delivery Stream
      description: describes the specified delivery stream and gets the status.
      operationId: DescribeDeliveryStream
      x-api-path-slug: actiondescribedeliverystream-get
      parameters:
      - in: query
        name: DeliveryStreamName
        description: The name of the delivery stream
        type: string
      - in: query
        name: ExclusiveStartDestinationId
        description: The ID of the destination to start returning the destination
          information
        type: string
      - in: query
        name: Limit
        description: The limit on the number of destinations to return
        type: string
      responses:
        200:
          description: OK
      tags:
      - Delivery Streams
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