# AWS Regions and Availability Zones

## AWS Region

An AWS Region is a geographical location where AWS has multiple data centres.

Companies choose a Region based on:
- Location of users
- Speed (latency)
- Data regulations

The closer the AWS Region is to users, the lower the latency and the faster the response time.

Example:
A UK company may choose the AWS London Region for UK customers.


## Availability Zone (AZ)

An Availability Zone is one or more separate AWS data centres inside an AWS Region.

A Region contains multiple Availability Zones.

Example:

AWS Region: London

        |
 ----------------
 |       |       |


## Why use multiple Availability Zones?

Companies use multiple Availability Zones for high availability.

If one Availability Zone fails because of:
- Power failure
- Hardware problems
- Network problems

Another Availability Zone can continue serving users.

Example:

AZ-1: Server fails ❌

AZ-2: Backup server continues working ✅


## Important Terms

Region:
A geographical AWS location.

Availability Zone:
Separate data centres inside a Region.

Latency:
The delay when data travels between locations.

High Availability:
Keeping applications running even when failures occur.
