# Troubleshooting

## Issue 1: IAM Permissions for EC2 Instance
- **Problem**: EC2 instance could not access S3 bucket due to IAM permission issues.
- **Solution**: Updated the IAM role policy to grant the EC2 instance access to the S3 bucket with `s3:GetObject` permission.

## Issue 2: VPC Peering Connectivity
- **Problem**: Instances in different VPCs could not communicate.
- **Solution**: Added proper route entries in the route tables and ensured security groups allowed traffic between the VPCs.
