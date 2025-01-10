# Security Configuration

## Identity and Access Management (IAM)
- Configured **IAM roles** for specific use cases (e.g., EC2 instances, Lambda functions) with the principle of least privilege.
- Created **IAM policies** that restrict access to only necessary resources and actions.
 
## Multi-Factor Authentication (MFA)
- Enforced **MFA** for all IAM users and root accounts to enhance access control.
- Configured **AWS MFA** and **Azure MFA** for securing access to the cloud environments.

## Data Encryption
- **AWS**: Used **S3 Server-Side Encryption (SSE)** for data stored in S3, **EBS encryption** for EC2 volumes, and **SSL/TLS** for data in transit.
- **Azure**: Used **Azure Key Vault** for storing and managing secrets, encryption keys, and certificates. Enforced **encryption at rest** for all storage accounts.

## Firewalls and Network Segmentation
- Configured **AWS Security Groups** and **Network ACLs** to control traffic flow between subnets and to/from the internet.
- Implemented **Azure Network Security Groups (NSGs)** to control inbound and outbound traffic to VMs and resources.
  
