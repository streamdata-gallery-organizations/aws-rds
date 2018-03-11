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
  /?Action=DownloadDBLogFilePortion&k=1:
    get:
      summary: Download D B Log File Portion
      description: Downloads all or a portion of the specified log file, up to 1 MB
        in size
      operationId: downloaddblogfileportion
      parameters:
      - in: query
        name: DBInstanceIdentifier
        description: The customer-assigned name of the DB instance that contains the
          log files you want to list
        type: string
      - in: query
        name: LogFileName
        description: The name of the log file to be downloaded
        type: string
      - in: query
        name: Marker
        description: The pagination token provided in the previous request or 0
        type: string
      - in: query
        name: NumberOfLines
        description: The number of lines to download
        type: string
      responses:
        200:
          description: OK
      tags:
      - log files
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