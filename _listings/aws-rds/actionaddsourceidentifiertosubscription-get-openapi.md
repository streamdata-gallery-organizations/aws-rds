---
swagger: "2.0"
x-collection-name: AWS RDS
x-complete: 0
info:
  title: Amazon RDS API Add Source Identifier To Subscription
  version: 1.0.0
  description: Adds a source identifier to an existing RDS event notification subscription.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=AddRoleToDBCluster:
    get:
      summary: Add Role To D B Cluster
      description: Associates an Identity and Access Management (IAM) role from an
        Aurora DB cluster.
      operationId: addroletodbcluster
      x-api-path-slug: actionaddroletodbcluster-get
      parameters:
      - in: query
        name: DBClusterIdentifier
        description: The name of the DB cluster to associate the IAM role with
        type: string
      - in: query
        name: RoleArn
        description: The Amazon Resource Name (ARN) of the IAM role to associate with
          the Aurora DB cluster, for example            arn:aws:iam::123456789012:role/AuroraAccessRole
        type: string
      responses:
        200:
          description: OK
      tags:
      - Clusters
  /?Action=AddSourceIdentifierToSubscription:
    get:
      summary: Add Source Identifier To Subscription
      description: Adds a source identifier to an existing RDS event notification
        subscription.
      operationId: addsourceidentifiertosubscription
      x-api-path-slug: actionaddsourceidentifiertosubscription-get
      parameters:
      - in: query
        name: SourceIdentifier
        description: The identifier of the event source to be added
        type: string
      - in: query
        name: SubscriptionName
        description: The name of the RDS event notification subscription you want
          to add a source identifier to
        type: string
      responses:
        200:
          description: OK
      tags:
      - Subscriptions
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