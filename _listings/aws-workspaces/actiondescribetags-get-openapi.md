---
swagger: "2.0"
x-collection-name: AWS WorkSpaces
x-complete: 0
info:
  title: AWS WorkSpaces Service API Describe Tags
  version: 1.0.0
  description: Describes tags for a WorkSpace.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=DescribeTags:
    get:
      summary: Describe Tags
      description: Describes tags for a WorkSpace.
      operationId: describeTags
      x-api-path-slug: actiondescribetags-get
      parameters:
      - in: query
        name: ResourceId
        description: The resource ID of the request
        type: string
      responses:
        200:
          description: OK
      tags:
      - Tags
  /?Action=DescribeWorkspaceBundles:
    get:
      summary: Describe Workspace Bundles
      description: Obtains information about the WorkSpace bundles that are available
        to your account in the specified region.
      operationId: describeWorkspaceBundles
      x-api-path-slug: actiondescribeworkspacebundles-get
      parameters:
      - in: query
        name: BundleIds
        description: An array of strings that contains the identifiers of the bundles
          to retrieve
        type: string
      - in: query
        name: NextToken
        description: The NextToken value from a previous call to this operation
        type: string
      - in: query
        name: Owner
        description: The owner of the bundles to retrieve
        type: string
      responses:
        200:
          description: OK
      tags:
      - Workspace Bundles
  /?Action=DescribeWorkspaceDirectories:
    get:
      summary: Describe Workspace Directories
      description: Retrieves information about the AWS Directory Service directories
        in the region that are registered with Amazon WorkSpaces and are available
        to your account.
      operationId: describeWorkspaceDirectories
      x-api-path-slug: actiondescribeworkspacedirectories-get
      parameters:
      - in: query
        name: DirectoryIds
        description: An array of strings that contains the directory identifiers to
          retrieve information for
        type: string
      - in: query
        name: NextToken
        description: The NextToken value from a previous call to this operation
        type: string
      responses:
        200:
          description: OK
      tags:
      - Workspace Directories
  /?Action=DescribeWorkspaces:
    get:
      summary: Describe Workspaces
      description: Obtains information about the specified WorkSpaces.
      operationId: describeWorkspaces
      x-api-path-slug: actiondescribeworkspaces-get
      parameters:
      - in: query
        name: BundleId
        description: The identifier of a bundle to obtain the WorkSpaces for
        type: string
      - in: query
        name: DirectoryId
        description: Specifies the directory identifier to which to limit the WorkSpaces
        type: string
      - in: query
        name: Limit
        description: The maximum number of items to return
        type: string
      - in: query
        name: NextToken
        description: The NextToken value from a previous call to this operation
        type: string
      - in: query
        name: UserName
        description: Used with the DirectoryId parameter to specify the directory
          user for whom to         obtain the WorkSpace
        type: string
      - in: query
        name: WorkspaceIds
        description: An array of strings that contain the identifiers of the WorkSpaces
          for which to retrieve information
        type: string
      responses:
        200:
          description: OK
      tags:
      - Workspaces
  /?Action=DescribeWorkspacesConnectionStatus:
    get:
      summary: Describe Workspaces Connection Status
      description: Describes the connection status of a specified WorkSpace.
      operationId: describeWorkspacesConnectionStatus
      x-api-path-slug: actiondescribeworkspacesconnectionstatus-get
      parameters:
      - in: query
        name: NextToken
        description: The next token of the request
        type: string
      - in: query
        name: WorkspaceIds
        description: An array of strings that contain the identifiers of the WorkSpaces
        type: string
      responses:
        200:
          description: OK
      tags:
      - Workspaces
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