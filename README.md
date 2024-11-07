# AWS-Certified-Cloud-Practitioner-CLF-C01/CLF-C02
# Questions we need to know

1- Which AWS service provides a global content delivery network (CDN)? 

A) Amazon S3

B) AWS Global Accelerator

C) Amazon CloudFront

D) AWS WAF
 <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C
    </details>

2- The ability to horizontally scale Amazon EC2 instances based on demand is an example of which concept?
  
A. Economy of Scale

B. Elasticity

C. High availability

D. Agility
 <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B
    </details>

3- What is the main benefit of using AWS Availability Zones?

A) Improved billing accuracy

B) Enhanced data encryption

C) Increased redundancy and fault tolerance

D) Simplified user access management
 <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C
    </details>

4- Which of the following pillars is NOT part of the AWS Well-Architected Framework?

A) Operational Excellence

B) Security

C) Cost Management

D) Performance Efficiency
 <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C
    </details>

5- The AWS Well-Architected Framework provides best practices to help you design and operate reliable, secure, efficient, and cost-effective systems in the cloud. Which pillar focuses specifically on the ability to recover from failures and meet customer demand?

A) Security

B) Reliability

C) Performance Efficiency

D) Cost Optimization
<details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B
    </details>

6- What is the primary purpose of the AWS Well-Architected Tool?

A) To deploy applications on AWS

B) To monitor and manage costs

C) To evaluate and improve cloud architectures 

D) To automate infrastructure deployment
<details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C
    </details>

7- In the context of the AWS Well-Architected Framework, which of the following is an important practice under the Cost Optimization pillar?

A) Using only on-demand instances

B) Automating infrastructure provisioning

C) Implementing security best practices

D) Continuously monitoring and analyzing usage 
<details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer:D
    </details>
8- Which of the following is an example of AWS’s responsibility under the Shared Responsibility Model?

A) Managing access control lists (ACLs)

B) Patching the hypervisor

C) Encrypting the customer's data in transit

D) Managing encryption keys in AWS KMS
<details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer:B
    </details>
 9-  Which of the following does the customer NOT manage under the AWS Shared Responsibility Model?

A) Configuring IAM users and roles

B) Monitoring and logging AWS infrastructure performance

C) Securing applications running on EC2

D) Applying security patches to the operating system on EC2
<details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer:B
    </details>
 10- In terms of the Shared Responsibility Model, who is responsible for the security of the guest operating system running on an EC2 instance?

A) AWS

B) The customer

C) AWS and the customer

D) The security team of the instance's region
<details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer:B
    </details>

11- Which of the following IAM features allows for automatic policy evaluation when a user attempts to access a resource?

A) IAM Access Analyzer

B) AWS Organizations Service Control Policies (SCPs)

C) IAM Policy Simulator

D) IAM Policy Evaluation Engine    
<details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer:D
    </details>
12- You have attached a policy to an IAM role that grants full access to all Amazon S3 actions. What happens if another policy attached to the same role denies access to s3:PutObject?

A) The s3:PutObject action is allowed due to the permissive nature of the full access policy

B) The s3:PutObject action is denied due to explicit deny overriding any allow

C) The s3:PutObject action is allowed due to implicit permission inheritance

D) The IAM role will fail to execute any action on Amazon S3
<details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer:B
    </details>

12- You are configuring cross-account access to an S3 bucket for an IAM user in another AWS account. What is the best approach to achieve this?

A) Attach a bucket policy to the S3 bucket granting the IAM user permission

B) Attach an IAM policy directly to the user in the other account with the necessary S3 permissions

C) Use AWS Organizations to grant cross-account access

D) Attach a role to the IAM user in the other account and allow them to assume it via a trust relationship
<details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer:A
    </details>

13- How can you restrict the use of an IAM user's API keys to a specific AWS region, preventing them from making API calls in any other region?

A) Use IAM policy conditions with the aws:RequestedRegion condition key

B) Attach an IAM policy to deny access to all regions except the specified one

C) Configure the IAM user’s profile to limit region access

D) Use AWS Config rules to enforce region-based access control
<details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer:A
    </details>
    
14- Which of the following IAM actions allows an administrator to provide an IAM user with temporary credentials with a specific expiration time?

A) Attach an inline policy with an expiration condition
B) AssumeRole
C) CreateAccessKey
D) GetFederationToken
<details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer:B
    </details>

15- What is the maximum number of managed IAM policies that can be attached to a single IAM role?

A) 5

B) 10

C) 15

D) 20
<details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer:B
    </details>








