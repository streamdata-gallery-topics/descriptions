swagger: "2.0"
x-collection-name: Google API Discovery Service
x-complete: 1
info:
  title: APIs Discovery Service
  description: provides-information-about-other-google-apis-such-as-what-apis-are-available-the-resource-and-method-details-for-each-api-
  contact:
    name: Google
    url: https://google.com
  version: v1
host: www.googleapis.com
basePath: /discovery/v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /apis/{api}/{version}/rest:
    get:
      summary: Get API Description
      description: Retrieve the description of a particular version of an api.
      operationId: discovery.apis.getRest
      x-api-path-slug: apisapiversionrest-get
      parameters:
      - in: path
        name: api
        description: The name of the API
      - in: path
        name: version
        description: The version of the API
      responses:
        200:
          description: OK
      tags:
      - API