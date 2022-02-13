# cloudfront-s3-terrform


For running the Terraform script:


1. terraform init

2. terrform apply 

3. You can input the environment name , application name tag to create the s3 bucket with name as environmentname-application name
   eg : dev-demohari-s3
   
4. The Terrform script will do the following things 


1. Create cloudfront and s3
2. Integrate cloudfront and s3
3. Kept the s3 as private and enable encryption with default encryption key \
4. Put the index page(Default root object) as "index.html"
5. Enable compression 
6. Enable Price class 200 (Edge location : North America, Europe, Asia, Middle East, and Africa)
7. Redirect HTTP to HTTPS 




If you are facing any error related with message "conflicting conditional operation is currently in progress" rerun the script again with same input fields to enable private policy in s3 bucket.

