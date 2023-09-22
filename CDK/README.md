#THINGS YOU SHOULD KNOW ABOUT CDKS
The AWS CDK(Development Kit) is a tool used by developers or engineers to provision Infastructure(or AWS resources)
using programming language such as java Golang, typescript, javaScript etc.

The Main Concepts of AWS CDK are :
1. App: this is seen as the master plan of your infastructure that contains stacks.
2. Stacks: are simply AWS resources defined in a constructs, constructs are more like classes in
3. programming languages, in python you make use of classes, in golang you make use of structs or
   methods. this is exactly how construct is in CDK.
5. CDK tooL-kit: A CLI for running stacks and apps commands.

6. Runtime Context: this contain values in a key-value pair format that is associated with apps,
   stacks and constructs. As many context values are tied to specific AWS environments, and a
   single AWS CDK application can be launched in multiple environments, it becomes crucial to
   configure context values separately for each environment. This is accomplished by incorporating
   the AWS account and region into the context key, ensuring that values from distinct
   environments remain distinct and avoid conflicts.

7. Commands for the CDK workshop:

   - cdk [command] <StackName> --profile <profile> --region <region>
   - cdk diff: shows added/deleted resources compared to the current stack.
   - cdk ls -> shows all the existing stacks in the directory.
   -  cdk deploy -> deploys CDK changes.
   -  cdk synth -> gets the CloudFormation template created by our AWS CDK app.
   -  cdk destroy -> deletes the CloudFormation stack.
  

STEPS:
1. Create an IDE  using cloud9 with the name "CICD-CDK"
2. we install jq. jq is a lightweight and flexible command-line JSON processor.
   - sudo yum install jq -y

   
