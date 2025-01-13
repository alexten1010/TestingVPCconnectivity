# Testing VPC Connectivity

## VPC Connectivity Project is a guide and implementation for establishing secure and efficient connectivity between Virtual Private Clouds (VPCs) in AWS and other networks. This project demonstrates various methods to connect resources within and across VPCs, regions, and on-premises networks.


## Setup and Installation


## Prepare Your Environment:

1. Define environment variables:

cp .env.example .env

2. Update the .env file with your AWS Region, VPC IDs, subnet IDs, and other configurations.

3. Run Deployment Scripts:

4. Deploy VPC peering connections:

 python deploy_peering.py

6. Configure Transit Gateway:

python setup_transit_gateway.py

7. Establish VPN connectivity:

python setup_vpn_connection.py

8. Verify Connectivity:

Use AWS Management Console or AWS CLI to confirm the connections.

Test communication between resources using ping or application-level checks.
