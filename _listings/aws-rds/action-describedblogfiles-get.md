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
  /?Action=DescribeDBLogFiles&k=1:
    get:
      summary: Describe D B Log Files
      description: Returns a list of DB log files for the DB instance
      operationId: describedblogfiles
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
      - blog files
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