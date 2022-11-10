# MarketplacePortalManagement Solution
Manage Marketplace portal list using cloudFormation

# Description

Define a cloudformation template (JSON format) to create an IAM role. This role trusts our “jump account” from where we are coming and provides us with permission to access and manage the marketplace portal in the destination portal.

# Deployment
https://us-east-1.console.aws.amazon.com/cloudformation/home?region=<Region>#/stacks/quickcreate?templateUrl=https%3A%2F%2Fstormfsi-solutions.s3.amazonaws.com%2F/marketplace-role/mp-role-v1.json&stackName=MarketPlacePortalRole&param_AWSAccountId=<ACCOUNT_ID>&param_AWSRegion=<Region>
