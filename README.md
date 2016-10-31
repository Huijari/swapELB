# swapELB
Get registered EC2 instances from one ELB and programatically add them to another ELB.

## usage
```
swapELB
-dest string
  Destination ELB
-region string
  EC2 region (default "us-east-1")
-role string
  IAM role
-source string
  Source ELB
```
example:
```bash
swapELB -source $SOURCE_ELB_NAME -dest $DESTINATION_ELB_NAME -role $IAM_ROLE
```
