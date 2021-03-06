---
swagger: "2.0"
x-collection-name: AWS Data Pipeline
x-complete: 0
info:
  title: AWS Data Pipeline API Describe Pipelines
  version: 1.0.0
  description: Retrieves metadata about one or more pipelines.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=DescribeObjects:
    get:
      summary: Describe Objects
      description: Gets the object definitions for a set of objects associated with
        the pipeline.
      operationId: describeObjects
      x-api-path-slug: actiondescribeobjects-get
      parameters:
      - in: query
        name: evaluateExpressions
        description: Indicates whether any expressions in the object should be evaluated
          when the object descriptions are returned
        type: string
      - in: query
        name: marker
        description: The starting point for the results to be returned
        type: string
      - in: query
        name: objectIds
        description: The IDs of the pipeline objects that contain the definitions
          to be described
        type: string
      - in: query
        name: pipelineId
        description: The ID of the pipeline that contains the object definitions
        type: string
      responses:
        200:
          description: OK
      tags:
      - Objects
  /?Action=DescribePipelines:
    get:
      summary: Describe Pipelines
      description: Retrieves metadata about one or more pipelines.
      operationId: describePipelines
      x-api-path-slug: actiondescribepipelines-get
      parameters:
      - in: query
        name: pipelineIds
        description: The IDs of the pipelines to describe
        type: string
      responses:
        200:
          description: OK
      tags:
      - Pipeline
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