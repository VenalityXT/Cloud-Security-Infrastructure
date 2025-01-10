# Infrastructure Design

## Architecture Overview
The cloud infrastructure was designed with high availability, scalability, and security in mind. The architecture includes multiple **VPCs** for isolation and segmentation of different environments (e.g., production, staging, testing).

- **AWS VPC Configuration**:  
  - Public and private subnets for separation of resources.
  - Internet Gateway for public access to selected services.
  - Route tables and Network ACLs for controlling traffic flow. 

- **Azure VNet Configuration**: 
  - Hub-and-spoke network topology for segmenting workloads.
  - Network Security Groups (NSGs) for granular control over inbound and outbound traffic.

## Key Security Considerations:
- **Encryption**: All sensitive data is encrypted at rest and in transit using AWS **KMS** and Azure **Key Vault**.
- **IAM Policies**: Access control is enforced using strict IAM roles and policies to ensure least-privilege access.
