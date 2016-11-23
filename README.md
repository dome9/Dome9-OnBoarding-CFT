# Dome9-OnBoarding-CFT
CloudFormation Template to connenct  AWS account to Dome9 


<u>The Process:<u>

1. Create new CFT stack
2. Choose file according to the protaction mode you choose (Read Only aor Full Protect)
3. Use parameter "Externalid" tou got from the onboarding process
4. Make sure you check "I acknowledge that AWS CloudFormation might create IAM resources." in the concule or use "--capabilities CAPABILITY_IAM" in cli command. 
5. When the process will finish you will get the "role ARN" and the "External ID"
 