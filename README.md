# NAME: Ryan David Prasad
# REG. NO.: 212224040282

# Deployment-and-configuration-of-a-Private-Cloud-in-AWS
Ex.4 Deployment and configuration of a Private Cloud in AWS

## Aim

To set up of a Private Cloud in AWS.  

---

## Procedure

### 1. Plan Your VPC:
- **Determine your needs:** Define your use case, including application requirements, security needs, and compliance standards.  
- **Plan IP address ranges:** Choose appropriate IP address ranges for your VPC and subnets to avoid conflicts.  
- **Select Availability Zones:** Decide which Availability Zones (AZs) you'll use for your resources, considering redundancy and performance.  
- **Plan internet connectivity:** Determine if you need public internet access and how to configure it.  
- **Define security:** Plan your security groups, network ACLs, and access controls to ensure a secure environment.

### 2. Create Your VPC:
- Sign in to AWS Management Console: Access the VPC console and navigate to the VPC dashboard.  
- Choose "Create VPC": Initiate the VPC creation process.  
- Configure VPC details: Enter the VPC name, CIDR block, Availability Zones, and other necessary settings.  
- Create subnets: Define subnets within your VPC to isolate different parts of your network.  
- Create route tables: Specify how traffic is routed within and outside the VPC.  
- Create security groups: Define access control rules for your resources.

### 3. Deploying Resources:
- Launch EC2 instances: Create and launch virtual machines within your VPC.  
- Set up RDS instances: Deploy databases for your applications.  
- Configure networking: Connect your resources to the appropriate subnets, security groups, and route tables.  
- Deploy other AWS services: Integrate other services like S3 for storage and Lambda for serverless computing.

### 4. Managing and Monitoring:
- Use AWS CloudWatch: Monitor your VPC and resources for performance and health.  
- Configure logging and auditing: Track access and activity within your VPC for security and compliance.  
- Implement security best practices: Regularly review and update your security configuration.  
- Scale and adjust as needed: Adjust your VPC infrastructure to meet changing demands.

---

## Output

### Create VPC
<img width="1917" height="992" alt="Screenshot 2026-11-02 205824" src="https://github.com/user-attachments/assets/e662b16d-baae-4534-9dab-1956fcaae5d2" />
<img width="1917" height="998" alt="image" src="https://github.com/user-attachments/assets/469041e1-12b2-4809-bd3d-2cca4b22b7b2" />


### Creating Subnets
<img width="1917" height="995" alt="image" src="https://github.com/user-attachments/assets/85a933f9-f40f-47f5-863f-d34966a04170" />

<img width="1917" height="997" alt="image" src="https://github.com/user-attachments/assets/7891e2ab-5da9-4f04-a65f-05d8f4c12b52" />

### Configuring Subnets
<img width="1917" height="995" alt="image" src="https://github.com/user-attachments/assets/f33db30c-831d-4243-b881-190a88598fd4" />

<img width="1917" height="987" alt="image" src="https://github.com/user-attachments/assets/bfaa66a5-3f8d-4ff1-8a0c-568a5ca2e31f" />

<img width="1917" height="992" alt="Screenshot 2026-11-02 211307" src="https://github.com/user-attachments/assets/a243fd58-dc7d-4a62-8c31-126a299dd484" />

<img width="1917" height="991" alt="Screenshot 2026-11-02 211810" src="https://github.com/user-attachments/assets/798d5476-1193-48be-952b-bf7c4b42af36" />

<img width="1916" height="987" alt="Screenshot 2026-11-02 211818" src="https://github.com/user-attachments/assets/252fcf12-2867-4bcd-938c-3e79206cc73a" />

<img width="1917" height="988" alt="Screenshot 2026-11-02 211834" src="https://github.com/user-attachments/assets/2141ea16-c1fa-4f61-a117-89a6de5be34a" />

<img width="1917" height="997" alt="image" src="https://github.com/user-attachments/assets/04b53985-2c70-4282-ae1e-82506701e44d" />

<img width="1172" height="133" alt="image" src="https://github.com/user-attachments/assets/d0456bbf-f488-4148-aeb7-7c6efc1bd806" />


## Result

Thus, a  private cloud on AWS involves using VPCs has been created for  a dedicated, isolated network where we can manage our resources and control access according to our requirements.
---
