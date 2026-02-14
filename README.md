https://www.loom.com/share/55df3e6d59f447d98760364f390c82d6
# Creating-a-AWS-Virtual-Machine
A simple, step-by-step guide to creating a Virtual Machine (EC2 instance) in AWS. This repository covers launching an instance, selecting an operating system, choosing an instance type, and creating a key pair—using default network and storage settings. Ideal for beginners learning AWS and cloud fundamentals.
This guide walks you through creating a Virtual Machine (EC2 instance) in **Amazon Web Services (AWS)** using the AWS Management Console.

---

## Prerequisites
- An active AWS account  
- Access to the AWS Management Console  

---

## Step 1: Access the EC2 Service

1. Log in to the **AWS Management Console**.
2. From the **Console Home**, select **EC2**.
   - You can also use the search bar at the top and type **EC2**.

---

## Step 2: Create an EC2 Instance

1. In the EC2 Dashboard, click **Launch Instance**.

---

## Step 3: Configure Instance Details

### 1. Name and Tags
- Enter a **Name** for your instance (e.g., `My-First-EC2`).
- Tags help identify and manage your resources.

---

### 2. Select an Application (AMI)
Choose an **Amazon Machine Image (AMI)**:
- **Linux** (e.g., Amazon Linux, Ubuntu)
- **Windows** (e.g., Windows Server)

This determines the operating system installed on your virtual machine.

---

### 3. Choose an Instance Type
- Select an instance type based on your needs.
- Example:
  - `t2.micro` or `t3.micro` (eligible for AWS Free Tier)

---

### 4. Create a Key Pair (Login)
1. Click **Create new key pair**.
2. Enter a key pair name.
3. Choose a key pair type:
   - **RSA** (commonly used)
4. Choose a private key file format:
   - `.pem` (Linux/macOS)
   - `.ppk` (Windows – PuTTY)
5. Download and securely store the key pair.
   - **You will need this key to log into your instance.**

---

## Step 4: Network Settings
- Leave **Network Settings** as **Default**.
- This includes:
  - Default VPC
  - Default security group
  - Auto-assigned public IP

---

## Step 5: Configure Storage
- Leave **Configure Storage** settings as **Default**.
- AWS automatically assigns recommended storage based on the AMI.

---

## Step 6: Launch the Instance
1. Review all settings.
2. Click **Launch Instance**.

---

## Step 7: Verify Instance Status
- Navigate back to **EC2 → Instances**.
- Confirm the instance state changes to **Running**.

---

## Conclusion
You have successfully created a Virtual Machine (EC2 instance) in AWS. You can now connect to it using:
- **SSH** (Linux)
- **RDP** (Windows)

---

## Next Steps (Optional)
- Connect to your instance
- Configure security groups
- Install applications
- Stop or terminate instances when not in use to avoid charges

---

**Author:** Detron  
**Purpose:** AWS EC2 / Cloud Fundamentals  
