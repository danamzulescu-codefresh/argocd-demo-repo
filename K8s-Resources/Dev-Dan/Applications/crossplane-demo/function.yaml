apiVersion: lambda.aws.crossplane.io/v1beta1
kind: Function
metadata:
  name: color-service
spec:
  forProvider:
    packageType: Image
    code:
      imageURI: 336151728602.dkr.ecr.us-east-1.amazonaws.com/dan-a/color-service:red
    role:
      name: crossplane-lambda-role
    region: us-east-1
    tags:
      user: dan
  providerConfigRef:
    name: aws-provider
