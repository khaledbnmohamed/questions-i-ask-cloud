# Question I ask the seniors at work [Cloud Edition]
Questions I ask the seniors [mostly] at cloud



* **Q1**) Can I use GetAtt Param.parent ex: use `!GetAttr (!Ref MyChosenSubnet).Vpc` ?

  A1) 

  **Q2**)  *diff bet NACL and Securty groups and add NACL*

  A2) NACL also adds an additional layer of security associated with subnets that control both inbound and outbound traffic at the subnet level.

  ![](q2.png)

  **Q3**)  *difference between s3 and s3api in aws CLI*

  A3) All commands in s3api can be done in s3 because s3 uses s3api

  **Q4**)  *difference between s3 and s3api in aws CLI*

  A4) All commands in s3api can be done in s3 because s3 uses s3api

# General Notes and Hints

- List all within the s3 bucket by using --recursive

# Good Resources

- https://www.javatpoint.com/aws-nacl-vs-security-group
- [A good article talking about best practices and tools to boost your CloudFormation experience](https://sanderknape.com/2018/08/two-years-with-cloudformation-lessons-learned/) 
