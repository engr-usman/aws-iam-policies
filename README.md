# AWS-IAM-Policies

I am AWS Trainer and I have writted these IAM policies to restrict my students to use limited resources while performing AWS Labs so I can manage my billing. 

PFB the details of these policies.

1- First Policy is to launch EC2 instances with limited access
    - Just t2.micro instances
    - EBS GP2 volume
    - Create security group
    - Create Key Pair
    - Attach IAM Role
    
2- Second Policy to restrict user to use Route53 single hosted zone. I have 2 hosted zones in my Route53 service. First hosted zone is in production and second hosted zone is for performing Labs so I have written this policy to restrict my students to just use second hosted zone. 
