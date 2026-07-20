
# AWS VPC

VPC = Virtual Private Cloud

A VPC is a private network inside AWS where cloud resources are placed.

Subnet:
A smaller network inside a VPC.

Public Subnet:
- Accessible from the Internet.
- Used for web servers.

Private Subnet:
- Not directly accessible from the Internet.
- Used for databases and internal servers.

Example:

VPC
│
├── Public Subnet
│      └── EC2 Web Server
│
└── Private Subnet
       └── Database
