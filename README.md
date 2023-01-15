# Welcome to your CDK TypeScript project

You should explore the contents of this project. It demonstrates a CDK app with an instance of a stack (`CdkWorkshopStack`)
which contains an Amazon SQS queue that is subscribed to an Amazon SNS topic.

The `cdk.json` file tells the CDK Toolkit how to execute your app.

## Useful commands

* `npm run build`   compile typescript to js
* `npm run watch`   watch for changes and compile
* `npm run test`    perform the jest unit tests
* `cdk run draw`    create structure draw.io image
* `cdk deploy`      deploy this stack to your default AWS account/region
* `cdk diff`        compare deployed stack with current state
* `cdk synth`       emits the synthesized CloudFormation template

## structure

<table>
    <tr>
        <td>
            <img src="diagram.png" alt="this app structure image">
        </td>
        <td>
            <p>lambda で 実装した API を APIGateway で 公開する. 
                <a href="https://zvikxhonn6.execute-api.ap-northeast-1.amazonaws.com/prod/" target="_blank" rel="noopener noreferrer">
                    こちらのURL
                </a>
                からお試しできる。
            </p>
        </td>
    </tr>
</table>
