# Vitality-Sphere
Vitality Sphere is a health and wellness company dedicated to improving the well-being of its clients through a variety of services and products.Vitality Sphere will achieve a more scalable, cost-effective, and efficient infrastructure for their website, along with valuable insights into user interactions and a streamlined deployment process.

# Purpose:
This document provides standardized naming conventions for AWS resources created during projects associated with Vitality Sphere. These guidelines ensure that all resources are named consistently, making them easily identifiable, searchable, and manageable across the team.

# Scope:
Applies to all AWS resources created by Engineers at Vitality Sphere, including but not limited to EC2 instances, S3 buckets, RDS databases, and Lambda functions.

# Naming Convention Format:
All AWS resources must adhere to the following naming convention format:
<VitalitySphere>-<Environment>-<ResourceType>-<UniqueID>-<FunctionalDescription>

# Components Explanation:
VitalitySphere:
A constant prefix to denote the company associated with the resource.
Example: VitalitySphere
Environment:
Identifies the environment for which the resource is provisioned.
Use Dev for development, Test for testing, Prod for production, and Stage for staging environments.
Example: Dev, Prod
ResourceType:
Specifies the type of AWS resource.
Use abbreviations like EC2 for Elastic Compute Cloud, S3 for Simple Storage Service, RDS for Relational Database Service.
Example: EC2, S3
UniqueID:
A unique identifier which could be a numeric sequence or team identifier that students can choose, like TeamA, 001.
Example: 001, TeamA
FunctionalDescription:
A brief descriptive name explaining the resource's purpose.
Example: Webserver, UserDB
# Examples:
EC2 instance for production web server: VitalitySphere-Prod-EC2-001-Webserver
S3 bucket for development data storage: VitalitySphere-Dev-S3-002-DataStore
RDS database for production user profiles: VitalitySphere-Prod-RDS-003-UserProfiles
#Guidelines for Use:
Ensure that the naming convention is followed during the creation of all resources to maintain consistency.
Avoid using spaces or special characters that are not supported or recommended in AWS resource names.
Review and update the naming conventions periodically to reflect any changes in project scope or AWS services.

