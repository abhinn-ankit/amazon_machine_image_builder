# AWS AMI

## Validate Template

```
packer validate centos-ami-template.json
```

## Build AMI

```
packer build -var 'aws_region=us-east-1' centos-ami-template.json
```
