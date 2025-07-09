# AWS EC2 instance
You can create EC2 instance in joindevops using this module

## Inputs

* ami_id(optional) - AMI ID that need to be used by instance
* instance_type (Optional) - Instance type to be used by instance. Valid values are t3.micro, t3.small, t3.medium.. Default is t3.micro
* sg-ids (Required) - A list of security Group IDS to attach instance
* tags (Required) - A map of tags to be associated with instance

## Outputs
* public_ip - Public IP of the instance created
* private_ip - Private IP of the instance created
* instance_id - Instance ID of the instance created
