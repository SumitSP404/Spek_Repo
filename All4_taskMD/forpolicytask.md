# Task - 1
## Hosting Web Server

#### Linux

Below are the images that reflects the hosting of web serevr through linux operating system

![](./Images/Screenshot%20(333).png)

![](./Images/Screenshot%20(335).png)

![](./Images/Screenshot%20(337).png)

![](./Images/Screenshot%20(334).png)

CFT:- [Linux](https://linuxodlcl.s3.amazonaws.com/CloudLabs2Linux.json)

---

#### Windows

Below are the images that reflects the hosting of web serevr through Windows operating system

![](./Images/Screenshot%20(324).png)

![](./Images/Screenshot%20(325).png)

![](./Images/Screenshot%20(326).png)

![](./Images/Screenshot%20(327).png)

CFT:- [Windows](https://clodldemo2.s3.amazonaws.com/CloudLab1.yml)

---

# Task - 2
## 	AWS: Creating-S3-from-Ec2

1.**CloudFormation Template Creation**: I created two JSON files as CloudFormation templates. One was dedicated to parameter configuration, and the other focused on setting up an IAM role named 'EC2AccessForS3' for an EC2 instance.

2.**IAM Policy Creation**: In order to grant specific permissions, I crafted an IAM policy within the role 'EC2AccessForS3'. This policy was designed to allow the creation and listing of S3 buckets.

3.**Instance Profile Configuration**: To seamlessly pass the IAM role to the EC2 instance, I established a 'RootInstanceProfile'. where i referred it to EC2 instance

4.**EC2 Configuration**: PasswordAuthentication was enabled for the EC2 instance, and I utilized UserData to create an S3 bucket during the instance setup process.

5.**S3 Bucket Deployment**: Both CloudFormation template files were stored in an S3 bucket with public access for easy deployment.

EC2ACCESSS3 cft link : [EC2ACCESSS3_CFT](https://test-sumit-ec2accesss3.s3.amazonaws.com/CloudLabs2Linuxrole.json)
Parameters link : [PARAMETERS](https://test-sumit-ec2accesss3.s3.amazonaws.com/TrailParameters.json)

6.**Deployment and Registration**: The templates were deployed via CloudLabs CloudFormation Template and subsequently in ODL. Users were registered through a [bit.ly] URL, and upon launching the lab, they received details about the lab environment and associated resources.

7.**Testing** : Upon connecting to the EC2 instance via SSH, users successfully created and listed S3 buckets

![](./Images/Screenshot%20(339).png)

![](./Images/Screenshot%20(340).png)

![](./Images/Screenshot%20(341).png)

![](./Images/Screenshot%20(342).png)

![](./Images/Screenshot%20(343).png)

---

# Task-3
## AWS: Creating-S3-With-Policy and restricting the user with certain action
#### Screenshots here demonstrate the user's ability to perform all actions specified in the policy.

![](./Images/Screenshot%20(349).png)

![](./Images/Screenshot%20(350).png)

![](./Images/Screenshot%20(351).png)

![](./Images/Screenshot%20(352).png)

![](./Images/Screenshot%20(353).png)

![](./Images/Screenshot%20(354).png)

![](./Images/Screenshot%20(355).png)

![](./Images/Screenshot%20(356).png)

![](./Images/Screenshot%20(357).png)

![](./Images/Screenshot%20(358).png)

![](./Images/Screenshot%20(359).png)

![](./Images/Screenshot%20(360).png)

![](./Images/Screenshot%20(361).png)

![](./Images/Screenshot%20(362).png)

![](./Images/Screenshot%20(363).png)

![](./Images/Screenshot%20(364).png)

![](./Images/Screenshot%20(365).png)

![](./Images/Screenshot%20(366).png)

![](./Images/Screenshot%20(367).png)

---

#### Below images depict instances where the user's actions were denied due to conditions not meeting the specified criteria, such as:

- Region: us-east-1
- AMI: AWS Linux
- Instance type: t3.micro or t3.nano
- Volume type and size: gp3 and 30 GB.

![](./Images/Screenshot%20(368).png)

![](./Images/Screenshot%20(369).png)

![](./Images/Screenshot%20(370).png)

![](./Images/Screenshot%20(371).png)

![](./Images/Screenshot%20(372).png)

![](./Images/Screenshot%20(373).png)

![](./Images/Screenshot%20(374).png)

![](./Images/Screenshot%20(375).png)

![](./Images/Screenshot%20(376).png)

#### Here are the resources screenshot from cloudlabs admin console

![](./Images/Screenshot%20(377).png)

![](./Images/Screenshot%20(378).png)

![](./Images/Screenshot%20(379).png)

![](./Images/Screenshot%20(380).png)

![](./Images/Screenshot%20(381).png)

![](./Images/Screenshot%20(382).png)

The policy that i have created:- [Policy](https://policyiam-for-odl.s3.amazonaws.com/forpolicy.json)
And S3 bucket creation CFT:- [CFT](https://policyiam-for-odl.s3.amazonaws.com/news3bucket.json)

---

# Task - 4

#### Data Migration and Relational Database

Github MasterDoc Link: [MasterDoc](https://github.com/SumitSP404/Spek_Repo)

Below are the images that reflect the process of creating the user with mentioned policy and with role. Here the AMI id which is used was by creating the insatnce image which contains the chrome and SQL Server and Workbench aswell. And the workbench consist of a database and the user who will be alloted to that lab will be performing the Data Migration task using that database.

![](./Images/Screenshot%20(383).png)

![](./Images/Screenshot%20(384).png)

![](./Images/Screenshot%20(385).png)

![](./Images/Screenshot%20(387).png)

![](./Images/Screenshot%20(388).png)

![](./Images/Screenshot%20(389).png)

![](./Images/Screenshot%20(390).png)

![](./Images/Screenshot%20(391).png)

![](./Images/Screenshot%20(392).png)

![](./Images/Screenshot%20(393).png)

![](./Images/Screenshot%20(394).png)

![](./Images/Screenshot%20(396).png)

CFT link :- [CFT](https://rds-dms-ec2.s3.amazonaws.com/rds-dms-folder/rds-dms.json)
Parameters link:- [parameters](https://rds-dms-ec2.s3.amazonaws.com/rds-dms-folder/param.json)
Policy link:- [Policy](https://rds-dms-ec2.s3.amazonaws.com/rds-dms-folder/new1policy.json)
