## aws-delete-default-vpcs
Delete the default VPC in all AWS regions.

Run:
```
$ ./aws-delete-default-vpcs.sh
No default VPC in ap-south-1
No default VPC in eu-west-3
No default VPC in eu-west-2
No default VPC in eu-west-1
No default VPC in ap-northeast-2
No default VPC in ap-northeast-1
No default VPC in sa-east-1
No default VPC in ca-central-1
No default VPC in ap-southeast-1
No default VPC in ap-southeast-2
No default VPC in eu-central-1
Removing default resources in us-east-1
Removed default VPC vpc-091f926f in us-east-1
Removing default resources in us-east-2
Removed default VPC vpc-9694fbff in us-east-2
No default VPC in us-west-1
Removing default resources in us-west-2
Removed default VPC vpc-420ae424 in us-west-2
```

Requires:
- `aws-cli`
- `jq`

More information about default VPCs and default subnets and how to create one can be found [here](https://docs.aws.amazon.com/vpc/latest/userguide/default-vpc.html).
