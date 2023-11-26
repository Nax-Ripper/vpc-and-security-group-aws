# vpc-and-security-group-aws
VPC and Security group in AWS Project

## Project Overview

![Alt text](image.png)

#### Key components

- Internet Gateway
- Route Table
- Public IP 
- Private IP
- NACL
- Security Group

### 1. Create Custom VPC
![Alt text](image-1.png)

### 2. Attach custom VPC to instance 
![Alt text](image-2.png)

### 3. Assign subnets to the instance

![Alt text](image-3.png)

### 4. Edit Security Groups

![Alt text](image-4.png)

- Now can access the web page

![Alt text](image-5.png)

- Try to edit nacl by deny port 8000
- The rule number is important , it will look for the smallest rule number to the larger
![Alt text](image-7.png)

- now cannot access the webpage
- we deny port 8000 in subnet level using nacl

![Alt text](image-8.png)