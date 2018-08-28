swagger: "2.0"
x-collection-name: Box
x-complete: 1
info:
  title: Box
  version: 1.0.0
host: api.box.com
basePath: /2.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /retention_policies:
    post:
      summary: Create Retention Policy
      description: Used to create a new retention policy.
      operationId: createRetentionPolicy
      x-api-path-slug: retention-policies-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Documents
      - Retention
      - Policies
    get:
      summary: Get Retention Policies
      description: Retrieves all of the retention policies for the given enterprise.
      operationId: getRetentionPolicies
      x-api-path-slug: retention-policies-get
      parameters:
      - in: query
        name: created_by_user_id
        description: A user id to filter the retention policies by
      - in: query
        name: policy_name
        description: A name to filter the retention policies by
      - in: query
        name: policy_type
        description: A policy type to filter the retention policies by
      responses:
        200:
          description: OK
      tags:
      - Documents
      - Retention
      - Policies
  /retention_policies/{POLICY_ID}:
    get:
      summary: Get Retention Policy
      description: Used to retrieve information about a retention policy
      operationId: getRetentionPolicy
      x-api-path-slug: retention-policiespolicy-id-get
      parameters:
      - in: path
        name: POLICY_ID
      responses:
        200:
          description: OK
      tags:
      - Documents
      - Retention
      - Policies
      - Policy
    put:
      summary: Update Retention Policy
      description: Used to update a retention policy.
      operationId: updateRetentionPolicy
      x-api-path-slug: retention-policiespolicy-id-put
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: POLICY_ID
      responses:
        200:
          description: OK
      tags:
      - Documents
      - Retention
      - Policies
      - Policy
  /retention_policies/{POLICY_ID}/assignments:
    get:
      summary: Get Retention Policy Assignments
      description: Returns a list of all retention policy assignments associated with
        a specified retention policy.
      operationId: getRetentionPolicyAssignments
      x-api-path-slug: retention-policiespolicy-idassignments-get
      parameters:
      - in: path
        name: POLICY_ID
      - in: query
        name: type
        description: The type of the retention policy assignment to retrieve
      responses:
        200:
          description: OK
      tags:
      - Documents
      - Retention
      - Policies
      - Policy
      - ""
      - Assignments
  /retention_policy_assignments:
    post:
      summary: Create Retention Policy Assignment
      description: Returns a list of all retention policy assignments associated with
        a specified retention policy.
      operationId: createRetentionPolicyAssignment
      x-api-path-slug: retention-policy-assignments-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Documents
      - Retention
      - Policy
      - Assignments
  /retention_policy_assignments/{RETENTION_POLICY_ASSIGNMENT_ID}:
    get:
      summary: Get Retention Policy Assignment
      description: Used to retrieve information about a retention policy assignment.
      operationId: getRetentionPolicyAssignment
      x-api-path-slug: retention-policy-assignmentsretention-policy-assignment-id-get
      parameters:
      - in: path
        name: RETENTION_POLICY_ASSIGNMENT_ID
      responses:
        200:
          description: OK
      tags:
      - Documents
      - Retention
      - Policy
      - Assignments
      - Retention
      - Policy
      - Assignment
  /file_version_retentions/{FILE_VERSION_RETENTION_ID}:
    get:
      summary: Get File Version Retention
      description: Used to retrieve information about a file version retention
      operationId: getFileVersionRetention
      x-api-path-slug: file-version-retentionsfile-version-retention-id-get
      parameters:
      - in: path
        name: FILE_VERSION_RETENTION_ID
      responses:
        200:
          description: OK
      tags:
      - Documents
      - File
      - Version
      - Retentions
      - File
      - Version
      - Retention