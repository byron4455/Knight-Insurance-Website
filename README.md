Knight Insurance Website
==================================================

This website was built for a business owner local to myself. It utilizes HTML, CSS, JavaScript and PHP in the near future. This deployment used AWS CodeStar along with 
Pipelines to build and deploy the code from this repository. 

Website uses a template by BootsrapMade https://bootstrapmade.com/

![KnightWebsite](https://user-images.githubusercontent.com/84740306/176028746-1ab24c23-a695-491f-9296-98c7ee693fb5.PNG)


What's Here
-----------

This sample includes:

* README.md - this file
* appspec.yml - this file is used by AWS CodeDeploy when deploying the website
  to EC2
* scripts/ - this directory contains scripts used by AWS CodeDeploy when
  installing and deploying your website on the Amazon EC2 instance
* webpage/ - this directory contains static web assets used by your website
  * index.html - this file contains the sample website
* template.yml - this file contains the description of AWS resources used by AWS
  CloudFormation to deploy your infrastructure
* template-configuration.json - this file contains the project ARN with placeholders used for tagging resources with the project ID


