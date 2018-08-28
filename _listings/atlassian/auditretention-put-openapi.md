---
swagger: "2.0"
x-collection-name: Atlassian
x-complete: 0
info:
  title: Confluence Cloud API Set retention period
  description: "Sets the retention period for records in the audit log. The retention
    period \ncan be set to a maximum of 20 years.\n\n**[Permissions](https://confluence.atlassian.com/x/_AozKw)
    required**: \n'Confluence Administrator' global permission."
  termsOfService: http://atlassian.com/terms/
  version: 1.0.0
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /audit/retention:
    get:
      summary: Get retention period
      description: "Returns the retention period for records in the audit log. The
        retention \nperiod is how long an audit record is kept for, from creation
        date until \nit is deleted.\n\n**[Permissions](https://confluence.atlassian.com/x/_AozKw)
        required**: \n'Confluence Administrator' global permission."
      operationId: com.atlassian.confluence.plugins.restapi.resources.AuditResource.getRetentionPeriod_get
      x-api-path-slug: auditretention-get
      responses:
        200:
          description: OK
      tags:
      - Retention
      - Period
    put:
      summary: Set retention period
      description: "Sets the retention period for records in the audit log. The retention
        period \ncan be set to a maximum of 20 years.\n\n**[Permissions](https://confluence.atlassian.com/x/_AozKw)
        required**: \n'Confluence Administrator' global permission."
      operationId: com.atlassian.confluence.plugins.restapi.resources.AuditResource.setRetentionPeriod_put
      x-api-path-slug: auditretention-put
      responses:
        200:
          description: OK
      tags:
      - Set
      - Retention
      - Period
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