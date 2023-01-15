# This is My CDK TypeScript project

AWS CDK のハンズオン。 https://cdkworkshop.com/ja/

追加で, cdk の diagram 自動生成できる　`cdk-dia` も試した.

<table>
    <tr>
        <td>
            <img src="https://gyazo.com/6a04ae4d6362ce5e83bfd3fc357ca221/raw" alt="">
        </td>
    </tr>
</table>

## Useful commands

* `npm run build`   compile typescript to js /* typescript を js にコンパイルする */
* `npm run watch`   watch for changes and compile /* 変更を監視してコンパイルする */
* `npm run test`    perform the jest unit tests /* jest単体テストを実行する */
* `cdk run draw`    create an App structure image with draw.io /* draw.io で アプリ構造イメージを作成する */
* `cdk deploy`      deploy this stack to your default AWS account/region /* このスタックをデフォルトの AWS アカウント / リージョンにデプロイします */
* `cdk diff`        compare deployed stack with current state /* デプロイされたスタックを現在の状態と比較する */
* `cdk synth`       emits the synthesized CloudFormation template /* 合成された CloudFormation テンプレートを発行します */

## structure

<table>
    <tr>
        <td>
            <img src="diagram.png" alt="this app structure image">
        </td>
        <td>
        </td>
    </tr>
    <tr>
        <td>
            CdkWorkshopStack.Endpoint8024A810
        </td>
        <td>
            https://hi0ndx6sk3.execute-api.ap-northeast-1.amazonaws.com/prod/
        </td>
    </tr>
    <tr>
        <td>
            CdkWorkshopStack.ViewHitCounterViewerEndpointCA1B1E4B
        </td>
        <td>
            https://hthcr0c9ff.execute-api.ap-northeast-1.amazonaws.com/prod/
        </td>
    </tr>
</table>
