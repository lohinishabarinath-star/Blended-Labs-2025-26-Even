# Blended-Labs
Lab 1 - Introduction to AWS Identity and Access Management (IAM)

Title
Introduction to AWS Identity and Access Management (IAM)

Objective

The objective of this lab is to understand how AWS Identity and Access Management (IAM) controls authentication and authorization in AWS. The lab focuses on exploring IAM users and groups, analyzing attached policies, assigning users to appropriate groups based on organizational roles, and validating permissions by testing service access.

Prerequisites

Basic understanding of cloud computing concepts
AWS Academy Lab access
Web browser with internet connectivity
Tools Used
AWS Management Console
AWS Identity and Access Management (IAM)
Amazon EC2
Amazon S3
Tasks Performed
Task 1: Explore IAM Users and Groups
Reviewed pre-created IAM users: user-1, user-2, user-3
Explored IAM groups: EC2-Admin, EC2-Support, S3-Support
Inspected managed and inline policies attached to groups
Screenshot:
(Add screenshot here)
Task 2: Add Users to Groups
Added user-1 to the S3-Support group
Added user-2 to the EC2-Support group
Added user-3 to the EC2-Admin group
Screenshot:
(Add screenshot here)
Task 3: Test IAM User Permissions
Logged in using IAM sign-in URL
Verified S3 access for user-1
Verified EC2 read-only access for user-2
Verified EC2 administrative access for user-3

Screenshot:

<img width="1915" height="1078" alt="Screenshot 2026-07-27 142026" src="https://github.com/user-attachments/assets/9ea3d3ac-7699-446c-aa59-092f9d41580e" />

<img width="1917" height="1078" alt="Screenshot 2026-07-27 142407" src="https://github.com/user-attachments/assets/a25fbc07-1986-4483-b53e-a665aeef181b" />

<img width="1920" height="1080" alt="Screenshot 2026-07-27 142958" src="https://github.com/user-attachments/assets/3636f83a-9b1e-45bd-bd05-698bc3ae9c53" />

<img width="1917" height="1078" alt="Screenshot 2026-07-27 144317" src="https://github.com/user-attachments/assets/c7e3f306-fff8-46f0-8889-15e5ebbe1af2" />

<img width="648" height="970" alt="Screenshot 2026-07-27 163656" src="https://github.com/user-attachments/assets/239321e5-1cc9-4bba-a0f1-225105a8d97c" />

Workflow

Accessed IAM console and reviewed users and groups.
Inspected policy permissions attached to groups.
Assigned users to groups based on their roles.

Logged in as each IAM user using the sign-in URL.
Validated permissions by accessing AWS services.
Learning Outcomes
Understood the role of IAM in AWS security.
Learned how IAM users, groups, and policies interact.
Gained practical experience implementing role-based access control.
Verified permission enforcement through real-time service testing.

Conclusion
This lab provided hands-on experience with AWS IAM by demonstrating how organizations manage secure access to cloud resources. Assigning users to groups with predefined policies simplified permission management and ensured role-based access control across AWS services.

Author
Name: LOHINI S 212225240079  
Course: Introduction to Cloud Computing
