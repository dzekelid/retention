---
swagger: "2.0"
x-collection-name: AWS Redshift
x-complete: 1
info:
  title: AWS Redshift API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=ModifySnapshotCopyRetentionPeriod:
    get:
      summary: Modify Snapshot Copy Retention Period
      description: |-
        Modifies the number of days to retain automated snapshots in the destination region
                    after they are copied from the source region.
      operationId: modifySnapshotCopyRetentionPeriod
      x-api-path-slug: actionmodifysnapshotcopyretentionperiod-get
      parameters:
      - in: query
        name: ClusterIdentifier
        description: The unique identifier of the cluster for which you want to change
          the retention            period for automated snapshots that are copied
          to a destination region
        type: string
      - in: query
        name: RetentionPeriod
        description: The number of days to retain automated snapshots in the destination
          region after            they are copied from the source region
        type: string
      responses:
        200:
          description: OK
      tags:
      - Snapshots
---