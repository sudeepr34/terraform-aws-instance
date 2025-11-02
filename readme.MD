# AWS EC2 Instance

This module creates EC2 Instance

#### Input

* ami_id - (Optional) Defaults to ''' ami-09c813fb71547fc4f '''
* instance_type - (Required) User must supply intance type either t3.micro or t3.small or t3.medium
* sg_ids - (Required) User must supply a list of security groupp IDS to attach to EC2 Instance
* tags - (Optional) User can supply tags to attach to EC2 Instance


#### Output

* public_ip - Public IP of the Instance Created
* private_ip - Private IP of the Instance Created