# AWS Marketplace Portal IAM Access Solution

Manage Marketplace portal listings using an IAM role deployed by this CFT

# Description
This template create a trust relationship between an AWS account where you manage your AWS Marketplace Subscriptions (Account A) and another "jump account" (Account B).

After deployment you can access the Account A by switch role from the Account B.

# Deployment

```
$REGION=<Region>
$BUCKET_NAME=stormfsi-solutions
$OBJECT_KEY=marketplace-role/mp-role-v1.json
$EXTERNAL_ACCOUNT=<ACCOUNT_ID>

https://us-east-1.console.aws.amazon.com/cloudformation/home?region=$REGION#/stacks/quickcreate?templateUrl=https%3A%2F%2F$BUCKET_NAME.s3.amazonaws.com%2F/$OBJECT_KEY&stackName=MarketPlacePortalRole&param_AWSAccountId=$EXTERNAL_ACCOUNT&param_AWSRegion=$REGION
```

