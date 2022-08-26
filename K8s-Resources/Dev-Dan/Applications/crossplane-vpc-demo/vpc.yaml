apiVersion: ec2.aws.crossplane.io/v1beta1
kind: VPC
metadata:
  name: crossplane-vpc-demo
  namespace: crossplane-vpc-demo
spec:
  forProvider:
    region: us-east-1
    cidrBlock: 192.168.0.0/16
    enableDnsSupport: true
    enableDnsHostNames: true
    tags:
    - key: Name
      value: dan-crossplane-demo
    instanceTenancy: default
  providerConfigRef:
    name: aws-provider
