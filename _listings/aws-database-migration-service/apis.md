---
name: AWS Database Migration Service
x-slug: aws-database-migration-service
description: AWS Database Migration Service helps you migrate databases to AWS easily
  and securely. The source database remains fully operational during the migration,
  minimizing downtime to applications that rely on the database. The AWS Database
  Migration Service can migrate your data to and from most widely used commercial
  and open-source databases. The service supports homogenous migrations such as Oracle
  to Oracle, as well as heterogeneous migrations between different database platforms,
  such as Oracle to Amazon Aurora or Microsoft SQL Server to MySQL. It also allows
  you to stream data to Amazon Redshift from any of the supported sources including
  Amazon Aurora, PostgreSQL, MySQL, MariaDB, Oracle, SAP ASE and SQL Server, enabling
  consolidation and easy analysis of data in the petabyte-scale data warehouse. AWS
  Database Migration Service can also be used for continuous data replication with
  high-availability.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AWSDatabaseMigrationService.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Resource Tags
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/resource-tags/master/_listings/aws-database-migration-service/apis.md
specificationVersion: "0.14"
apis:
- name: AWS Database Migration Service API - Add Tags To Resource
  x-api-slug: actionaddtagstoresource-get
  description: Adds metadata tags to a DMS resource, including replication instance,
    endpoint, security group, and migration task.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AWSDatabaseMigrationService.png
  humanURL: https://aws.amazon.com/dms/
  baseURL: :///
  tags: Amazon Web Services, Stack Network, API Service Provider, API Service Provider,
    API Provider, Databases, Migrations, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/resource-tags/master/_listings/aws-database-migration-service/actionaddtagstoresource-get-openapi.md
- name: AWS Database Migration Service API - List Tags For Resource
  x-api-slug: actionlisttagsforresource-get
  description: Lists all tags for an AWS DMS resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AWSDatabaseMigrationService.png
  humanURL: https://aws.amazon.com/dms/
  baseURL: :///
  tags: Amazon Web Services, Stack Network, API Service Provider, API Service Provider,
    API Provider, Databases, Migrations, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/resource-tags/master/_listings/aws-database-migration-service/actionlisttagsforresource-get-openapi.md
- name: AWS Database Migration Service API - Remove Tags From Resource
  x-api-slug: actionremovetagsfromresource-get
  description: Removes metadata tags from a DMS resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AWSDatabaseMigrationService.png
  humanURL: https://aws.amazon.com/dms/
  baseURL: :///
  tags: Amazon Web Services, Stack Network, API Service Provider, API Service Provider,
    API Provider, Databases, Migrations, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/resource-tags/master/_listings/aws-database-migration-service/actionremovetagsfromresource-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://aws.data.pipeline.api.gallery.streamdata.io
- type: x-api-stack
  url: http://aws.database.migration.service.stack.network
- type: x-documentation
  url: http://docs.aws.amazon.com/dms/latest/APIReference/Welcome.html
- type: x-faq
  url: https://aws.amazon.com/dms/faqs/
- type: x-getting-started
  url: https://aws.amazon.com/dms/getting-started/
- type: x-partners
  url: https://aws.amazon.com/dms/partners/
- type: x-pricing
  url: https://aws.amazon.com/dms/pricing/
- type: x-schema-conversion
  url: https://aws.amazon.com/dms/#sct
- type: x-testimonials
  url: https://aws.amazon.com/dms/testimonials/
- type: x-website
  url: https://aws.amazon.com/dms/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---