Here is the short explanation on what i did, sorry i did not have much time to do a portal that can do a repeatable deployment.

·         Come up with a way to deploy this app and write configuration-as-code to deploy it

·         I will be using AWS/Cloud Formation on deploying the app

Use AWS/Cloudformation to deploy this. You can create a free-tier aws account
Cloudformation in aws can use the scrip Json or YAML, I created a 1st YAML script to create a well secured VPC and security group, 2nd YAML File is to provision the EC2 instance with all the required software need by the developers below is the bash script

