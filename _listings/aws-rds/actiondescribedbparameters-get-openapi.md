---
swagger: "2.0"
x-collection-name: AWS RDS
x-complete: 0
info:
  title: Amazon RDS API Describe D B Parameters
  version: 1.0.0
  description: Returns the detailed parameter list for a particular DB parameter group.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=DescribeAccountAttributes:
    get:
      summary: Describe Account Attributes
      description: Lists all of the attributes for a customer account.
      operationId: describeaccountattributes
      x-api-path-slug: actiondescribeaccountattributes-get
      parameters:
      - in: query
        name: AccountQuotas.AccountQuota.N
        description: A list of AccountQuota objects
        type: string
      responses:
        200:
          description: OK
      tags:
      - Accounts
  /?Action=DescribeCertificates:
    get:
      summary: Describe Certificates
      description: Lists the set of CA certificates provided by Amazon RDS for this
        AWS account.
      operationId: describecertificates
      x-api-path-slug: actiondescribecertificates-get
      parameters:
      - in: query
        name: CertificateIdentifier
        description: The user-supplied certificate identifier
        type: string
      - in: query
        name: Filters.Filter.N
        description: This parameter is not currently supported
        type: string
      - in: query
        name: Marker
        description: An optional pagination token provided by a previous        DescribeCertificates
          request
        type: string
      - in: query
        name: MaxRecords
        description: The maximum number of records to include in the response
        type: string
      responses:
        200:
          description: OK
      tags:
      - Certificates
  /?Action=DescribeDBClusterParameterGroups:
    get:
      summary: Describe D B Cluster Parameter Groups
      description: Returns a list of DBClusterParameterGroup descriptions.
      operationId: describedbclusterparametergroups
      x-api-path-slug: actiondescribedbclusterparametergroups-get
      parameters:
      - in: query
        name: DBClusterParameterGroupName
        description: The name of a specific DB cluster parameter group to return details
          for
        type: string
      - in: query
        name: Filters.Filter.N
        description: This parameter is not currently supported
        type: string
      - in: query
        name: Marker
        description: An optional pagination token provided by a previous        DescribeDBClusterParameterGroups
          request
        type: string
      - in: query
        name: MaxRecords
        description: The maximum number of records to include in the response
        type: string
      responses:
        200:
          description: OK
      tags:
      - Cluster Parameter Groups
  /?Action=DescribeDBClusterParameters:
    get:
      summary: Describe D B Cluster Parameters
      description: Returns the detailed parameter list for a particular DB cluster
        parameter group.
      operationId: describedbclusterparameters
      x-api-path-slug: actiondescribedbclusterparameters-get
      parameters:
      - in: query
        name: DBClusterParameterGroupName
        description: The name of a specific DB cluster parameter group to return parameter
          details for
        type: string
      - in: query
        name: Filters.Filter.N
        description: This parameter is not currently supported
        type: string
      - in: query
        name: Marker
        description: An optional pagination token provided by a previous      DescribeDBClusterParameters
          request
        type: string
      - in: query
        name: MaxRecords
        description: The maximum number of records to include in the response
        type: string
      - in: query
        name: Source
        description: A value that indicates to return only parameters for a specific
          source
        type: string
      responses:
        200:
          description: OK
      tags:
      - Cluster Parameters
  /?Action=DescribeDBClusters:
    get:
      summary: Describe D B Clusters
      description: Returns information about provisioned Aurora DB clusters.
      operationId: describedbclusters
      x-api-path-slug: actiondescribedbclusters-get
      parameters:
      - in: query
        name: DBClusterIdentifier
        description: The user-supplied DB cluster identifier
        type: string
      - in: query
        name: Filters.Filter.N
        description: A filter that specifies one or more DB clusters to describe
        type: string
      - in: query
        name: Marker
        description: An optional pagination token provided by a previous            DescribeDBClusters
          request
        type: string
      - in: query
        name: MaxRecords
        description: The maximum number of records to include in the response
        type: string
      responses:
        200:
          description: OK
      tags:
      - Clusters
  /?Action=DescribeDBClusterSnapshotAttributes:
    get:
      summary: Describe D B Cluster Snapshot Attributes
      description: Returns a list of DB cluster snapshot attribute names and values
        for a manual DB cluster snapshot.
      operationId: describedbclustersnapshotattributes
      x-api-path-slug: actiondescribedbclustersnapshotattributes-get
      parameters:
      - in: query
        name: DBClusterSnapshotIdentifier
        description: The identifier for the DB cluster snapshot to describe the attributes
          for
        type: string
      responses:
        200:
          description: OK
      tags:
      - Cluster Snapshots
  /?Action=DescribeDBClusterSnapshots:
    get:
      summary: Describe D B Cluster Snapshots
      description: Returns information about DB cluster snapshots.
      operationId: describedbclustersnapshots
      x-api-path-slug: actiondescribedbclustersnapshots-get
      parameters:
      - in: query
        name: DBClusterIdentifier
        description: The ID of the DB cluster to retrieve the list of DB cluster snapshots
          for
        type: string
      - in: query
        name: DBClusterSnapshotIdentifier
        description: A specific DB cluster snapshot identifier to describe
        type: string
      - in: query
        name: Filters.Filter.N
        description: This parameter is not currently supported
        type: string
      - in: query
        name: IncludePublic
        description: Set this value to true to include manual DB cluster snapshots
          that are public and can be copied             or restored by any AWS account,
          otherwise set this value to false
        type: string
      - in: query
        name: IncludeShared
        description: Set this value to true to include shared manual DB cluster snapshots             from
          other AWS accounts that this AWS account has been given             permission
          to copy or restore, otherwise set this value to false
        type: string
      - in: query
        name: Marker
        description: An optional pagination token provided by a previous            DescribeDBClusterSnapshots
          request
        type: string
      - in: query
        name: MaxRecords
        description: The maximum number of records to include in the response
        type: string
      - in: query
        name: SnapshotType
        description: The type of DB cluster snapshots to be returned
        type: string
      responses:
        200:
          description: OK
      tags:
      - Cluster Snapshots
  /?Action=DescribeDBEngineVersions:
    get:
      summary: Describe D B Engine Versions
      description: Returns a list of the available DB engines.
      operationId: describedbengineversions
      x-api-path-slug: actiondescribedbengineversions-get
      parameters:
      - in: query
        name: DBParameterGroupFamily
        description: The name of a specific DB parameter group family to return details
          for
        type: string
      - in: query
        name: DefaultOnly
        description: Indicates that only the default version of the specified engine
          or engine and major version combination is returned
        type: string
      - in: query
        name: Engine
        description: The database engine to return
        type: string
      - in: query
        name: EngineVersion
        description: The database engine version to return
        type: string
      - in: query
        name: Filters.Filter.N
        description: Not currently supported
        type: string
      - in: query
        name: ListSupportedCharacterSets
        description: If this parameter is specified           and the requested engine
          supports the CharacterSetName parameter for CreateDBInstance,           the
          response includes a list of supported character sets for each engine version
        type: string
      - in: query
        name: ListSupportedTimezones
        description: If this parameter is specified             and the requested
          engine supports the TimeZone parameter for CreateDBInstance,             the
          response includes a list of supported time zones for each engine version
        type: string
      - in: query
        name: Marker
        description: An optional pagination token provided by a previous request
        type: string
      - in: query
        name: MaxRecords
        description: The maximum number of records to include in the response
        type: string
      responses:
        200:
          description: OK
      tags:
      - Engines
  /?Action=DescribeDBInstances:
    get:
      summary: Describe D B Instances
      description: Returns information about provisioned RDS instances.
      operationId: describedbinstances
      x-api-path-slug: actiondescribedbinstances-get
      parameters:
      - in: query
        name: DBInstanceIdentifier
        description: The user-supplied instance identifier
        type: string
      - in: query
        name: Filters.Filter.N
        description: A filter that specifies one or more DB instances to describe
        type: string
      - in: query
        name: Marker
        description: An optional pagination token provided by a previous        DescribeDBInstances
          request
        type: string
      - in: query
        name: MaxRecords
        description: The maximum number of records to include in the response
        type: string
      responses:
        200:
          description: OK
      tags:
      - Instances
  /?Action=DescribeDBLogFiles:
    get:
      summary: Describe D B Log Files
      description: Returns a list of DB log files for the DB instance.
      operationId: describedblogfiles
      x-api-path-slug: actiondescribedblogfiles-get
      parameters:
      - in: query
        name: DBInstanceIdentifier
        description: The customer-assigned name of the DB instance that contains the
          log files you want to list
        type: string
      - in: query
        name: FileLastWritten
        description: Filters the available log files for files written since the specified
          date, in POSIX timestamp format with milliseconds
        type: string
      - in: query
        name: FilenameContains
        description: Filters the available log files for log file names that contain
          the specified string
        type: string
      - in: query
        name: FileSize
        description: Filters the available log files for files larger than the specified
          size
        type: string
      - in: query
        name: Filters.Filter.N
        description: This parameter is not currently supported
        type: string
      - in: query
        name: Marker
        description: The pagination token provided in the previous request
        type: string
      - in: query
        name: MaxRecords
        description: The maximum number of records to include in the response
        type: string
      responses:
        200:
          description: OK
      tags:
      - Blog Files
  /?Action=DescribeDBParameterGroups:
    get:
      summary: Describe D B Parameter Groups
      description: Returns a list of DBParameterGroup descriptions.
      operationId: describedbparametergroups
      x-api-path-slug: actiondescribedbparametergroups-get
      parameters:
      - in: query
        name: DBParameterGroupName
        description: The name of a specific DB parameter group to return details for
        type: string
      - in: query
        name: Filters.Filter.N
        description: This parameter is not currently supported
        type: string
      - in: query
        name: Marker
        description: An optional pagination token provided by a previous        DescribeDBParameterGroups
          request
        type: string
      - in: query
        name: MaxRecords
        description: The maximum number of records to include in the response
        type: string
      responses:
        200:
          description: OK
      tags:
      - Parameter Groups
  /?Action=DescribeDBParameters:
    get:
      summary: Describe D B Parameters
      description: Returns the detailed parameter list for a particular DB parameter
        group.
      operationId: describedbparameters
      x-api-path-slug: actiondescribedbparameters-get
      parameters:
      - in: query
        name: DBParameterGroupName
        description: The name of a specific DB parameter group to return details for
        type: string
      - in: query
        name: Filters.Filter.N
        description: This parameter is not currently supported
        type: string
      - in: query
        name: Marker
        description: An optional pagination token provided by a previous        DescribeDBParameters
          request
        type: string
      - in: query
        name: MaxRecords
        description: The maximum number of records to include in the response
        type: string
      - in: query
        name: Source
        description: The parameter types to return
        type: string
      responses:
        200:
          description: OK
      tags:
      - Parameters
  /?Action=DescribeDBSecurityGroups:
    get:
      summary: Describe D B Security Groups
      description: Returns a list of DBSecurityGroup descriptions.
      operationId: describedbsecuritygroups
      x-api-path-slug: actiondescribedbsecuritygroups-get
      parameters:
      - in: query
        name: DBSecurityGroupName
        description: The name of the DB security group to return details for
        type: string
      - in: query
        name: Filters.Filter.N
        description: This parameter is not currently supported
        type: string
      - in: query
        name: Marker
        description: An optional pagination token provided by a previous        DescribeDBSecurityGroups
          request
        type: string
      - in: query
        name: MaxRecords
        description: The maximum number of records to include in the response
        type: string
      responses:
        200:
          description: OK
      tags:
      - Security Groups
  /?Action=DescribeDBSnapshotAttributes:
    get:
      summary: Describe D B Snapshot Attributes
      description: Returns a list of DB snapshot attribute names and values for a
        manual DB snapshot.
      operationId: describedbsnapshotattributes
      x-api-path-slug: actiondescribedbsnapshotattributes-get
      parameters:
      - in: query
        name: DBSnapshotIdentifier
        description: The identifier for the DB snapshot to describe the attributes
          for
        type: string
      responses:
        200:
          description: OK
      tags:
      - Snapshots
  /?Action=DescribeDBSnapshots:
    get:
      summary: Describe D B Snapshots
      description: Returns information about DB snapshots.
      operationId: describedbsnapshots
      x-api-path-slug: actiondescribedbsnapshots-get
      parameters:
      - in: query
        name: DBInstanceIdentifier
        description: The ID of the DB instance to retrieve the list of DB snapshots
          for
        type: string
      - in: query
        name: DBSnapshotIdentifier
        description: A specific DB snapshot identifier to describe
        type: string
      - in: query
        name: Filters.Filter.N
        description: This parameter is not currently supported
        type: string
      - in: query
        name: IncludePublic
        description: Set this value to true to include manual DB snapshots that are
          public and can be copied or restored           by any AWS account, otherwise
          set this value to false
        type: string
      - in: query
        name: IncludeShared
        description: Set this value to true to include shared manual DB snapshots
          from other           AWS accounts that this AWS account has been given permission
          to copy or restore, otherwise set this value to false
        type: string
      - in: query
        name: Marker
        description: An optional pagination token provided by a previous        DescribeDBSnapshots
          request
        type: string
      - in: query
        name: MaxRecords
        description: The maximum number of records to include in the response
        type: string
      - in: query
        name: SnapshotType
        description: The type of snapshots to be returned
        type: string
      responses:
        200:
          description: OK
      tags:
      - Snapshots
  /?Action=DescribeDBSubnetGroups:
    get:
      summary: Describe D B Subnet Groups
      description: Returns a list of DBSubnetGroup descriptions.
      operationId: describedbsubnetgroups
      x-api-path-slug: actiondescribedbsubnetgroups-get
      parameters:
      - in: query
        name: DBSubnetGroupName
        description: The name of the DB subnet group to return details for
        type: string
      - in: query
        name: Filters.Filter.N
        description: This parameter is not currently supported
        type: string
      - in: query
        name: Marker
        description: An optional pagination token provided by a previous DescribeDBSubnetGroups
          request
        type: string
      - in: query
        name: MaxRecords
        description: The maximum number of records to include in the response
        type: string
      responses:
        200:
          description: OK
      tags:
      - Subnet Groups
  /?Action=DescribeEngineDefaultClusterParameters:
    get:
      summary: Describe Engine Default Cluster Parameters
      description: Returns the default engine and system parameter information for
        the cluster database engine.
      operationId: describeenginedefaultclusterparameters
      x-api-path-slug: actiondescribeenginedefaultclusterparameters-get
      parameters:
      - in: query
        name: DBParameterGroupFamily
        description: The name of the DB cluster parameter group family to return engine
          parameter information for
        type: string
      - in: query
        name: Filters.Filter.N
        description: This parameter is not currently supported
        type: string
      - in: query
        name: Marker
        description: An optional pagination token provided by a previous      DescribeEngineDefaultClusterParameters
          request
        type: string
      - in: query
        name: MaxRecords
        description: The maximum number of records to include in the response
        type: string
      responses:
        200:
          description: OK
      tags:
      - Default Cluster Parameters
  /?Action=DescribeEngineDefaultParameters:
    get:
      summary: Describe Engine Default Parameters
      description: Returns the default engine and system parameter information for
        the specified database engine.
      operationId: describeenginedefaultparameters
      x-api-path-slug: actiondescribeenginedefaultparameters-get
      parameters:
      - in: query
        name: DBParameterGroupFamily
        description: The name of the DB parameter group family
        type: string
      - in: query
        name: Filters.Filter.N
        description: Not currently supported
        type: string
      - in: query
        name: Marker
        description: An optional pagination token provided by a previous        DescribeEngineDefaultParameters
          request
        type: string
      - in: query
        name: MaxRecords
        description: The maximum number of records to include in the response
        type: string
      responses:
        200:
          description: OK
      tags:
      - Default Parameters
  /?Action=DescribeEventCategories:
    get:
      summary: Describe Event Categories
      description: Displays a list of categories for all event source types, or, if
        specified, for a specified source type.
      operationId: describeeventcategories
      x-api-path-slug: actiondescribeeventcategories-get
      parameters:
      - in: query
        name: Filters.Filter.N
        description: This parameter is not currently supported
        type: string
      - in: query
        name: SourceType
        description: The type of source that will be generating the events
        type: string
      responses:
        200:
          description: OK
      tags:
      - Event Categories
  /?Action=DescribeEvents:
    get:
      summary: Describe Events
      description: Returns events related to DB instances, DB security groups, DB
        snapshots, and DB parameter groups for the past 14 days.
      operationId: describeevents
      x-api-path-slug: actiondescribeevents-get
      parameters:
      - in: query
        name: Duration
        description: The number of minutes to retrieve events for
        type: string
      - in: query
        name: EndTime
        description: The end of the time interval for which to retrieve events,        specified
          in ISO 8601 format
        type: string
      - in: query
        name: EventCategories.EventCategory.N
        description: A list of event categories that trigger notifications for a event
          notification subscription
        type: string
      - in: query
        name: Filters.Filter.N
        description: This parameter is not currently supported
        type: string
      - in: query
        name: Marker
        description: An optional pagination token provided by a previous        DescribeEvents
          request
        type: string
      - in: query
        name: MaxRecords
        description: The maximum number of records to include in the response
        type: string
      - in: query
        name: SourceIdentifier
        description: The identifier of the event source for which events will be returned
        type: string
      - in: query
        name: SourceType
        description: The event source to retrieve events for
        type: string
      - in: query
        name: StartTime
        description: The beginning of the time interval to retrieve events for,        specified
          in ISO 8601 format
        type: string
      responses:
        200:
          description: OK
      tags:
      - Events
  /?Action=DescribeEventSubscriptions:
    get:
      summary: Describe Event Subscriptions
      description: Lists all the subscription descriptions for a customer account.
      operationId: describeeventsubscriptions
      x-api-path-slug: actiondescribeeventsubscriptions-get
      parameters:
      - in: query
        name: Filters.Filter.N
        description: This parameter is not currently supported
        type: string
      - in: query
        name: Marker
        description: An optional pagination token provided by a previous            DescribeOrderableDBInstanceOptions
          request
        type: string
      - in: query
        name: MaxRecords
        description: The maximum number of records to include in the response
        type: string
      - in: query
        name: SubscriptionName
        description: The name of the RDS event notification subscription you want
          to describe
        type: string
      responses:
        200:
          description: OK
      tags:
      - Event Subscriptions
  /?Action=DescribeOptionGroupOptions:
    get:
      summary: Describe Option Group Options
      description: Describes all available options.
      operationId: describeoptiongroupoptions
      x-api-path-slug: actiondescribeoptiongroupoptions-get
      parameters:
      - in: query
        name: EngineName
        description: A required parameter
        type: string
      - in: query
        name: Filters.Filter.N
        description: This parameter is not currently supported
        type: string
      - in: query
        name: MajorEngineVersion
        description: If specified, filters the results to include only options for
          the specified major engine version
        type: string
      - in: query
        name: Marker
        description: An optional pagination token provided by a previous request
        type: string
      - in: query
        name: MaxRecords
        description: The maximum number of records to include in the response
        type: string
      responses:
        200:
          description: OK
      tags:
      - Option Groups
  /?Action=DescribeOptionGroups:
    get:
      summary: Describe Option Groups
      description: Describes the available option groups.
      operationId: describeoptiongroups
      x-api-path-slug: actiondescribeoptiongroups-get
      parameters:
      - in: query
        name: EngineName
        description: Filters the list of option groups to only include groups associated
          with a specific database engine
        type: string
      - in: query
        name: Filters.Filter.N
        description: This parameter is not currently supported
        type: string
      - in: query
        name: MajorEngineVersion
        description: Filters the list of option groups to only include groups associated
          with a specific database engine version
        type: string
      - in: query
        name: Marker
        description: An optional pagination token provided by a previous DescribeOptionGroups
          request
        type: string
      - in: query
        name: MaxRecords
        description: The maximum number of records to include in the response
        type: string
      - in: query
        name: OptionGroupName
        description: The name of the option group to describe
        type: string
      responses:
        200:
          description: OK
      tags:
      - Option Groups
  /?Action=DescribeOrderableDBInstanceOptions:
    get:
      summary: Describe Orderable D B Instance Options
      description: Returns a list of orderable DB instance options for the specified
        engine.
      operationId: describeorderabledbinstanceoptions
      x-api-path-slug: actiondescribeorderabledbinstanceoptions-get
      parameters:
      - in: query
        name: DBInstanceClass
        description: The DB instance class filter value
        type: string
      - in: query
        name: Engine
        description: The name of the engine to retrieve DB instance options for
        type: string
      - in: query
        name: EngineVersion
        description: The engine version filter value
        type: string
      - in: query
        name: Filters.Filter.N
        description: This parameter is not currently supported
        type: string
      - in: query
        name: LicenseModel
        description: The license model filter value
        type: string
      - in: query
        name: Marker
        description: An optional pagination token provided by a previous            DescribeOrderableDBInstanceOptions
          request
        type: string
      - in: query
        name: MaxRecords
        description: The maximum number of records to include in the response
        type: string
      - in: query
        name: Vpc
        description: The VPC filter value
        type: string
      responses:
        200:
          description: OK
      tags:
      - Instances
  /?Action=DescribePendingMaintenanceActions:
    get:
      summary: Describe Pending Maintenance Actions
      description: Returns a list of resources (for example, DB instances) that have
        at least one pending maintenance action.
      operationId: describependingmaintenanceactions
      x-api-path-slug: actiondescribependingmaintenanceactions-get
      parameters:
      - in: query
        name: Filters.Filter.N
        description: A filter that specifies one or more resources to return pending
          maintenance actions for
        type: string
      - in: query
        name: Marker
        description: An optional pagination token provided by a previous            DescribePendingMaintenanceActions
          request
        type: string
      - in: query
        name: MaxRecords
        description: The maximum number of records to include in the response
        type: string
      - in: query
        name: ResourceIdentifier
        description: The ARN of a resource to return pending maintenance actions for
        type: string
      responses:
        200:
          description: OK
      tags:
      - Maintenance Actions
  /?Action=DescribeReservedDBInstances:
    get:
      summary: Describe Reserved D B Instances
      description: Returns information about reserved DB instances for this account,
        or about a specified reserved DB instance.
      operationId: describereserveddbinstances
      x-api-path-slug: actiondescribereserveddbinstances-get
      parameters:
      - in: query
        name: DBInstanceClass
        description: The DB instance class filter value
        type: string
      - in: query
        name: Duration
        description: The duration filter value, specified in years or seconds
        type: string
      - in: query
        name: Filters.Filter.N
        description: This parameter is not currently supported
        type: string
      - in: query
        name: Marker
        description: An optional pagination token provided by a previous request
        type: string
      - in: query
        name: MaxRecords
        description: The maximum number of records to include in the response
        type: string
      - in: query
        name: MultiAZ
        description: The Multi-AZ filter value
        type: string
      - in: query
        name: OfferingType
        description: The offering type filter value
        type: string
      - in: query
        name: ProductDescription
        description: The product description filter value
        type: string
      - in: query
        name: ReservedDBInstanceId
        description: The reserved DB instance identifier filter value
        type: string
      - in: query
        name: ReservedDBInstancesOfferingId
        description: The offering identifier filter value
        type: string
      responses:
        200:
          description: OK
      tags:
      - Instances
  /?Action=DescribeReservedDBInstancesOfferings:
    get:
      summary: Describe Reserved D B Instances Offerings
      description: Lists available reserved DB instance offerings.
      operationId: describereserveddbinstancesofferings
      x-api-path-slug: actiondescribereserveddbinstancesofferings-get
      parameters:
      - in: query
        name: DBInstanceClass
        description: The DB instance class filter value
        type: string
      - in: query
        name: Duration
        description: Duration filter value, specified in years or seconds
        type: string
      - in: query
        name: Filters.Filter.N
        description: This parameter is not currently supported
        type: string
      - in: query
        name: Marker
        description: An optional pagination token provided by a previous request
        type: string
      - in: query
        name: MaxRecords
        description: The maximum number of records to include in the response
        type: string
      - in: query
        name: MultiAZ
        description: The Multi-AZ filter value
        type: string
      - in: query
        name: OfferingType
        description: The offering type filter value
        type: string
      - in: query
        name: ProductDescription
        description: Product description filter value
        type: string
      - in: query
        name: ReservedDBInstancesOfferingId
        description: The offering identifier filter value
        type: string
      responses:
        200:
          description: OK
      tags:
      - Instances
  /?Action=DescribeSourceRegions:
    get:
      summary: Describe Source Regions
      description: "Returns a list of the source AWS regions where the current AWS
        region can create a Read Replica \n            or copy a DB snapshot from."
      operationId: describesourceregions
      x-api-path-slug: actiondescribesourceregions-get
      parameters:
      - in: query
        name: Filters.Filter.N
        description: This parameter is not currently supported
        type: string
      - in: query
        name: Marker
        description: An optional pagination token provided by a previous DescribeSourceRegions
          request
        type: string
      - in: query
        name: MaxRecords
        description: The maximum number of records to include in the response
        type: string
      - in: query
        name: RegionName
        description: The source region name
        type: string
      responses:
        200:
          description: OK
      tags:
      - Source Regions
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