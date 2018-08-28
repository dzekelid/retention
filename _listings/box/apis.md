---
name: Box
x-slug: box
description: Box is changing how you manage content across your business from simple
  file sharing to building custom apps.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/162-box.jpg
x-kinRank: "9"
x-alexaRank: "445"
tags: Retention
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/retention/master/_listings/box/apis.md
specificationVersion: "0.14"
apis:
- name: Box - Create Retention Policy
  x-api-slug: retention-policies-post
  description: Used to create a new retention policy.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/162-box.jpg
  humanURL: http://box.com
  baseURL: https://api.box.com//2.0
  tags: Files, Collaboration, Sharing, Storage, Storage, Stack Network, Stack, Productivity,
    SaaS, Technology, Enterprise, API Provider, Profiles, Publish, Service API, Relative
    Data, Relative StreamRank, Streams, Backups
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/retention/master/_listings/box/retention-policies-post-openapi.md
- name: Box - Get Retention Policies
  x-api-slug: retention-policies-get
  description: Retrieves all of the retention policies for the given enterprise.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/162-box.jpg
  humanURL: http://box.com
  baseURL: https://api.box.com//2.0
  tags: Files, Collaboration, Sharing, Storage, Storage, Stack Network, Stack, Productivity,
    SaaS, Technology, Enterprise, API Provider, Profiles, Publish, Service API, Relative
    Data, Relative StreamRank, Streams, Backups
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/retention/master/_listings/box/retention-policies-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/retention/master/_listings/box/retention-policies-get-openapi.md
- name: Box - Get Retention Policy
  x-api-slug: retention-policiespolicy-id-get
  description: Used to retrieve information about a retention policy
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/162-box.jpg
  humanURL: http://box.com
  baseURL: https://api.box.com//2.0
  tags: Files, Collaboration, Sharing, Storage, Storage, Stack Network, Stack, Productivity,
    SaaS, Technology, Enterprise, API Provider, Profiles, Publish, Service API, Relative
    Data, Relative StreamRank, Streams, Backups
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/retention/master/_listings/box/retention-policiespolicy-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/retention/master/_listings/box/retention-policiespolicy-id-get-openapi.md
- name: Box - Update Retention Policy
  x-api-slug: retention-policiespolicy-id-put
  description: Used to update a retention policy.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/162-box.jpg
  humanURL: http://box.com
  baseURL: https://api.box.com//2.0
  tags: Files, Collaboration, Sharing, Storage, Storage, Stack Network, Stack, Productivity,
    SaaS, Technology, Enterprise, API Provider, Profiles, Publish, Service API, Relative
    Data, Relative StreamRank, Streams, Backups
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/retention/master/_listings/box/retention-policiespolicy-id-put-openapi.md
- name: Box - Get Retention Policy Assignments
  x-api-slug: retention-policiespolicy-idassignments-get
  description: Returns a list of all retention policy assignments associated with
    a specified retention policy.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/162-box.jpg
  humanURL: http://box.com
  baseURL: https://api.box.com//2.0
  tags: Files, Collaboration, Sharing, Storage, Storage, Stack Network, Stack, Productivity,
    SaaS, Technology, Enterprise, API Provider, Profiles, Publish, Service API, Relative
    Data, Relative StreamRank, Streams, Backups
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/retention/master/_listings/box/retention-policiespolicy-idassignments-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/retention/master/_listings/box/retention-policiespolicy-idassignments-get-openapi.md
- name: Box - Create Retention Policy Assignment
  x-api-slug: retention-policy-assignments-post
  description: Returns a list of all retention policy assignments associated with
    a specified retention policy.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/162-box.jpg
  humanURL: http://box.com
  baseURL: https://api.box.com//2.0
  tags: Files, Collaboration, Sharing, Storage, Storage, Stack Network, Stack, Productivity,
    SaaS, Technology, Enterprise, API Provider, Profiles, Publish, Service API, Relative
    Data, Relative StreamRank, Streams, Backups
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/retention/master/_listings/box/retention-policy-assignments-post-openapi.md
- name: Box - Get Retention Policy Assignment
  x-api-slug: retention-policy-assignmentsretention-policy-assignment-id-get
  description: Used to retrieve information about a retention policy assignment.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/162-box.jpg
  humanURL: http://box.com
  baseURL: https://api.box.com//2.0
  tags: Files, Collaboration, Sharing, Storage, Storage, Stack Network, Stack, Productivity,
    SaaS, Technology, Enterprise, API Provider, Profiles, Publish, Service API, Relative
    Data, Relative StreamRank, Streams, Backups
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/retention/master/_listings/box/retention-policy-assignmentsretention-policy-assignment-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/retention/master/_listings/box/retention-policy-assignmentsretention-policy-assignment-id-get-openapi.md
- name: Box - Get File Version Retention
  x-api-slug: file-version-retentionsfile-version-retention-id-get
  description: Used to retrieve information about a file version retention
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/162-box.jpg
  humanURL: http://box.com
  baseURL: https://api.box.com//2.0
  tags: Files, Collaboration, Sharing, Storage, Storage, Stack Network, Stack, Productivity,
    SaaS, Technology, Enterprise, API Provider, Profiles, Publish, Service API, Relative
    Data, Relative StreamRank, Streams, Backups
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/retention/master/_listings/box/file-version-retentionsfile-version-retention-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/retention/master/_listings/box/file-version-retentionsfile-version-retention-id-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://botify.api.gallery.streamdata.io
- type: x-api-stack
  url: http://box.stack.network
- type: x-base
  url: https://api.box.com/
- type: x-blog
  url: http://blog.box.com/
- type: x-blog-rss
  url: http://blog.box.com/feed/
- type: x-crunchbase
  url: http://www.crunchbase.com/company/box
- type: x-crunchbase
  url: https://crunchbase.com/organization/box
- type: x-developer
  url: http://developers.box.com
- type: x-github
  url: https://github.com/box
- type: x-pricing
  url: https://developers.box.com/box-platform-pricing/
- type: x-road-map
  url: https://developers.box.com/roadmap/
- type: x-twitter
  url: https://twitter.com/BoxPlatform
- type: x-twitter
  url: https://twitter.com/BoxHQ
- type: x-website
  url: http://box.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---