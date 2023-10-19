# Lift-Shift-Application-Workload
*	Architecture of AWS Services for the project : EC2 instance, ELB, Autoscaling, EFS/S3 for storage, Amazon Certificate manage, Route53.

*	Multi-tier Web Application stack, which is hosts and run on AWS cloud for production using Lift and Shift strategy.

*	FLOW OF EXECUTION:
  
1. Login to AWS Account
2. Create Key Pairs
3. Create Security groups
4. Launch Instances with user data [BASH SCRIPTS]
5. Update IP to name mapping in route 53
6. Build Application from source code
7. Upload to S3 bucket
8. Download artifact to Tomcat Ec2 Instance
9. Setup ELB with HTTPS [Cert from Amazon Certificate Manager]
10. Map ELB Endpoint to website name in Godaddy DNS
11. Verify
12. Build Autoscaling Group for Tomcat Instances.
