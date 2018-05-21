---
name: AWS RDS
x-slug: aws-rds
description: Amazon Relational Database Service (Amazon RDS) makes it easy to set
  up, operate, and scale arelational databasein the cloud. It provides cost-efficient
  and resizable capacity while managing time-consuming database administration tasks,
  freeing you up to focus on your applications and business. Amazon RDS provides you
  six familiar database engines to choose from, includingAmazon Aurora,PostgreSQL,MySQL,MariaDB,Oracle,
  andMicrosoft SQL Server.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonRDS.png
x-kinRank: "10"
x-alexaRank: ""
tags: AWS RDS
created: "2018-05-21"
modified: "2018-05-21"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-rds/master/_listings/aws-rds/apis.md
specificationVersion: "0.14"
apis:
- name: Amazon RDS API Add Role To D B Cluster
  x-api-slug: amazon-rds-api
  description: Associates an Identity and Access Management (IAM) role from an Aurora
    DB cluster.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonRDS.png
  humanURL: https://aws.amazon.com/rds/
  baseURL: ://///?Action=AddRoleToDBCluster
  tags: Clusters
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-rds/master/_listings/aws-rds/actionaddroletodbcluster-get-openapi.md
- name: Amazon RDS API Add Source Identifier To Subscription
  x-api-slug: amazon-rds-api
  description: Adds a source identifier to an existing RDS event notification subscription.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonRDS.png
  humanURL: https://aws.amazon.com/rds/
  baseURL: ://///?Action=AddSourceIdentifierToSubscription
  tags: Subscriptions
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-rds/master/_listings/aws-rds/actionaddsourceidentifiertosubscription-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-rds/master/_listings/aws-rds/actionaddsourceidentifiertosubscription-get-openapi.md
- name: Amazon RDS API Add Tags To Resource
  x-api-slug: amazon-rds-api
  description: Adds metadata tags to an Amazon RDS resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonRDS.png
  humanURL: https://aws.amazon.com/rds/
  baseURL: ://///?Action=AddTagsToResource
  tags: Tags
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-rds/master/_listings/aws-rds/actionaddtagstoresource-get-openapi.md
- name: Amazon RDS API Apply Pending Maintenance Action
  x-api-slug: amazon-rds-api
  description: Applies a pending maintenance action to a resource (for example, to
    a DB instance).
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonRDS.png
  humanURL: https://aws.amazon.com/rds/
  baseURL: ://///?Action=ApplyPendingMaintenanceAction
  tags: Maintenance Actions
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-rds/master/_listings/aws-rds/actionapplypendingmaintenanceaction-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-rds/master/_listings/aws-rds/actionapplypendingmaintenanceaction-get-openapi.md
- name: Amazon RDS API Authorize D B Security Group Ingress
  x-api-slug: amazon-rds-api
  description: Enables ingress to a DBSecurityGroup using one of two forms of authorization.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonRDS.png
  humanURL: https://aws.amazon.com/rds/
  baseURL: ://///?Action=AuthorizeDBSecurityGroupIngress
  tags: Security Groups
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-rds/master/_listings/aws-rds/actionauthorizedbsecuritygroupingress-get-openapi.md
- name: Amazon RDS API Copy D B Cluster Parameter Group
  x-api-slug: amazon-rds-api
  description: Copies the specified DB cluster parameter group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonRDS.png
  humanURL: https://aws.amazon.com/rds/
  baseURL: ://///?Action=CopyDBClusterParameterGroup
  tags: Cluster Parameter Groups
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-rds/master/_listings/aws-rds/actioncopydbclusterparametergroup-get-openapi.md
- name: Amazon RDS API Copy D B Cluster Snapshot
  x-api-slug: amazon-rds-api
  description: Creates a snapshot of a DB cluster.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonRDS.png
  humanURL: https://aws.amazon.com/rds/
  baseURL: ://///?Action=CopyDBClusterSnapshot
  tags: Cluster Snapshots
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-rds/master/_listings/aws-rds/actioncopydbclustersnapshot-get-openapi.md
- name: Amazon RDS API Copy D B Parameter Group
  x-api-slug: amazon-rds-api
  description: Copies the specified DB parameter group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonRDS.png
  humanURL: https://aws.amazon.com/rds/
  baseURL: ://///?Action=CopyDBParameterGroup
  tags: Parameter Groups
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-rds/master/_listings/aws-rds/actioncopydbparametergroup-get-openapi.md
- name: Amazon RDS API Copy D B Snapshot
  x-api-slug: amazon-rds-api
  description: Copies the specified DB snapshot.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonRDS.png
  humanURL: https://aws.amazon.com/rds/
  baseURL: ://///?Action=CopyDBSnapshot
  tags: Snapshots
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-rds/master/_listings/aws-rds/actioncopydbsnapshot-get-openapi.md
- name: Amazon RDS API Copy Option Group
  x-api-slug: amazon-rds-api
  description: Copies the specified option group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonRDS.png
  humanURL: https://aws.amazon.com/rds/
  baseURL: ://///?Action=CopyOptionGroup
  tags: Option Groups
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-rds/master/_listings/aws-rds/actioncopyoptiongroup-get-openapi.md
- name: Amazon RDS API Create D B Cluster
  x-api-slug: amazon-rds-api
  description: Creates a new Amazon Aurora DB cluster.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonRDS.png
  humanURL: https://aws.amazon.com/rds/
  baseURL: ://///?Action=CreateDBCluster
  tags: Clusters
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-rds/master/_listings/aws-rds/actioncreatedbcluster-get-openapi.md
- name: Amazon RDS API Create D B Cluster Parameter Group
  x-api-slug: amazon-rds-api
  description: Creates a new DB cluster parameter group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonRDS.png
  humanURL: https://aws.amazon.com/rds/
  baseURL: ://///?Action=CreateDBClusterParameterGroup
  tags: Cluster Parameter Groups
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-rds/master/_listings/aws-rds/actioncreatedbclusterparametergroup-get-openapi.md
- name: Amazon RDS API Create D B Cluster Snapshot
  x-api-slug: amazon-rds-api
  description: Creates a snapshot of a DB cluster.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonRDS.png
  humanURL: https://aws.amazon.com/rds/
  baseURL: ://///?Action=CreateDBClusterSnapshot
  tags: Cluster Snapshots
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-rds/master/_listings/aws-rds/actioncreatedbclustersnapshot-get-openapi.md
- name: Amazon RDS API Create D B Instance
  x-api-slug: amazon-rds-api
  description: Creates a new DB instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonRDS.png
  humanURL: https://aws.amazon.com/rds/
  baseURL: ://///?Action=CreateDBInstance
  tags: Instances
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-rds/master/_listings/aws-rds/actioncreatedbinstance-get-openapi.md
- name: Amazon RDS API Create D B Instance Read Replica
  x-api-slug: amazon-rds-api
  description: Creates a DB instance for a DB instance running MySQL, MariaDB, or
    PostgreSQL that acts as a Read Replica of a source DB instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonRDS.png
  humanURL: https://aws.amazon.com/rds/
  baseURL: ://///?Action=CreateDBInstanceReadReplica
  tags: Instances
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-rds/master/_listings/aws-rds/actioncreatedbinstancereadreplica-get-openapi.md
- name: Amazon RDS API Create D B Parameter Group
  x-api-slug: amazon-rds-api
  description: Creates a new DB parameter group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonRDS.png
  humanURL: https://aws.amazon.com/rds/
  baseURL: ://///?Action=CreateDBParameterGroup
  tags: Parameter Groups
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-rds/master/_listings/aws-rds/actioncreatedbparametergroup-get-openapi.md
- name: Amazon RDS API Create D B Security Group
  x-api-slug: amazon-rds-api
  description: Creates a new DB security group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonRDS.png
  humanURL: https://aws.amazon.com/rds/
  baseURL: ://///?Action=CreateDBSecurityGroup
  tags: Security Groups
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-rds/master/_listings/aws-rds/actioncreatedbsecuritygroup-get-openapi.md
- name: Amazon RDS API Create D B Snapshot
  x-api-slug: amazon-rds-api
  description: Creates a DBSnapshot.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonRDS.png
  humanURL: https://aws.amazon.com/rds/
  baseURL: ://///?Action=CreateDBSnapshot
  tags: Snapshots
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-rds/master/_listings/aws-rds/actioncreatedbsnapshot-get-openapi.md
- name: Amazon RDS API Create D B Subnet Group
  x-api-slug: amazon-rds-api
  description: Creates a new DB subnet group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonRDS.png
  humanURL: https://aws.amazon.com/rds/
  baseURL: ://///?Action=CreateDBSubnetGroup
  tags: Subnet Groups
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-rds/master/_listings/aws-rds/actioncreatedbsubnetgroup-get-openapi.md
- name: Amazon RDS API Create Event Subscription
  x-api-slug: amazon-rds-api
  description: Creates an RDS event notification subscription.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonRDS.png
  humanURL: https://aws.amazon.com/rds/
  baseURL: ://///?Action=CreateEventSubscription
  tags: Event Subscriptions
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-rds/master/_listings/aws-rds/actioncreateeventsubscription-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-rds/master/_listings/aws-rds/actioncreateeventsubscription-get-openapi.md
- name: Amazon RDS API Create Option Group
  x-api-slug: amazon-rds-api
  description: Creates a new option group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonRDS.png
  humanURL: https://aws.amazon.com/rds/
  baseURL: ://///?Action=CreateOptionGroup
  tags: Option Groups
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-rds/master/_listings/aws-rds/actioncreateoptiongroup-get-openapi.md
- name: Amazon RDS API Delete D B Cluster
  x-api-slug: amazon-rds-api
  description: The DeleteDBCluster action deletes a previously provisioned DB cluster.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonRDS.png
  humanURL: https://aws.amazon.com/rds/
  baseURL: ://///?Action=DeleteDBCluster
  tags: Clusters
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-rds/master/_listings/aws-rds/actiondeletedbcluster-get-openapi.md
- name: Amazon RDS API Delete D B Cluster Parameter Group
  x-api-slug: amazon-rds-api
  description: Deletes a specified DB cluster parameter group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonRDS.png
  humanURL: https://aws.amazon.com/rds/
  baseURL: ://///?Action=DeleteDBClusterParameterGroup
  tags: Cluster Parameter Groups
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-rds/master/_listings/aws-rds/actiondeletedbclusterparametergroup-get-openapi.md
- name: Amazon RDS API Delete D B Cluster Snapshot
  x-api-slug: amazon-rds-api
  description: Deletes a DB cluster snapshot.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonRDS.png
  humanURL: https://aws.amazon.com/rds/
  baseURL: ://///?Action=DeleteDBClusterSnapshot
  tags: Cluster Snapshots
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-rds/master/_listings/aws-rds/actiondeletedbclustersnapshot-get-openapi.md
- name: Amazon RDS API Delete D B Instance
  x-api-slug: amazon-rds-api
  description: The DeleteDBInstance action deletes a previously provisioned DB instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonRDS.png
  humanURL: https://aws.amazon.com/rds/
  baseURL: ://///?Action=DeleteDBInstance
  tags: Instances
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-rds/master/_listings/aws-rds/actiondeletedbinstance-get-openapi.md
- name: Amazon RDS API Delete D B Parameter Group
  x-api-slug: amazon-rds-api
  description: Deletes a specified DBParameterGroup.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonRDS.png
  humanURL: https://aws.amazon.com/rds/
  baseURL: ://///?Action=DeleteDBParameterGroup
  tags: Parameter Groups
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-rds/master/_listings/aws-rds/actiondeletedbparametergroup-get-openapi.md
- name: Amazon RDS API Delete D B Security Group
  x-api-slug: amazon-rds-api
  description: Deletes a DB security group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonRDS.png
  humanURL: https://aws.amazon.com/rds/
  baseURL: ://///?Action=DeleteDBSecurityGroup
  tags: Security Groups
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-rds/master/_listings/aws-rds/actiondeletedbsecuritygroup-get-openapi.md
- name: Amazon RDS API Delete D B Snapshot
  x-api-slug: amazon-rds-api
  description: Deletes a DBSnapshot.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonRDS.png
  humanURL: https://aws.amazon.com/rds/
  baseURL: ://///?Action=DeleteDBSnapshot
  tags: Snapshots
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-rds/master/_listings/aws-rds/actiondeletedbsnapshot-get-openapi.md
- name: Amazon RDS API Delete D B Subnet Group
  x-api-slug: amazon-rds-api
  description: Deletes a DB subnet group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonRDS.png
  humanURL: https://aws.amazon.com/rds/
  baseURL: ://///?Action=DeleteDBSubnetGroup
  tags: Subnet Groups
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-rds/master/_listings/aws-rds/actiondeletedbsubnetgroup-get-openapi.md
- name: Amazon RDS API Delete Event Subscription
  x-api-slug: amazon-rds-api
  description: Deletes an RDS event notification subscription.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonRDS.png
  humanURL: https://aws.amazon.com/rds/
  baseURL: ://///?Action=DeleteEventSubscription
  tags: Event Subscriptions
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-rds/master/_listings/aws-rds/actiondeleteeventsubscription-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-rds/master/_listings/aws-rds/actiondeleteeventsubscription-get-openapi.md
- name: Amazon RDS API Delete Option Group
  x-api-slug: amazon-rds-api
  description: Deletes an existing option group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonRDS.png
  humanURL: https://aws.amazon.com/rds/
  baseURL: ://///?Action=DeleteOptionGroup
  tags: Option Groups
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-rds/master/_listings/aws-rds/actiondeleteoptiongroup-get-openapi.md
- name: Amazon RDS API Describe Account Attributes
  x-api-slug: amazon-rds-api
  description: Lists all of the attributes for a customer account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonRDS.png
  humanURL: https://aws.amazon.com/rds/
  baseURL: ://///?Action=DescribeAccountAttributes
  tags: Accounts
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-rds/master/_listings/aws-rds/actiondescribeaccountattributes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-rds/master/_listings/aws-rds/actiondescribeaccountattributes-get-openapi.md
- name: Amazon RDS API Describe Certificates
  x-api-slug: amazon-rds-api
  description: Lists the set of CA certificates provided by Amazon RDS for this AWS
    account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonRDS.png
  humanURL: https://aws.amazon.com/rds/
  baseURL: ://///?Action=DescribeCertificates
  tags: Certificates
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-rds/master/_listings/aws-rds/actiondescribecertificates-get-openapi.md
- name: Amazon RDS API Describe D B Cluster Parameter Groups
  x-api-slug: amazon-rds-api
  description: Returns a list of DBClusterParameterGroup descriptions.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonRDS.png
  humanURL: https://aws.amazon.com/rds/
  baseURL: ://///?Action=DescribeDBClusterParameterGroups
  tags: Cluster Parameter Groups
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-rds/master/_listings/aws-rds/actiondescribedbclusterparametergroups-get-openapi.md
- name: Amazon RDS API Describe D B Cluster Parameters
  x-api-slug: amazon-rds-api
  description: Returns the detailed parameter list for a particular DB cluster parameter
    group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonRDS.png
  humanURL: https://aws.amazon.com/rds/
  baseURL: ://///?Action=DescribeDBClusterParameters
  tags: Cluster Parameters
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-rds/master/_listings/aws-rds/actiondescribedbclusterparameters-get-openapi.md
- name: Amazon RDS API Describe D B Clusters
  x-api-slug: amazon-rds-api
  description: Returns information about provisioned Aurora DB clusters.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonRDS.png
  humanURL: https://aws.amazon.com/rds/
  baseURL: ://///?Action=DescribeDBClusters
  tags: Clusters
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-rds/master/_listings/aws-rds/actiondescribedbclusters-get-openapi.md
- name: Amazon RDS API Describe D B Cluster Snapshot Attributes
  x-api-slug: amazon-rds-api
  description: Returns a list of DB cluster snapshot attribute names and values for
    a manual DB cluster snapshot.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonRDS.png
  humanURL: https://aws.amazon.com/rds/
  baseURL: ://///?Action=DescribeDBClusterSnapshotAttributes
  tags: Cluster Snapshots
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-rds/master/_listings/aws-rds/actiondescribedbclustersnapshotattributes-get-openapi.md
- name: Amazon RDS API Describe D B Cluster Snapshots
  x-api-slug: amazon-rds-api
  description: Returns information about DB cluster snapshots.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonRDS.png
  humanURL: https://aws.amazon.com/rds/
  baseURL: ://///?Action=DescribeDBClusterSnapshots
  tags: Cluster Snapshots
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-rds/master/_listings/aws-rds/actiondescribedbclustersnapshots-get-openapi.md
- name: Amazon RDS API Describe D B Engine Versions
  x-api-slug: amazon-rds-api
  description: Returns a list of the available DB engines.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonRDS.png
  humanURL: https://aws.amazon.com/rds/
  baseURL: ://///?Action=DescribeDBEngineVersions
  tags: Engines
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-rds/master/_listings/aws-rds/actiondescribedbengineversions-get-openapi.md
- name: Amazon RDS API Describe D B Instances
  x-api-slug: amazon-rds-api
  description: Returns information about provisioned RDS instances.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonRDS.png
  humanURL: https://aws.amazon.com/rds/
  baseURL: ://///?Action=DescribeDBInstances
  tags: Instances
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-rds/master/_listings/aws-rds/actiondescribedbinstances-get-openapi.md
- name: Amazon RDS API Describe D B Log Files
  x-api-slug: amazon-rds-api
  description: Returns a list of DB log files for the DB instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonRDS.png
  humanURL: https://aws.amazon.com/rds/
  baseURL: ://///?Action=DescribeDBLogFiles
  tags: Blog Files
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-rds/master/_listings/aws-rds/actiondescribedblogfiles-get-openapi.md
- name: Amazon RDS API Describe D B Parameter Groups
  x-api-slug: amazon-rds-api
  description: Returns a list of DBParameterGroup descriptions.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonRDS.png
  humanURL: https://aws.amazon.com/rds/
  baseURL: ://///?Action=DescribeDBParameterGroups
  tags: Parameter Groups
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-rds/master/_listings/aws-rds/actiondescribedbparametergroups-get-openapi.md
- name: Amazon RDS API Describe D B Parameters
  x-api-slug: amazon-rds-api
  description: Returns the detailed parameter list for a particular DB parameter group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonRDS.png
  humanURL: https://aws.amazon.com/rds/
  baseURL: ://///?Action=DescribeDBParameters
  tags: Parameters
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-rds/master/_listings/aws-rds/actiondescribedbparameters-get-openapi.md
- name: Amazon RDS API Describe D B Security Groups
  x-api-slug: amazon-rds-api
  description: Returns a list of DBSecurityGroup descriptions.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonRDS.png
  humanURL: https://aws.amazon.com/rds/
  baseURL: ://///?Action=DescribeDBSecurityGroups
  tags: Security Groups
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-rds/master/_listings/aws-rds/actiondescribedbsecuritygroups-get-openapi.md
- name: Amazon RDS API Describe D B Snapshot Attributes
  x-api-slug: amazon-rds-api
  description: Returns a list of DB snapshot attribute names and values for a manual
    DB snapshot.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonRDS.png
  humanURL: https://aws.amazon.com/rds/
  baseURL: ://///?Action=DescribeDBSnapshotAttributes
  tags: Snapshots
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-rds/master/_listings/aws-rds/actiondescribedbsnapshotattributes-get-openapi.md
- name: Amazon RDS API Describe D B Snapshots
  x-api-slug: amazon-rds-api
  description: Returns information about DB snapshots.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonRDS.png
  humanURL: https://aws.amazon.com/rds/
  baseURL: ://///?Action=DescribeDBSnapshots
  tags: Snapshots
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-rds/master/_listings/aws-rds/actiondescribedbsnapshots-get-openapi.md
- name: Amazon RDS API Describe D B Subnet Groups
  x-api-slug: amazon-rds-api
  description: Returns a list of DBSubnetGroup descriptions.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonRDS.png
  humanURL: https://aws.amazon.com/rds/
  baseURL: ://///?Action=DescribeDBSubnetGroups
  tags: Subnet Groups
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-rds/master/_listings/aws-rds/actiondescribedbsubnetgroups-get-openapi.md
- name: Amazon RDS API Describe Engine Default Cluster Parameters
  x-api-slug: amazon-rds-api
  description: Returns the default engine and system parameter information for the
    cluster database engine.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonRDS.png
  humanURL: https://aws.amazon.com/rds/
  baseURL: ://///?Action=DescribeEngineDefaultClusterParameters
  tags: Default Cluster Parameters
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-rds/master/_listings/aws-rds/actiondescribeenginedefaultclusterparameters-get-openapi.md
- name: Amazon RDS API Describe Engine Default Parameters
  x-api-slug: amazon-rds-api
  description: Returns the default engine and system parameter information for the
    specified database engine.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonRDS.png
  humanURL: https://aws.amazon.com/rds/
  baseURL: ://///?Action=DescribeEngineDefaultParameters
  tags: Default Parameters
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-rds/master/_listings/aws-rds/actiondescribeenginedefaultparameters-get-openapi.md
- name: Amazon RDS API Describe Event Categories
  x-api-slug: amazon-rds-api
  description: Displays a list of categories for all event source types, or, if specified,
    for a specified source type.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonRDS.png
  humanURL: https://aws.amazon.com/rds/
  baseURL: ://///?Action=DescribeEventCategories
  tags: Event Categories
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-rds/master/_listings/aws-rds/actiondescribeeventcategories-get-openapi.md
- name: Amazon RDS API Describe Events
  x-api-slug: amazon-rds-api
  description: Returns events related to DB instances, DB security groups, DB snapshots,
    and DB parameter groups for the past 14 days.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonRDS.png
  humanURL: https://aws.amazon.com/rds/
  baseURL: ://///?Action=DescribeEvents
  tags: Events
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-rds/master/_listings/aws-rds/actiondescribeevents-get-openapi.md
- name: Amazon RDS API Describe Event Subscriptions
  x-api-slug: amazon-rds-api
  description: Lists all the subscription descriptions for a customer account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonRDS.png
  humanURL: https://aws.amazon.com/rds/
  baseURL: ://///?Action=DescribeEventSubscriptions
  tags: Event Subscriptions
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-rds/master/_listings/aws-rds/actiondescribeeventsubscriptions-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-rds/master/_listings/aws-rds/actiondescribeeventsubscriptions-get-openapi.md
- name: Amazon RDS API Describe Option Group Options
  x-api-slug: amazon-rds-api
  description: Describes all available options.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonRDS.png
  humanURL: https://aws.amazon.com/rds/
  baseURL: ://///?Action=DescribeOptionGroupOptions
  tags: Option Groups
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-rds/master/_listings/aws-rds/actiondescribeoptiongroupoptions-get-openapi.md
- name: Amazon RDS API Describe Option Groups
  x-api-slug: amazon-rds-api
  description: Describes the available option groups.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonRDS.png
  humanURL: https://aws.amazon.com/rds/
  baseURL: ://///?Action=DescribeOptionGroups
  tags: Option Groups
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-rds/master/_listings/aws-rds/actiondescribeoptiongroups-get-openapi.md
- name: Amazon RDS API Describe Orderable D B Instance Options
  x-api-slug: amazon-rds-api
  description: Returns a list of orderable DB instance options for the specified engine.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonRDS.png
  humanURL: https://aws.amazon.com/rds/
  baseURL: ://///?Action=DescribeOrderableDBInstanceOptions
  tags: Instances
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-rds/master/_listings/aws-rds/actiondescribeorderabledbinstanceoptions-get-openapi.md
- name: Amazon RDS API Describe Pending Maintenance Actions
  x-api-slug: amazon-rds-api
  description: Returns a list of resources (for example, DB instances) that have at
    least one pending maintenance action.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonRDS.png
  humanURL: https://aws.amazon.com/rds/
  baseURL: ://///?Action=DescribePendingMaintenanceActions
  tags: Maintenance Actions
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-rds/master/_listings/aws-rds/actiondescribependingmaintenanceactions-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-rds/master/_listings/aws-rds/actiondescribependingmaintenanceactions-get-openapi.md
- name: Amazon RDS API Describe Reserved D B Instances
  x-api-slug: amazon-rds-api
  description: Returns information about reserved DB instances for this account, or
    about a specified reserved DB instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonRDS.png
  humanURL: https://aws.amazon.com/rds/
  baseURL: ://///?Action=DescribeReservedDBInstances
  tags: Instances
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-rds/master/_listings/aws-rds/actiondescribereserveddbinstances-get-openapi.md
- name: Amazon RDS API Describe Reserved D B Instances Offerings
  x-api-slug: amazon-rds-api
  description: Lists available reserved DB instance offerings.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonRDS.png
  humanURL: https://aws.amazon.com/rds/
  baseURL: ://///?Action=DescribeReservedDBInstancesOfferings
  tags: Instances
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-rds/master/_listings/aws-rds/actiondescribereserveddbinstancesofferings-get-openapi.md
- name: Amazon RDS API Describe Source Regions
  x-api-slug: amazon-rds-api
  description: "Returns a list of the source AWS regions where the current AWS region
    can create a Read Replica \n            or copy a DB snapshot from."
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonRDS.png
  humanURL: https://aws.amazon.com/rds/
  baseURL: ://///?Action=DescribeSourceRegions
  tags: Source Regions
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-rds/master/_listings/aws-rds/actiondescribesourceregions-get-openapi.md
- name: Amazon RDS API Download D B Log File Portion
  x-api-slug: amazon-rds-api
  description: Downloads all or a portion of the specified log file, up to 1 MB in
    size.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonRDS.png
  humanURL: https://aws.amazon.com/rds/
  baseURL: ://///?Action=DownloadDBLogFilePortion
  tags: Log Files
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-rds/master/_listings/aws-rds/actiondownloaddblogfileportion-get-openapi.md
- name: Amazon RDS API Failover D B Cluster
  x-api-slug: amazon-rds-api
  description: Forces a failover for a DB cluster.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonRDS.png
  humanURL: https://aws.amazon.com/rds/
  baseURL: ://///?Action=FailoverDBCluster
  tags: Clusters
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-rds/master/_listings/aws-rds/actionfailoverdbcluster-get-openapi.md
- name: Amazon RDS API List Tags For Resource
  x-api-slug: amazon-rds-api
  description: Lists all tags on an Amazon RDS resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonRDS.png
  humanURL: https://aws.amazon.com/rds/
  baseURL: ://///?Action=ListTagsForResource
  tags: Tags
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-rds/master/_listings/aws-rds/actionlisttagsforresource-get-openapi.md
- name: Amazon RDS API Modify D B Cluster
  x-api-slug: amazon-rds-api
  description: Modify a setting for an Amazon Aurora DB cluster.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonRDS.png
  humanURL: https://aws.amazon.com/rds/
  baseURL: ://///?Action=ModifyDBCluster
  tags: Clusters
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-rds/master/_listings/aws-rds/actionmodifydbcluster-get-openapi.md
- name: Amazon RDS API Modify D B Cluster Parameter Group
  x-api-slug: amazon-rds-api
  description: Modifies the parameters of a DB cluster parameter group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonRDS.png
  humanURL: https://aws.amazon.com/rds/
  baseURL: ://///?Action=ModifyDBClusterParameterGroup
  tags: Cluster Parameter Groups
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-rds/master/_listings/aws-rds/actionmodifydbclusterparametergroup-get-openapi.md
- name: Amazon RDS API Modify D B Cluster Snapshot Attribute
  x-api-slug: amazon-rds-api
  description: Adds an attribute and values to, or removes an attribute and values
    from, a manual DB cluster snapshot.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonRDS.png
  humanURL: https://aws.amazon.com/rds/
  baseURL: ://///?Action=ModifyDBClusterSnapshotAttribute
  tags: Cluster Snapshots
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-rds/master/_listings/aws-rds/actionmodifydbclustersnapshotattribute-get-openapi.md
- name: Amazon RDS API Modify D B Instance
  x-api-slug: amazon-rds-api
  description: Modifies settings for a DB instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonRDS.png
  humanURL: https://aws.amazon.com/rds/
  baseURL: ://///?Action=ModifyDBInstance
  tags: Instances
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-rds/master/_listings/aws-rds/actionmodifydbinstance-get-openapi.md
- name: Amazon RDS API Modify D B Parameter Group
  x-api-slug: amazon-rds-api
  description: Modifies the parameters of a DB parameter group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonRDS.png
  humanURL: https://aws.amazon.com/rds/
  baseURL: ://///?Action=ModifyDBParameterGroup
  tags: Parameter Groups
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-rds/master/_listings/aws-rds/actionmodifydbparametergroup-get-openapi.md
- name: Amazon RDS API Modify D B Snapshot Attribute
  x-api-slug: amazon-rds-api
  description: Adds an attribute and values to, or removes an attribute and values
    from, a manual DB snapshot.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonRDS.png
  humanURL: https://aws.amazon.com/rds/
  baseURL: ://///?Action=ModifyDBSnapshotAttribute
  tags: Snapshots
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-rds/master/_listings/aws-rds/actionmodifydbsnapshotattribute-get-openapi.md
- name: Amazon RDS API Modify D B Subnet Group
  x-api-slug: amazon-rds-api
  description: Modifies an existing DB subnet group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonRDS.png
  humanURL: https://aws.amazon.com/rds/
  baseURL: ://///?Action=ModifyDBSubnetGroup
  tags: Subnet Groups
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-rds/master/_listings/aws-rds/actionmodifydbsubnetgroup-get-openapi.md
- name: Amazon RDS API Modify Event Subscription
  x-api-slug: amazon-rds-api
  description: Modifies an existing RDS event notification subscription.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonRDS.png
  humanURL: https://aws.amazon.com/rds/
  baseURL: ://///?Action=ModifyEventSubscription
  tags: Event Subscriptions
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-rds/master/_listings/aws-rds/actionmodifyeventsubscription-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-rds/master/_listings/aws-rds/actionmodifyeventsubscription-get-openapi.md
- name: Amazon RDS API Modify Option Group
  x-api-slug: amazon-rds-api
  description: Modifies an existing option group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonRDS.png
  humanURL: https://aws.amazon.com/rds/
  baseURL: ://///?Action=ModifyOptionGroup
  tags: Option Groups
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-rds/master/_listings/aws-rds/actionmodifyoptiongroup-get-openapi.md
- name: Amazon RDS API Promote Read Replica
  x-api-slug: amazon-rds-api
  description: Promotes a Read Replica DB instance to a standalone DB instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonRDS.png
  humanURL: https://aws.amazon.com/rds/
  baseURL: ://///?Action=PromoteReadReplica
  tags: Replicas
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-rds/master/_listings/aws-rds/actionpromotereadreplica-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-rds/master/_listings/aws-rds/actionpromotereadreplica-get-openapi.md
- name: Amazon RDS API Promote Read Replica D B Cluster
  x-api-slug: amazon-rds-api
  description: Promotes a Read Replica DB cluster to a standalone DB cluster.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonRDS.png
  humanURL: https://aws.amazon.com/rds/
  baseURL: ://///?Action=PromoteReadReplicaDBCluster
  tags: Replicas
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-rds/master/_listings/aws-rds/actionpromotereadreplicadbcluster-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-rds/master/_listings/aws-rds/actionpromotereadreplicadbcluster-get-openapi.md
- name: Amazon RDS API Purchase Reserved D B Instances Offering
  x-api-slug: amazon-rds-api
  description: Purchases a reserved DB instance offering.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonRDS.png
  humanURL: https://aws.amazon.com/rds/
  baseURL: ://///?Action=PurchaseReservedDBInstancesOffering
  tags: Instances
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-rds/master/_listings/aws-rds/actionpurchasereserveddbinstancesoffering-get-openapi.md
- name: Amazon RDS API Reboot D B Instance
  x-api-slug: amazon-rds-api
  description: Rebooting a DB instance restarts the database engine service.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonRDS.png
  humanURL: https://aws.amazon.com/rds/
  baseURL: ://///?Action=RebootDBInstance
  tags: Instances
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-rds/master/_listings/aws-rds/actionrebootdbinstance-get-openapi.md
- name: Amazon RDS API Remove Role From D B Cluster
  x-api-slug: amazon-rds-api
  description: Disassociates an Identity and Access Management (IAM) role from an
    Aurora DB cluster.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonRDS.png
  humanURL: https://aws.amazon.com/rds/
  baseURL: ://///?Action=RemoveRoleFromDBCluster
  tags: Clusters
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-rds/master/_listings/aws-rds/actionremoverolefromdbcluster-get-openapi.md
- name: Amazon RDS API Remove Source Identifier From Subscription
  x-api-slug: amazon-rds-api
  description: Removes a source identifier from an existing RDS event notification
    subscription.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonRDS.png
  humanURL: https://aws.amazon.com/rds/
  baseURL: ://///?Action=RemoveSourceIdentifierFromSubscription
  tags: Subscriptions
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-rds/master/_listings/aws-rds/actionremovesourceidentifierfromsubscription-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-rds/master/_listings/aws-rds/actionremovesourceidentifierfromsubscription-get-openapi.md
- name: Amazon RDS API Remove Tags From Resource
  x-api-slug: amazon-rds-api
  description: Removes metadata tags from an Amazon RDS resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonRDS.png
  humanURL: https://aws.amazon.com/rds/
  baseURL: ://///?Action=RemoveTagsFromResource
  tags: Tags
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-rds/master/_listings/aws-rds/actionremovetagsfromresource-get-openapi.md
- name: Amazon RDS API Reset D B Cluster Parameter Group
  x-api-slug: amazon-rds-api
  description: Modifies the parameters of a DB cluster parameter group to the default
    value.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonRDS.png
  humanURL: https://aws.amazon.com/rds/
  baseURL: ://///?Action=ResetDBClusterParameterGroup
  tags: Cluster Parameter Groups
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-rds/master/_listings/aws-rds/actionresetdbclusterparametergroup-get-openapi.md
- name: Amazon RDS API Reset D B Parameter Group
  x-api-slug: amazon-rds-api
  description: Modifies the parameters of a DB parameter group to the engine/system
    default value.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonRDS.png
  humanURL: https://aws.amazon.com/rds/
  baseURL: ://///?Action=ResetDBParameterGroup
  tags: Parameter Groups
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-rds/master/_listings/aws-rds/actionresetdbparametergroup-get-openapi.md
- name: Amazon RDS API Restore D B Cluster From S3
  x-api-slug: amazon-rds-api
  description: Creates an Amazon Aurora DB cluster from data stored in an Amazon S3
    bucket.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonRDS.png
  humanURL: https://aws.amazon.com/rds/
  baseURL: ://///?Action=RestoreDBClusterFromS3
  tags: Clusters
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-rds/master/_listings/aws-rds/actionrestoredbclusterfroms3-get-openapi.md
- name: Amazon RDS API Restore D B Cluster From Snapshot
  x-api-slug: amazon-rds-api
  description: Creates a new DB cluster from a DB cluster snapshot.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonRDS.png
  humanURL: https://aws.amazon.com/rds/
  baseURL: ://///?Action=RestoreDBClusterFromSnapshot
  tags: Snapshots
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-rds/master/_listings/aws-rds/actionrestoredbclusterfromsnapshot-get-openapi.md
- name: Amazon RDS API Restore D B Cluster To Point In Time
  x-api-slug: amazon-rds-api
  description: Restores a DB cluster to an arbitrary point in time.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonRDS.png
  humanURL: https://aws.amazon.com/rds/
  baseURL: ://///?Action=RestoreDBClusterToPointInTime
  tags: Clusters
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-rds/master/_listings/aws-rds/actionrestoredbclustertopointintime-get-openapi.md
- name: Amazon RDS API Restore D B Instance From D B Snapshot
  x-api-slug: amazon-rds-api
  description: Creates a new DB instance from a DB snapshot.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonRDS.png
  humanURL: https://aws.amazon.com/rds/
  baseURL: ://///?Action=RestoreDBInstanceFromDBSnapshot
  tags: Instances
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-rds/master/_listings/aws-rds/actionrestoredbinstancefromdbsnapshot-get-openapi.md
- name: Amazon RDS API Restore D B Instance To Point In Time
  x-api-slug: amazon-rds-api
  description: Restores a DB instance to an arbitrary point in time.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonRDS.png
  humanURL: https://aws.amazon.com/rds/
  baseURL: ://///?Action=RestoreDBInstanceToPointInTime
  tags: Instances
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-rds/master/_listings/aws-rds/actionrestoredbinstancetopointintime-get-openapi.md
- name: Amazon RDS API Revoke D B Security Group Ingress
  x-api-slug: amazon-rds-api
  description: Revokes ingress from a DBSecurityGroup for previously authorized IP
    ranges or EC2 or VPC Security Groups.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonRDS.png
  humanURL: https://aws.amazon.com/rds/
  baseURL: ://///?Action=RevokeDBSecurityGroupIngress
  tags: Security Groups
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-rds/master/_listings/aws-rds/actionrevokedbsecuritygroupingress-get-openapi.md
- name: Amazon RDS API
  x-api-slug: amazon-rds-api
  description: Amazon Relational Database Service (Amazon RDS) makes it easy to set
    up, operate, and scale arelational databasein the cloud. It provides cost-efficient
    and resizable capacity while managing time-consuming database administration tasks,
    freeing you up to focus on your applications and business. Amazon RDS provides
    you six familiar database engines to choose from, includingAmazon Aurora,PostgreSQL,MySQL,MariaDB,Oracle,
    andMicrosoft SQL Server.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonRDS.png
  humanURL: https://aws.amazon.com/rds/
  baseURL: :///
  tags: AWS RDS
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-rds/master/_listings/aws-rds/openapi.md
x-common:
- type: x-articles
  url: https://aws.amazon.com/articles/Amazon-RDS
- type: x-blog
  url: https://aws.amazon.com/blogs/database/
- type: x-change-log
  url: http://developer.amazonwebservices.com/connect/kbcategory.jspa?categoryID=291
- type: x-code
  url: http://developer.amazonwebservices.com/connect/kbcategory.jspa?categoryID=293
- type: x-command-line-interface
  url: http://docs.aws.amazon.com/AmazonRDS/latest/CommandLineReference/
- type: x-customer-highlights
  url: https://aws.amazon.com/rds/customers/
- type: x-documentation
  url: http://docs.aws.amazon.com/AmazonRDS/latest/APIReference/
- type: x-faq
  url: https://aws.amazon.com/rds/faqs/
- type: x-forum
  url: http://developer.amazonwebservices.com/connect/forum.jspa?forumID=60
- type: x-getting-started
  url: https://aws.amazon.com/rds/getting-started/
- type: x-partners
  url: https://aws.amazon.com/rds/partners/
- type: x-pricing
  url: https://aws.amazon.com/rds/pricing/
- type: x-service-level-agreement
  url: https://aws.amazon.com/rds/sla/
- type: x-tools
  url: http://developer.amazonwebservices.com/connect/kbcategory.jspa?categoryID=294
- type: x-website
  url: https://aws.amazon.com/rds/
- type: x-whats-new
  url: https://aws.amazon.com/rds/whats-new/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---