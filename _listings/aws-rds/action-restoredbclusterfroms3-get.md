---
swagger: "2.0"
info:
  title: AWS RDS API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=RestoreDBClusterFromS3&k=1:
    get:
      summary: Restore D B Cluster From S3
      description: Creates an Amazon Aurora DB cluster from data stored in an Amazon
        S3 bucket
      operationId: restoredbclusterfroms3
      parameters:
      - in: query
        name: AvailabilityZones.AvailabilityZone.N
        description: A list of EC2 Availability Zones that instances in the restored
          DB cluster can be created in
        type: string
      - in: query
        name: BackupRetentionPeriod
        description: The number of days for which automated backups of the restored
          DB cluster are retained
        type: string
      - in: query
        name: CharacterSetName
        description: A value that indicates that the restored DB cluster should be
          associated with the specified CharacterSet
        type: string
      - in: query
        name: DatabaseName
        description: The database name for the restored DB cluster
        type: string
      - in: query
        name: DBClusterIdentifier
        description: The name of the DB cluster to create from the source data in
          the S3 bucket
        type: string
      - in: query
        name: DBClusterParameterGroupName
        description: The name of the DB cluster parameter group to associate            with
          the restored DB cluster
        type: string
      - in: query
        name: DBSubnetGroupName
        description: A DB subnet group to associate with the restored DB cluster
        type: string
      - in: query
        name: Engine
        description: The name of the database engine to be used for the restored DB
          cluster
        type: string
      - in: query
        name: EngineVersion
        description: The version number of the database engine to use
        type: string
      - in: query
        name: KmsKeyId
        description: The KMS key identifier for an encrypted DB cluster
        type: string
      - in: query
        name: MasterUsername
        description: The name of the master user for the restored DB cluster
        type: string
      - in: query
        name: MasterUserPassword
        description: The password for the master database user
        type: string
      - in: query
        name: OptionGroupName
        description: A value that indicates that the restored DB cluster should be
          associated with the specified option group
        type: string
      - in: query
        name: Port
        description: The port number on which the instances in the restored DB cluster
          accept connections
        type: string
      - in: query
        name: PreferredBackupWindow
        description: The daily time range during which automated backups are created            if
          automated backups are enabled            using the BackupRetentionPeriod
          parameter
        type: string
      - in: query
        name: PreferredMaintenanceWindow
        description: The weekly time range during which system maintenance can occur,
          in Universal Coordinated Time (UTC)
        type: string
      - in: query
        name: S3BucketName
        description: The name of the Amazon S3 bucket that contains the data used
          to create the Amazon Aurora DB cluster
        type: string
      - in: query
        name: S3IngestionRoleArn
        description: The Amazon Resource Name (ARN) of the AWS Identity and Access
          Management (IAM) role that authorizes        Amazon RDS to access the Amazon
          S3 bucket on your behalf
        type: string
      - in: query
        name: S3Prefix
        description: The prefix for all of the file names that contain the data used
          to create the Amazon Aurora DB cluster
        type: string
      - in: query
        name: SourceEngine
        description: The identifier for the database engine that was backed up to
          create the files stored in the            Amazon S3 bucket
        type: string
      - in: query
        name: SourceEngineVersion
        description: The version of the database that the backup files were created
          from
        type: string
      - in: query
        name: StorageEncrypted
        description: Specifies whether the restored DB cluster is encrypted
        type: string
      - in: query
        name: Tags.Tag.N
        description: A list of tags
        type: string
      - in: query
        name: VpcSecurityGroupIds.VpcSecurityGroupId.N
        description: A list of EC2 VPC security groups to associate with the restored
          DB cluster
        type: string
      responses:
        200:
          description: OK
      tags:
      - clusters
definitions: []
x-collection-name: AWS RDS
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