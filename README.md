# ApiGatewayProxy
Proxy for API gateway to SNS topic. Used for quickly spinning up API gateway that sends a HTTP Post body to SNS topic. 

## Installation

[aws-cli](https://docs.aws.amazon.com/cli/latest/userguide/cli-chap-install.html)
or
[sam-cli](https://docs.aws.amazon.com/serverless-application-model/latest/developerguide/serverless-sam-cli-install.html)

## Usage

| Parameters | Description | Default|
| --- | --- | --- |
| PathUrl | Webendpoint for the POST request to come | webhook |
| StageName | Api Gateway stage name for the deployment| prod |

