# TerraFlow

`TerraFlow` is a GitHub actions workflow for running terraform.

## Prerequisites

Terraform assumes the following is already in place:

1. Remote state backend and locking table:
   Bucket name: `terraflow-state-${AWS_ACCOUNT_ID}`
   DynamoDB table name: `terraflow-lock-${AWS_ACCOUNT_ID}`
1. SSM parameters to lookup AWS Account ID's based on aws account prefix and environment
