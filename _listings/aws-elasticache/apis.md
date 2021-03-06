---
name: AWS ElastiCache
x-slug: aws-elasticache
description: Amazon ElastiCache is a web service that makes it easy to deploy, operate,
  and scale an in-memory data store or cache in the cloud. The service improves the
  performance of web applications by allowing you to retrieve information from fast,
  managed, in-memory data stores, instead of relying entirely on slower disk-based
  databases. Amazon ElastiCache automatically detects and replaces failed nodes, reducing
  the overhead associated with self-managed infrastructures and provides a resilient
  system that mitigates the risk of overloaded databases, which slow website and application
  load times. Through integration with Amazon CloudWatch, Amazon ElastiCache provides
  enhanced visibility into key performance metrics associated with your Redis or Memcached
  nodes.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Descriptions
created: "2018-08-27"
modified: "2018-08-27"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-elasticache/apis.md
specificationVersion: "0.14"
apis:
- name: AWS ElastiCache API - Describe Cache Clusters
  x-api-slug: actiondescribecacheclusters-get
  description: |-
    Returns information about all provisioned
                cache clusters if no cache cluster identifier is specified, or about a specific cache
                cluster if a cache cluster identifier is supplied.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: :///
  tags: Amazon Web Services, Cache, Stack Network, Performance, Availability, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-elasticache/actiondescribecacheclusters-get-openapi.md
- name: AWS ElastiCache API - Describe Cache Engine Versions
  x-api-slug: actiondescribecacheengineversions-get
  description: |-
    Returns a list of the available cache
                engines and their versions.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: :///
  tags: Amazon Web Services, Cache, Stack Network, Performance, Availability, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-elasticache/actiondescribecacheengineversions-get-openapi.md
- name: AWS ElastiCache API - Describe Cache Parameter Groups
  x-api-slug: actiondescribecacheparametergroups-get
  description: |-
    Returns a list of cache parameter group
                descriptions.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: :///
  tags: Amazon Web Services, Cache, Stack Network, Performance, Availability, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-elasticache/actiondescribecacheparametergroups-get-openapi.md
- name: AWS ElastiCache API - Describe Cache Parameters
  x-api-slug: actiondescribecacheparameters-get
  description: |-
    Returns the detailed parameter list for a
                particular cache parameter group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: :///
  tags: Amazon Web Services, Cache, Stack Network, Performance, Availability, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-elasticache/actiondescribecacheparameters-get-openapi.md
- name: AWS ElastiCache API - Describe Cache Security Groups
  x-api-slug: actiondescribecachesecuritygroups-get
  description: |-
    Returns a list of cache security group
                descriptions.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: :///
  tags: Amazon Web Services, Cache, Stack Network, Performance, Availability, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-elasticache/actiondescribecachesecuritygroups-get-openapi.md
- name: AWS ElastiCache API - Describe Cache Subnet Groups
  x-api-slug: actiondescribecachesubnetgroups-get
  description: |-
    Returns a list of cache subnet group
                descriptions.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: :///
  tags: Amazon Web Services, Cache, Stack Network, Performance, Availability, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-elasticache/actiondescribecachesubnetgroups-get-openapi.md
- name: AWS ElastiCache API - Describe Engine Default Parameters
  x-api-slug: actiondescribeenginedefaultparameters-get
  description: |-
    Returns the default engine and
                system parameter information for the specified cache engine.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: :///
  tags: Amazon Web Services, Cache, Stack Network, Performance, Availability, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-elasticache/actiondescribeenginedefaultparameters-get-openapi.md
- name: AWS ElastiCache API - Describe Events
  x-api-slug: actiondescribeevents-get
  description: |-
    Returns events related to cache clusters, cache
                security groups, and cache parameter groups.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: :///
  tags: Amazon Web Services, Cache, Stack Network, Performance, Availability, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-elasticache/actiondescribeevents-get-openapi.md
- name: AWS ElastiCache API - Describe Events
  x-api-slug: actiondescribeevents-get
  description: |-
    Returns events related to cache clusters, cache
                security groups, and cache parameter groups.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: :///
  tags: Amazon Web Services, Cache, Stack Network, Performance, Availability, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-elasticache/actiondescribeevents-get-openapi.md
- name: AWS ElastiCache API - Describe Replication Groups
  x-api-slug: actiondescribereplicationgroups-get
  description: |-
    Returns information about a particular
                replication group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: :///
  tags: Amazon Web Services, Cache, Stack Network, Performance, Availability, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-elasticache/actiondescribereplicationgroups-get-openapi.md
- name: AWS ElastiCache API - Describe Replication Groups
  x-api-slug: actiondescribereplicationgroups-get
  description: |-
    Returns information about a particular
                replication group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: :///
  tags: Amazon Web Services, Cache, Stack Network, Performance, Availability, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-elasticache/actiondescribereplicationgroups-get-openapi.md
- name: AWS ElastiCache API - Describe Reserved Cache Nodes
  x-api-slug: actiondescribereservedcachenodes-get
  description: |-
    Returns information about reserved cache
                nodes for this account, or about a specified reserved cache node.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: :///
  tags: Amazon Web Services, Cache, Stack Network, Performance, Availability, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-elasticache/actiondescribereservedcachenodes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-elasticache/actiondescribereservedcachenodes-get-openapi.md
- name: AWS ElastiCache API - Describe Reserved Cache Nodes
  x-api-slug: actiondescribereservedcachenodes-get
  description: |-
    Returns information about reserved cache
                nodes for this account, or about a specified reserved cache node.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: :///
  tags: Amazon Web Services, Cache, Stack Network, Performance, Availability, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-elasticache/actiondescribereservedcachenodes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-elasticache/actiondescribereservedcachenodes-get-openapi.md
- name: AWS ElastiCache API - Describe Reserved Cache Nodes Offerings
  x-api-slug: actiondescribereservedcachenodesofferings-get
  description: |-
    Lists available reserved cache
                node offerings.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: :///
  tags: Amazon Web Services, Cache, Stack Network, Performance, Availability, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-elasticache/actiondescribereservedcachenodesofferings-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-elasticache/actiondescribereservedcachenodesofferings-get-openapi.md
- name: AWS ElastiCache API - Describe Reserved Cache Nodes Offerings
  x-api-slug: actiondescribereservedcachenodesofferings-get
  description: |-
    Lists available reserved cache
                node offerings.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: :///
  tags: Amazon Web Services, Cache, Stack Network, Performance, Availability, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-elasticache/actiondescribereservedcachenodesofferings-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-elasticache/actiondescribereservedcachenodesofferings-get-openapi.md
- name: AWS ElastiCache API - Describe Snapshots
  x-api-slug: actiondescribesnapshots-get
  description: Returns information about cache cluster or replication group snapshots.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: :///
  tags: Amazon Web Services, Cache, Stack Network, Performance, Availability, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-elasticache/actiondescribesnapshots-get-openapi.md
- name: AWS ElastiCache API - Describe Snapshots
  x-api-slug: actiondescribesnapshots-get
  description: Returns information about cache cluster or replication group snapshots.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: :///
  tags: Amazon Web Services, Cache, Stack Network, Performance, Availability, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-elasticache/actiondescribesnapshots-get-openapi.md
- name: AWS ElastiCache API - Describe Cache Clusters
  x-api-slug: actiondescribecacheclusters-get
  description: |-
    Returns information about all provisioned
                cache clusters if no cache cluster identifier is specified, or about a specific cache
                cluster if a cache cluster identifier is supplied.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: :///
  tags: Amazon Web Services, Cache, Stack Network, Performance, Availability, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-elasticache/actiondescribecacheclusters-get-openapi.md
- name: AWS ElastiCache API - Describe Cache Clusters
  x-api-slug: actiondescribecacheclusters-get
  description: |-
    Returns information about all provisioned
                cache clusters if no cache cluster identifier is specified, or about a specific cache
                cluster if a cache cluster identifier is supplied.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: :///
  tags: Amazon Web Services, Cache, Stack Network, Performance, Availability, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-elasticache/actiondescribecacheclusters-get-openapi.md
- name: AWS ElastiCache API - Describe Cache Clusters
  x-api-slug: actiondescribecacheclusters-get
  description: |-
    Returns information about all provisioned
                cache clusters if no cache cluster identifier is specified, or about a specific cache
                cluster if a cache cluster identifier is supplied.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: :///
  tags: Amazon Web Services, Cache, Stack Network, Performance, Availability, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-elasticache/actiondescribecacheclusters-get-openapi.md
- name: AWS ElastiCache API - Describe Cache Clusters
  x-api-slug: actiondescribecacheclusters-get
  description: |-
    Returns information about all provisioned
                cache clusters if no cache cluster identifier is specified, or about a specific cache
                cluster if a cache cluster identifier is supplied.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: :///
  tags: Amazon Web Services, Cache, Stack Network, Performance, Availability, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-elasticache/actiondescribecacheclusters-get-openapi.md
- name: AWS ElastiCache API - Describe Cache Clusters
  x-api-slug: actiondescribecacheclusters-get
  description: |-
    Returns information about all provisioned
                cache clusters if no cache cluster identifier is specified, or about a specific cache
                cluster if a cache cluster identifier is supplied.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: :///
  tags: Amazon Web Services, Cache, Stack Network, Performance, Availability, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-elasticache/actiondescribecacheclusters-get-openapi.md
- name: AWS ElastiCache API - Describe Cache Clusters
  x-api-slug: actiondescribecacheclusters-get
  description: |-
    Returns information about all provisioned
                cache clusters if no cache cluster identifier is specified, or about a specific cache
                cluster if a cache cluster identifier is supplied.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: :///
  tags: Amazon Web Services, Cache, Stack Network, Performance, Availability, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-elasticache/actiondescribecacheclusters-get-openapi.md
- name: AWS ElastiCache API - Describe Cache Clusters
  x-api-slug: actiondescribecacheclusters-get
  description: |-
    Returns information about all provisioned
                cache clusters if no cache cluster identifier is specified, or about a specific cache
                cluster if a cache cluster identifier is supplied.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: :///
  tags: Amazon Web Services, Cache, Stack Network, Performance, Availability, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-elasticache/actiondescribecacheclusters-get-openapi.md
- name: AWS ElastiCache API - Describe Cache Engine Versions
  x-api-slug: actiondescribecacheengineversions-get
  description: |-
    Returns a list of the available cache
                engines and their versions.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: :///
  tags: Amazon Web Services, Cache, Stack Network, Performance, Availability, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-elasticache/actiondescribecacheengineversions-get-openapi.md
- name: AWS ElastiCache API - Describe Cache Engine Versions
  x-api-slug: actiondescribecacheengineversions-get
  description: |-
    Returns a list of the available cache
                engines and their versions.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: :///
  tags: Amazon Web Services, Cache, Stack Network, Performance, Availability, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-elasticache/actiondescribecacheengineversions-get-openapi.md
- name: AWS ElastiCache API - Describe Cache Engine Versions
  x-api-slug: actiondescribecacheengineversions-get
  description: |-
    Returns a list of the available cache
                engines and their versions.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: :///
  tags: Amazon Web Services, Cache, Stack Network, Performance, Availability, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-elasticache/actiondescribecacheengineversions-get-openapi.md
- name: AWS ElastiCache API - Describe Cache Engine Versions
  x-api-slug: actiondescribecacheengineversions-get
  description: |-
    Returns a list of the available cache
                engines and their versions.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: :///
  tags: Amazon Web Services, Cache, Stack Network, Performance, Availability, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-elasticache/actiondescribecacheengineversions-get-openapi.md
- name: AWS ElastiCache API - Describe Cache Engine Versions
  x-api-slug: actiondescribecacheengineversions-get
  description: |-
    Returns a list of the available cache
                engines and their versions.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: :///
  tags: Amazon Web Services, Cache, Stack Network, Performance, Availability, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-elasticache/actiondescribecacheengineversions-get-openapi.md
- name: AWS ElastiCache API - Describe Cache Engine Versions
  x-api-slug: actiondescribecacheengineversions-get
  description: |-
    Returns a list of the available cache
                engines and their versions.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: :///
  tags: Amazon Web Services, Cache, Stack Network, Performance, Availability, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-elasticache/actiondescribecacheengineversions-get-openapi.md
- name: AWS ElastiCache API - Describe Cache Engine Versions
  x-api-slug: actiondescribecacheengineversions-get
  description: |-
    Returns a list of the available cache
                engines and their versions.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: :///
  tags: Amazon Web Services, Cache, Stack Network, Performance, Availability, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-elasticache/actiondescribecacheengineversions-get-openapi.md
- name: AWS ElastiCache API - Describe Cache Parameter Groups
  x-api-slug: actiondescribecacheparametergroups-get
  description: |-
    Returns a list of cache parameter group
                descriptions.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: :///
  tags: Amazon Web Services, Cache, Stack Network, Performance, Availability, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-elasticache/actiondescribecacheparametergroups-get-openapi.md
- name: AWS ElastiCache API - Describe Cache Parameter Groups
  x-api-slug: actiondescribecacheparametergroups-get
  description: |-
    Returns a list of cache parameter group
                descriptions.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: :///
  tags: Amazon Web Services, Cache, Stack Network, Performance, Availability, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-elasticache/actiondescribecacheparametergroups-get-openapi.md
- name: AWS ElastiCache API - Describe Cache Parameter Groups
  x-api-slug: actiondescribecacheparametergroups-get
  description: |-
    Returns a list of cache parameter group
                descriptions.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: :///
  tags: Amazon Web Services, Cache, Stack Network, Performance, Availability, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-elasticache/actiondescribecacheparametergroups-get-openapi.md
- name: AWS ElastiCache API - Describe Cache Parameter Groups
  x-api-slug: actiondescribecacheparametergroups-get
  description: |-
    Returns a list of cache parameter group
                descriptions.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: :///
  tags: Amazon Web Services, Cache, Stack Network, Performance, Availability, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-elasticache/actiondescribecacheparametergroups-get-openapi.md
- name: AWS ElastiCache API - Describe Cache Parameter Groups
  x-api-slug: actiondescribecacheparametergroups-get
  description: |-
    Returns a list of cache parameter group
                descriptions.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: :///
  tags: Amazon Web Services, Cache, Stack Network, Performance, Availability, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-elasticache/actiondescribecacheparametergroups-get-openapi.md
- name: AWS ElastiCache API - Describe Cache Parameter Groups
  x-api-slug: actiondescribecacheparametergroups-get
  description: |-
    Returns a list of cache parameter group
                descriptions.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: :///
  tags: Amazon Web Services, Cache, Stack Network, Performance, Availability, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-elasticache/actiondescribecacheparametergroups-get-openapi.md
- name: AWS ElastiCache API - Describe Cache Parameter Groups
  x-api-slug: actiondescribecacheparametergroups-get
  description: |-
    Returns a list of cache parameter group
                descriptions.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: :///
  tags: Amazon Web Services, Cache, Stack Network, Performance, Availability, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-elasticache/actiondescribecacheparametergroups-get-openapi.md
- name: AWS ElastiCache API - Describe Cache Parameters
  x-api-slug: actiondescribecacheparameters-get
  description: |-
    Returns the detailed parameter list for a
                particular cache parameter group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: :///
  tags: Amazon Web Services, Cache, Stack Network, Performance, Availability, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-elasticache/actiondescribecacheparameters-get-openapi.md
- name: AWS ElastiCache API - Describe Cache Parameters
  x-api-slug: actiondescribecacheparameters-get
  description: |-
    Returns the detailed parameter list for a
                particular cache parameter group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: :///
  tags: Amazon Web Services, Cache, Stack Network, Performance, Availability, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-elasticache/actiondescribecacheparameters-get-openapi.md
- name: AWS ElastiCache API - Describe Cache Parameters
  x-api-slug: actiondescribecacheparameters-get
  description: |-
    Returns the detailed parameter list for a
                particular cache parameter group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: :///
  tags: Amazon Web Services, Cache, Stack Network, Performance, Availability, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-elasticache/actiondescribecacheparameters-get-openapi.md
- name: AWS ElastiCache API - Describe Cache Parameters
  x-api-slug: actiondescribecacheparameters-get
  description: |-
    Returns the detailed parameter list for a
                particular cache parameter group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: :///
  tags: Amazon Web Services, Cache, Stack Network, Performance, Availability, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-elasticache/actiondescribecacheparameters-get-openapi.md
- name: AWS ElastiCache API - Describe Cache Parameters
  x-api-slug: actiondescribecacheparameters-get
  description: |-
    Returns the detailed parameter list for a
                particular cache parameter group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: :///
  tags: Amazon Web Services, Cache, Stack Network, Performance, Availability, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-elasticache/actiondescribecacheparameters-get-openapi.md
- name: AWS ElastiCache API - Describe Cache Parameters
  x-api-slug: actiondescribecacheparameters-get
  description: |-
    Returns the detailed parameter list for a
                particular cache parameter group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: :///
  tags: Amazon Web Services, Cache, Stack Network, Performance, Availability, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-elasticache/actiondescribecacheparameters-get-openapi.md
- name: AWS ElastiCache API - Describe Cache Parameters
  x-api-slug: actiondescribecacheparameters-get
  description: |-
    Returns the detailed parameter list for a
                particular cache parameter group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: :///
  tags: Amazon Web Services, Cache, Stack Network, Performance, Availability, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-elasticache/actiondescribecacheparameters-get-openapi.md
- name: AWS ElastiCache API - Describe Cache Security Groups
  x-api-slug: actiondescribecachesecuritygroups-get
  description: |-
    Returns a list of cache security group
                descriptions.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: :///
  tags: Amazon Web Services, Cache, Stack Network, Performance, Availability, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-elasticache/actiondescribecachesecuritygroups-get-openapi.md
- name: AWS ElastiCache API - Describe Cache Security Groups
  x-api-slug: actiondescribecachesecuritygroups-get
  description: |-
    Returns a list of cache security group
                descriptions.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: :///
  tags: Amazon Web Services, Cache, Stack Network, Performance, Availability, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-elasticache/actiondescribecachesecuritygroups-get-openapi.md
- name: AWS ElastiCache API - Describe Cache Security Groups
  x-api-slug: actiondescribecachesecuritygroups-get
  description: |-
    Returns a list of cache security group
                descriptions.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: :///
  tags: Amazon Web Services, Cache, Stack Network, Performance, Availability, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-elasticache/actiondescribecachesecuritygroups-get-openapi.md
- name: AWS ElastiCache API - Describe Cache Security Groups
  x-api-slug: actiondescribecachesecuritygroups-get
  description: |-
    Returns a list of cache security group
                descriptions.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: :///
  tags: Amazon Web Services, Cache, Stack Network, Performance, Availability, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-elasticache/actiondescribecachesecuritygroups-get-openapi.md
- name: AWS ElastiCache API - Describe Cache Security Groups
  x-api-slug: actiondescribecachesecuritygroups-get
  description: |-
    Returns a list of cache security group
                descriptions.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: :///
  tags: Amazon Web Services, Cache, Stack Network, Performance, Availability, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-elasticache/actiondescribecachesecuritygroups-get-openapi.md
- name: AWS ElastiCache API - Describe Cache Security Groups
  x-api-slug: actiondescribecachesecuritygroups-get
  description: |-
    Returns a list of cache security group
                descriptions.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: :///
  tags: Amazon Web Services, Cache, Stack Network, Performance, Availability, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-elasticache/actiondescribecachesecuritygroups-get-openapi.md
- name: AWS ElastiCache API - Describe Cache Security Groups
  x-api-slug: actiondescribecachesecuritygroups-get
  description: |-
    Returns a list of cache security group
                descriptions.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: :///
  tags: Amazon Web Services, Cache, Stack Network, Performance, Availability, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-elasticache/actiondescribecachesecuritygroups-get-openapi.md
- name: AWS ElastiCache API - Describe Cache Subnet Groups
  x-api-slug: actiondescribecachesubnetgroups-get
  description: |-
    Returns a list of cache subnet group
                descriptions.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: :///
  tags: Amazon Web Services, Cache, Stack Network, Performance, Availability, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-elasticache/actiondescribecachesubnetgroups-get-openapi.md
- name: AWS ElastiCache API - Describe Cache Subnet Groups
  x-api-slug: actiondescribecachesubnetgroups-get
  description: |-
    Returns a list of cache subnet group
                descriptions.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: :///
  tags: Amazon Web Services, Cache, Stack Network, Performance, Availability, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-elasticache/actiondescribecachesubnetgroups-get-openapi.md
- name: AWS ElastiCache API - Describe Cache Subnet Groups
  x-api-slug: actiondescribecachesubnetgroups-get
  description: |-
    Returns a list of cache subnet group
                descriptions.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: :///
  tags: Amazon Web Services, Cache, Stack Network, Performance, Availability, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-elasticache/actiondescribecachesubnetgroups-get-openapi.md
- name: AWS ElastiCache API - Describe Cache Subnet Groups
  x-api-slug: actiondescribecachesubnetgroups-get
  description: |-
    Returns a list of cache subnet group
                descriptions.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: :///
  tags: Amazon Web Services, Cache, Stack Network, Performance, Availability, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-elasticache/actiondescribecachesubnetgroups-get-openapi.md
- name: AWS ElastiCache API - Describe Cache Subnet Groups
  x-api-slug: actiondescribecachesubnetgroups-get
  description: |-
    Returns a list of cache subnet group
                descriptions.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: :///
  tags: Amazon Web Services, Cache, Stack Network, Performance, Availability, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-elasticache/actiondescribecachesubnetgroups-get-openapi.md
- name: AWS ElastiCache API - Describe Cache Subnet Groups
  x-api-slug: actiondescribecachesubnetgroups-get
  description: |-
    Returns a list of cache subnet group
                descriptions.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: :///
  tags: Amazon Web Services, Cache, Stack Network, Performance, Availability, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-elasticache/actiondescribecachesubnetgroups-get-openapi.md
- name: AWS ElastiCache API - Describe Cache Subnet Groups
  x-api-slug: actiondescribecachesubnetgroups-get
  description: |-
    Returns a list of cache subnet group
                descriptions.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: :///
  tags: Amazon Web Services, Cache, Stack Network, Performance, Availability, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-elasticache/actiondescribecachesubnetgroups-get-openapi.md
- name: AWS ElastiCache API - Describe Engine Default Parameters
  x-api-slug: actiondescribeenginedefaultparameters-get
  description: |-
    Returns the default engine and
                system parameter information for the specified cache engine.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: :///
  tags: Amazon Web Services, Cache, Stack Network, Performance, Availability, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-elasticache/actiondescribeenginedefaultparameters-get-openapi.md
- name: AWS ElastiCache API - Describe Engine Default Parameters
  x-api-slug: actiondescribeenginedefaultparameters-get
  description: |-
    Returns the default engine and
                system parameter information for the specified cache engine.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: :///
  tags: Amazon Web Services, Cache, Stack Network, Performance, Availability, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-elasticache/actiondescribeenginedefaultparameters-get-openapi.md
- name: AWS ElastiCache API - Describe Engine Default Parameters
  x-api-slug: actiondescribeenginedefaultparameters-get
  description: |-
    Returns the default engine and
                system parameter information for the specified cache engine.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: :///
  tags: Amazon Web Services, Cache, Stack Network, Performance, Availability, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-elasticache/actiondescribeenginedefaultparameters-get-openapi.md
- name: AWS ElastiCache API - Describe Engine Default Parameters
  x-api-slug: actiondescribeenginedefaultparameters-get
  description: |-
    Returns the default engine and
                system parameter information for the specified cache engine.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: :///
  tags: Amazon Web Services, Cache, Stack Network, Performance, Availability, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-elasticache/actiondescribeenginedefaultparameters-get-openapi.md
- name: AWS ElastiCache API - Describe Engine Default Parameters
  x-api-slug: actiondescribeenginedefaultparameters-get
  description: |-
    Returns the default engine and
                system parameter information for the specified cache engine.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: :///
  tags: Amazon Web Services, Cache, Stack Network, Performance, Availability, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-elasticache/actiondescribeenginedefaultparameters-get-openapi.md
- name: AWS ElastiCache API - Describe Engine Default Parameters
  x-api-slug: actiondescribeenginedefaultparameters-get
  description: |-
    Returns the default engine and
                system parameter information for the specified cache engine.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: :///
  tags: Amazon Web Services, Cache, Stack Network, Performance, Availability, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-elasticache/actiondescribeenginedefaultparameters-get-openapi.md
- name: AWS ElastiCache API - Describe Engine Default Parameters
  x-api-slug: actiondescribeenginedefaultparameters-get
  description: |-
    Returns the default engine and
                system parameter information for the specified cache engine.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: :///
  tags: Amazon Web Services, Cache, Stack Network, Performance, Availability, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-elasticache/actiondescribeenginedefaultparameters-get-openapi.md
- name: AWS ElastiCache API - Describe Engine Default Parameters
  x-api-slug: actiondescribeenginedefaultparameters-get
  description: |-
    Returns the default engine and
                system parameter information for the specified cache engine.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: :///
  tags: Amazon Web Services, Cache, Stack Network, Performance, Availability, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-elasticache/actiondescribeenginedefaultparameters-get-openapi.md
- name: AWS ElastiCache API - Describe Events
  x-api-slug: actiondescribeevents-get
  description: |-
    Returns events related to cache clusters, cache
                security groups, and cache parameter groups.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: :///
  tags: Amazon Web Services, Cache, Stack Network, Performance, Availability, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-elasticache/actiondescribeevents-get-openapi.md
- name: AWS ElastiCache API - Describe Events
  x-api-slug: actiondescribeevents-get
  description: |-
    Returns events related to cache clusters, cache
                security groups, and cache parameter groups.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: :///
  tags: Amazon Web Services, Cache, Stack Network, Performance, Availability, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-elasticache/actiondescribeevents-get-openapi.md
- name: AWS ElastiCache API - Describe Events
  x-api-slug: actiondescribeevents-get
  description: |-
    Returns events related to cache clusters, cache
                security groups, and cache parameter groups.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: :///
  tags: Amazon Web Services, Cache, Stack Network, Performance, Availability, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-elasticache/actiondescribeevents-get-openapi.md
- name: AWS ElastiCache API - Describe Events
  x-api-slug: actiondescribeevents-get
  description: |-
    Returns events related to cache clusters, cache
                security groups, and cache parameter groups.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: :///
  tags: Amazon Web Services, Cache, Stack Network, Performance, Availability, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-elasticache/actiondescribeevents-get-openapi.md
- name: AWS ElastiCache API - Describe Events
  x-api-slug: actiondescribeevents-get
  description: |-
    Returns events related to cache clusters, cache
                security groups, and cache parameter groups.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: :///
  tags: Amazon Web Services, Cache, Stack Network, Performance, Availability, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-elasticache/actiondescribeevents-get-openapi.md
- name: AWS ElastiCache API - Describe Events
  x-api-slug: actiondescribeevents-get
  description: |-
    Returns events related to cache clusters, cache
                security groups, and cache parameter groups.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: :///
  tags: Amazon Web Services, Cache, Stack Network, Performance, Availability, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-elasticache/actiondescribeevents-get-openapi.md
- name: AWS ElastiCache API - Describe Events
  x-api-slug: actiondescribeevents-get
  description: |-
    Returns events related to cache clusters, cache
                security groups, and cache parameter groups.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: :///
  tags: Amazon Web Services, Cache, Stack Network, Performance, Availability, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-elasticache/actiondescribeevents-get-openapi.md
- name: AWS ElastiCache API - Describe Events
  x-api-slug: actiondescribeevents-get
  description: |-
    Returns events related to cache clusters, cache
                security groups, and cache parameter groups.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: :///
  tags: Amazon Web Services, Cache, Stack Network, Performance, Availability, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-elasticache/actiondescribeevents-get-openapi.md
- name: AWS ElastiCache API - Describe Replication Groups
  x-api-slug: actiondescribereplicationgroups-get
  description: |-
    Returns information about a particular
                replication group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: :///
  tags: Amazon Web Services, Cache, Stack Network, Performance, Availability, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-elasticache/actiondescribereplicationgroups-get-openapi.md
- name: AWS ElastiCache API - Describe Replication Groups
  x-api-slug: actiondescribereplicationgroups-get
  description: |-
    Returns information about a particular
                replication group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: :///
  tags: Amazon Web Services, Cache, Stack Network, Performance, Availability, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-elasticache/actiondescribereplicationgroups-get-openapi.md
- name: AWS ElastiCache API - Describe Replication Groups
  x-api-slug: actiondescribereplicationgroups-get
  description: |-
    Returns information about a particular
                replication group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: :///
  tags: Amazon Web Services, Cache, Stack Network, Performance, Availability, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-elasticache/actiondescribereplicationgroups-get-openapi.md
- name: AWS ElastiCache API - Describe Replication Groups
  x-api-slug: actiondescribereplicationgroups-get
  description: |-
    Returns information about a particular
                replication group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: :///
  tags: Amazon Web Services, Cache, Stack Network, Performance, Availability, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-elasticache/actiondescribereplicationgroups-get-openapi.md
- name: AWS ElastiCache API - Describe Replication Groups
  x-api-slug: actiondescribereplicationgroups-get
  description: |-
    Returns information about a particular
                replication group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: :///
  tags: Amazon Web Services, Cache, Stack Network, Performance, Availability, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-elasticache/actiondescribereplicationgroups-get-openapi.md
- name: AWS ElastiCache API - Describe Replication Groups
  x-api-slug: actiondescribereplicationgroups-get
  description: |-
    Returns information about a particular
                replication group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: :///
  tags: Amazon Web Services, Cache, Stack Network, Performance, Availability, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-elasticache/actiondescribereplicationgroups-get-openapi.md
- name: AWS ElastiCache API - Describe Replication Groups
  x-api-slug: actiondescribereplicationgroups-get
  description: |-
    Returns information about a particular
                replication group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: :///
  tags: Amazon Web Services, Cache, Stack Network, Performance, Availability, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-elasticache/actiondescribereplicationgroups-get-openapi.md
- name: AWS ElastiCache API - Describe Replication Groups
  x-api-slug: actiondescribereplicationgroups-get
  description: |-
    Returns information about a particular
                replication group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: :///
  tags: Amazon Web Services, Cache, Stack Network, Performance, Availability, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-elasticache/actiondescribereplicationgroups-get-openapi.md
- name: AWS ElastiCache API - Describe Replication Groups
  x-api-slug: actiondescribereplicationgroups-get
  description: |-
    Returns information about a particular
                replication group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: :///
  tags: Amazon Web Services, Cache, Stack Network, Performance, Availability, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-elasticache/actiondescribereplicationgroups-get-openapi.md
- name: AWS ElastiCache API - Describe Reserved Cache Nodes
  x-api-slug: actiondescribereservedcachenodes-get
  description: |-
    Returns information about reserved cache
                nodes for this account, or about a specified reserved cache node.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: :///
  tags: Amazon Web Services, Cache, Stack Network, Performance, Availability, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-elasticache/actiondescribereservedcachenodes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-elasticache/actiondescribereservedcachenodes-get-openapi.md
- name: AWS ElastiCache API - Describe Reserved Cache Nodes
  x-api-slug: actiondescribereservedcachenodes-get
  description: |-
    Returns information about reserved cache
                nodes for this account, or about a specified reserved cache node.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: :///
  tags: Amazon Web Services, Cache, Stack Network, Performance, Availability, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-elasticache/actiondescribereservedcachenodes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-elasticache/actiondescribereservedcachenodes-get-openapi.md
- name: AWS ElastiCache API - Describe Reserved Cache Nodes
  x-api-slug: actiondescribereservedcachenodes-get
  description: |-
    Returns information about reserved cache
                nodes for this account, or about a specified reserved cache node.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: :///
  tags: Amazon Web Services, Cache, Stack Network, Performance, Availability, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-elasticache/actiondescribereservedcachenodes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-elasticache/actiondescribereservedcachenodes-get-openapi.md
- name: AWS ElastiCache API - Describe Reserved Cache Nodes
  x-api-slug: actiondescribereservedcachenodes-get
  description: |-
    Returns information about reserved cache
                nodes for this account, or about a specified reserved cache node.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: :///
  tags: Amazon Web Services, Cache, Stack Network, Performance, Availability, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-elasticache/actiondescribereservedcachenodes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-elasticache/actiondescribereservedcachenodes-get-openapi.md
- name: AWS ElastiCache API - Describe Reserved Cache Nodes
  x-api-slug: actiondescribereservedcachenodes-get
  description: |-
    Returns information about reserved cache
                nodes for this account, or about a specified reserved cache node.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: :///
  tags: Amazon Web Services, Cache, Stack Network, Performance, Availability, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-elasticache/actiondescribereservedcachenodes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-elasticache/actiondescribereservedcachenodes-get-openapi.md
- name: AWS ElastiCache API - Describe Reserved Cache Nodes
  x-api-slug: actiondescribereservedcachenodes-get
  description: |-
    Returns information about reserved cache
                nodes for this account, or about a specified reserved cache node.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: :///
  tags: Amazon Web Services, Cache, Stack Network, Performance, Availability, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-elasticache/actiondescribereservedcachenodes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-elasticache/actiondescribereservedcachenodes-get-openapi.md
- name: AWS ElastiCache API - Describe Reserved Cache Nodes
  x-api-slug: actiondescribereservedcachenodes-get
  description: |-
    Returns information about reserved cache
                nodes for this account, or about a specified reserved cache node.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: :///
  tags: Amazon Web Services, Cache, Stack Network, Performance, Availability, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-elasticache/actiondescribereservedcachenodes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-elasticache/actiondescribereservedcachenodes-get-openapi.md
- name: AWS ElastiCache API - Describe Reserved Cache Nodes
  x-api-slug: actiondescribereservedcachenodes-get
  description: |-
    Returns information about reserved cache
                nodes for this account, or about a specified reserved cache node.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: :///
  tags: Amazon Web Services, Cache, Stack Network, Performance, Availability, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-elasticache/actiondescribereservedcachenodes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-elasticache/actiondescribereservedcachenodes-get-openapi.md
- name: AWS ElastiCache API - Describe Reserved Cache Nodes
  x-api-slug: actiondescribereservedcachenodes-get
  description: |-
    Returns information about reserved cache
                nodes for this account, or about a specified reserved cache node.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: :///
  tags: Amazon Web Services, Cache, Stack Network, Performance, Availability, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-elasticache/actiondescribereservedcachenodes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-elasticache/actiondescribereservedcachenodes-get-openapi.md
- name: AWS ElastiCache API - Describe Reserved Cache Nodes Offerings
  x-api-slug: actiondescribereservedcachenodesofferings-get
  description: |-
    Lists available reserved cache
                node offerings.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: :///
  tags: Amazon Web Services, Cache, Stack Network, Performance, Availability, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-elasticache/actiondescribereservedcachenodesofferings-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-elasticache/actiondescribereservedcachenodesofferings-get-openapi.md
- name: AWS ElastiCache API - Describe Reserved Cache Nodes Offerings
  x-api-slug: actiondescribereservedcachenodesofferings-get
  description: |-
    Lists available reserved cache
                node offerings.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: :///
  tags: Amazon Web Services, Cache, Stack Network, Performance, Availability, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-elasticache/actiondescribereservedcachenodesofferings-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-elasticache/actiondescribereservedcachenodesofferings-get-openapi.md
- name: AWS ElastiCache API - Describe Reserved Cache Nodes Offerings
  x-api-slug: actiondescribereservedcachenodesofferings-get
  description: |-
    Lists available reserved cache
                node offerings.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: :///
  tags: Amazon Web Services, Cache, Stack Network, Performance, Availability, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-elasticache/actiondescribereservedcachenodesofferings-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-elasticache/actiondescribereservedcachenodesofferings-get-openapi.md
- name: AWS ElastiCache API - Describe Reserved Cache Nodes Offerings
  x-api-slug: actiondescribereservedcachenodesofferings-get
  description: |-
    Lists available reserved cache
                node offerings.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: :///
  tags: Amazon Web Services, Cache, Stack Network, Performance, Availability, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-elasticache/actiondescribereservedcachenodesofferings-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-elasticache/actiondescribereservedcachenodesofferings-get-openapi.md
- name: AWS ElastiCache API - Describe Reserved Cache Nodes Offerings
  x-api-slug: actiondescribereservedcachenodesofferings-get
  description: |-
    Lists available reserved cache
                node offerings.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: :///
  tags: Amazon Web Services, Cache, Stack Network, Performance, Availability, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-elasticache/actiondescribereservedcachenodesofferings-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-elasticache/actiondescribereservedcachenodesofferings-get-openapi.md
- name: AWS ElastiCache API - Describe Reserved Cache Nodes Offerings
  x-api-slug: actiondescribereservedcachenodesofferings-get
  description: |-
    Lists available reserved cache
                node offerings.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: :///
  tags: Amazon Web Services, Cache, Stack Network, Performance, Availability, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-elasticache/actiondescribereservedcachenodesofferings-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-elasticache/actiondescribereservedcachenodesofferings-get-openapi.md
- name: AWS ElastiCache API - Describe Reserved Cache Nodes Offerings
  x-api-slug: actiondescribereservedcachenodesofferings-get
  description: |-
    Lists available reserved cache
                node offerings.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: :///
  tags: Amazon Web Services, Cache, Stack Network, Performance, Availability, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-elasticache/actiondescribereservedcachenodesofferings-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-elasticache/actiondescribereservedcachenodesofferings-get-openapi.md
- name: AWS ElastiCache API - Describe Reserved Cache Nodes Offerings
  x-api-slug: actiondescribereservedcachenodesofferings-get
  description: |-
    Lists available reserved cache
                node offerings.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: :///
  tags: Amazon Web Services, Cache, Stack Network, Performance, Availability, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-elasticache/actiondescribereservedcachenodesofferings-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-elasticache/actiondescribereservedcachenodesofferings-get-openapi.md
- name: AWS ElastiCache API - Describe Reserved Cache Nodes Offerings
  x-api-slug: actiondescribereservedcachenodesofferings-get
  description: |-
    Lists available reserved cache
                node offerings.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: :///
  tags: Amazon Web Services, Cache, Stack Network, Performance, Availability, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-elasticache/actiondescribereservedcachenodesofferings-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-elasticache/actiondescribereservedcachenodesofferings-get-openapi.md
- name: AWS ElastiCache API - Describe Snapshots
  x-api-slug: actiondescribesnapshots-get
  description: Returns information about cache cluster or replication group snapshots.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: :///
  tags: Amazon Web Services, Cache, Stack Network, Performance, Availability, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-elasticache/actiondescribesnapshots-get-openapi.md
- name: AWS ElastiCache API - Describe Snapshots
  x-api-slug: actiondescribesnapshots-get
  description: Returns information about cache cluster or replication group snapshots.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: :///
  tags: Amazon Web Services, Cache, Stack Network, Performance, Availability, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-elasticache/actiondescribesnapshots-get-openapi.md
- name: AWS ElastiCache API - Describe Snapshots
  x-api-slug: actiondescribesnapshots-get
  description: Returns information about cache cluster or replication group snapshots.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: :///
  tags: Amazon Web Services, Cache, Stack Network, Performance, Availability, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-elasticache/actiondescribesnapshots-get-openapi.md
- name: AWS ElastiCache API - Describe Snapshots
  x-api-slug: actiondescribesnapshots-get
  description: Returns information about cache cluster or replication group snapshots.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: :///
  tags: Amazon Web Services, Cache, Stack Network, Performance, Availability, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-elasticache/actiondescribesnapshots-get-openapi.md
- name: AWS ElastiCache API - Describe Snapshots
  x-api-slug: actiondescribesnapshots-get
  description: Returns information about cache cluster or replication group snapshots.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: :///
  tags: Amazon Web Services, Cache, Stack Network, Performance, Availability, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-elasticache/actiondescribesnapshots-get-openapi.md
- name: AWS ElastiCache API - Describe Snapshots
  x-api-slug: actiondescribesnapshots-get
  description: Returns information about cache cluster or replication group snapshots.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: :///
  tags: Amazon Web Services, Cache, Stack Network, Performance, Availability, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-elasticache/actiondescribesnapshots-get-openapi.md
- name: AWS ElastiCache API - Describe Snapshots
  x-api-slug: actiondescribesnapshots-get
  description: Returns information about cache cluster or replication group snapshots.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: :///
  tags: Amazon Web Services, Cache, Stack Network, Performance, Availability, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-elasticache/actiondescribesnapshots-get-openapi.md
- name: AWS ElastiCache API - Describe Snapshots
  x-api-slug: actiondescribesnapshots-get
  description: Returns information about cache cluster or replication group snapshots.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: :///
  tags: Amazon Web Services, Cache, Stack Network, Performance, Availability, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-elasticache/actiondescribesnapshots-get-openapi.md
- name: AWS ElastiCache API - Describe Snapshots
  x-api-slug: actiondescribesnapshots-get
  description: Returns information about cache cluster or replication group snapshots.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonElasticCache.png
  humanURL: https://aws.amazon.com/elasticache/
  baseURL: :///
  tags: Amazon Web Services, Cache, Stack Network, Performance, Availability, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/descriptions/master/_listings/aws-elasticache/actiondescribesnapshots-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://aws.elastic.mapreduce.api.gallery.streamdata.io
- type: x-api-stack
  url: http://aws.elasticache.stack.network
- type: x-documentation
  url: http://docs.aws.amazon.com/AmazonElastiCache/latest/APIReference/Welcome.html
- type: x-faq
  url: https://aws.amazon.com/elasticache/faqs/
- type: x-getting-started
  url: https://aws.amazon.com/elasticache/getting-started/
- type: x-pricing
  url: https://aws.amazon.com/elasticache/pricing/
- type: x-resources
  url: https://aws.amazon.com/elasticache/developer-resources/
- type: x-testimonials
  url: https://aws.amazon.com/elasticache/testimonials/
- type: x-website
  url: https://aws.amazon.com/elasticache/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---