swagger: "2.0"
x-collection-name: Atlassian
x-complete: 1
info:
  title: Stride API
  description: this-service-provides-public-api-for-the-stride-
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