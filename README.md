# Azure Functions ハンズオン

2018/03/24 JAZUG福岡(ふくあず) 2018#2 で実施するハンズオンの手順書です。  
イベントページ：https://fukuazu.connpass.com/event/81210/

Azure Functionsの概要については、[こちら](https://docs.microsoft.com/ja-jp/azure/azure-functions/functions-overview)をご覧ください。


## 今回作成するもの

* HTTPリクエストの内容をもとに、以下のアクションを行う
    * HTTPレスポンスを返す
    * メールを送信する
    * Slackへポストする


## 必要なもの

* Microsoft Azureアカウント
    * [無料試用アカウント](https://azure.microsoft.com/ja-jp/free/) (要クレジットカード)
    * (学生向け) [Microsoft Imagine](https://imagine.microsoft.com/ja-jp/account)
* 開発環境(2018/03時点)
    * Node 8.0+(v8.10.0)
    * Azure Core Function Tools 2.0(2.0.1-beta.23-1)
        * `npm install -g azure-functions-core-tools@core`
    * .NET Core 2.0(2.1.4) [Windows](https://www.microsoft.com/net/download/windows/build) | [Mac](https://www.microsoft.com/net/download/macos)
    * [Visual Studio Code(1.21.0)](https://code.visualstudio.com)
    * [Azure Account(0.3.1)](https://marketplace.visualstudio.com/items?itemName=ms-vscode.azure-account) (Visual Studio Code拡張)
    * [Azure Functions for Visual Studio Code (0.7.0)](https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-azurefunctions) (Visual Studio Code拡張)
* SendGridアカウント(ハンズオン時は提供します)
* Slackスペース(ハンズオン時は提供します)
