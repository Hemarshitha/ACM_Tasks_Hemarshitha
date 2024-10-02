Hey There!
This is regarding the TASK-4 about deloying a web application on AWS ..I was trying to deploy the portfolio from TASK-1..
First i created AWS Account and then went to AWS management console---->IAM and then went to Roles and created a role by choosing the AWS service as EC2 and attaching AmazonS3FullAccess policy and then named it as WEB-APP-EC2-ROLE..Next i launched an instance by choosing Amazon Linux as AMI and t2.micro as instance type and connected the role i created previously and changed the inbound rules of security group like SSH(PORT22) and HTTP(PORT80) and HTTPS(PORT443) and launched the instance by leaving all the others as default.
Now,in S3 i created a Bucket named my-portfolio-site-resume and then i uploaded my web application to it.
Next was setting up Route 53 for DNS Management...I created a public hosted zone called portfolioexample.com and then the record type was set to A and was pointed to my publicIP...
Next is connecting the Test Application...

