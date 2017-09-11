
# This has moved to https://github.com/Dome9/onboarding-scripts
# Please check there for all future updates


# Dome9-OnBoarding-CFT
CloudFormation Template that Prepare Role on AWS account to connenct to Dome9 


<u>The Process:<u>

1. Choose file according to the protection mode you prefer (Read Only or Full Protect)
2. Create new CFT stack
3. Use the parameter "Externalid" from the onboarding process under "Create Role" step.
4. Make sure you check "I acknowledge that AWS CloudFormation might create IAM resources." in the console or use "--capabilities CAPABILITY_IAM" in cli command. 
5. After the process finished, a new role is created which will contain the "role ARN" and the "External ID" that required to enter.

1. Choose file according to the protection mode you prefer (Read Only or Full Protect)
![on-boarding-cft - Staging](https://github.com/Dome9/wiki/blob/master/images/on-boarding-cft.png)

2. Create new CFT stack and use the downloaded file 
Inline image 2

Enter External ID according to the Create role step
Inline image 4

Inline image 3

On progress
Inline image 5


Inline image 6
