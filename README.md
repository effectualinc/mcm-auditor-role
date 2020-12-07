# Effectual MCM Auditor

Template to deploy a cross-account role that enables secure access for Effectual MCM Cloud Audit.

## Prerequisites

The following prerequisites will need to be met to launch the MCM Auditor solution in your account.

1. The person launching the stack should be logged into the target account with IAM full access (if the user is logged in as an admin this will meet the requirement)
2. An Effectual representative supplied the value for the stack parameter `AccountId` to the person deploying the stack.

## Deployment

The deployment process leverages AWS CloudFormation and is relatively simple once prerequisites are satisfied. Overall the process entails three steps

**Steps to Deploy:**

1. Open your web browser and login to your AWS Account.
2. Click the `Launch Stack` button below to launch stack.
3. Fill in the parameter value for AWS Account ID (`AccountId`)

> **Note:** If you want to open the link as a new tab use `ctrl+click` when clicking the *launch Stack* button below.

[![Launch Stack](https://cdn.rawgit.com/buildkite/cloudformation-launch-stack-button-svg/master/launch-stack.svg)](https://console.aws.amazon.com/cloudformation/home#/stacks/new?stackName=effectual-mcm-auditor-role&templateURL=https://effectualinc.s3.amazonaws.com/mcm-auditor-role/mcm-auditor-role.yml)

The template requires a single parameter `AccountId`. Your Effectual representative will supply you with the AWS Account ID required. Do not try to launch the stack unless you have this information.
