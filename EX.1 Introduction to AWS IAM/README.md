# Lab 1 - Introduction to AWS Identity and Access Management (IAM)

## Title
Introduction to AWS Identity and Access Management (IAM)


## Objective
The objective of this lab is to understand how AWS Identity and Access Management (IAM) controls authentication and authorization in AWS. The lab focuses on exploring IAM users and groups, analyzing attached policies, assigning users to appropriate groups based on organizational roles, and validating permissions by testing service access.


## Prerequisites
- Basic understanding of cloud computing concepts  
- AWS Academy Lab access  
- Web browser with internet connectivity  


## Tools Used
- AWS Management Console  
- AWS Identity and Access Management (IAM)  
- Amazon EC2  
- Amazon S3  


## Tasks Performed

### Task 1: Explore IAM Users and Groups
- Reviewed pre-created IAM users: user-1, user-2, user-3  
- Explored IAM groups: EC2-Admin, EC2-Support, S3-Support  
- Inspected managed and inline policies attached to groups  
**Screenshot:**
  
<img width="1906" height="838" alt="Screenshot 2026-07-31 144654" src="https://github.com/user-attachments/assets/be75eb02-db38-41d2-bca7-a40c625715a4" />


### Task 2: Add Users to Groups
- Added user-1 to the S3-Support group  
- Added user-2 to the EC2-Support group  
- Added user-3 to the EC2-Admin group  
**Screenshot:**
  <img width="1906" height="838" alt="Screenshot 2026-07-31 144654" src="https://github.com/user-attachments/assets/67faddbb-09fa-4d94-bbbc-ea81df574791" />
 
<img width="1912" height="859" alt="Screenshot 2026-07-31 144644" src="https://github.com/user-attachments/assets/dd9cd439-9feb-47e0-be28-a9680e5f6204" />
<img width="1915" height="928" alt="Screenshot 2026-07-31 144633" src="https://github.com/user-attachments/assets/d6d40c12-cfb7-4efc-a8cc-30eb7a65e891" />

### Task 3: Test IAM User Permissions
- Logged in using IAM sign-in URL  
- Verified S3 access for user-1  
- Verified EC2 read-only access for user-2  
- Verified EC2 administrative access for user-3  
**Screenshot:**  
<img width="1915" height="937" alt="Screenshot 2026-07-31 150414" src="https://github.com/user-attachments/assets/ae01706d-60ab-4076-9e1c-1d30124e3041" />
<img width="1908" height="954" alt="Screenshot 2026-07-31 145512" src="https://github.com/user-attachments/assets/ce4f993f-6c5f-465c-83d7-47cadb0097dc" />
<img width="1915" height="910" alt="Screenshot 2026-07-31 145809" src="https://github.com/user-attachments/assets/823d285c-e394-4987-b45c-1ed696ccc758" />

<img width="1915" height="890" alt="Screenshot 2026-07-31 144948" src="https://github.com/user-attachments/assets/4d41ce16-033b-4f15-b7ba-108e22f43003" />

## Workflow
1. Accessed IAM console and reviewed users and groups.  
2. Inspected policy permissions attached to groups.  
3. Assigned users to groups based on their roles.  
4. Logged in as each IAM user using the sign-in URL.  
5. Validated permissions by accessing AWS services.  


## Learning Outcomes
- Understood the role of IAM in AWS security.  
- Learned how IAM users, groups, and policies interact.  
- Gained practical experience implementing role-based access control.  
- Verified permission enforcement through real-time service testing.  


## Conclusion
This lab provided hands-on experience with AWS IAM by demonstrating how organizations manage secure access to cloud resources. Assigning users to groups with predefined policies simplified permission management and ensured role-based access control across AWS services.


## Author
**Name:**Rithika R 212224240136
**Course:** Introduction to Cloud Computing  

