# Architecture Design
![alt text](https://github.com/rossenbergvillanuevaramboanga/aws-eks-RDS/blob/main/images/aws-eks-rds.jpg?raw=true)

### 1. Create RDS Database
- #### Review VPC of our EKS Cluster
- #### Create a SG Security Group
- #### Create DB Subnet Group in RDS
- #### Create a RDS Database
### 2. Create Kubernetes externalName service Manifest and Deploy
### 3. Connect to RDS Database using kubectl and create usermgmt schema/db
### 4. In User Management Microservice deployment file change username from root to dbadmin
### 5. Deploy User Management Microservice and Test
### 6. Access Application
