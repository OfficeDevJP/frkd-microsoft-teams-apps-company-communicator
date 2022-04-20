# Company Communicator App Template

| [ドキュメント](https://github.com/OfficeDev/microsoft-teams-company-communicator-app/wiki) | [展開ガイド powershell](https://github.com/OfficeDev/microsoft-teams-company-communicator-app/wiki/Deployment-guide-powershell)  |[展開ガイド](https://github.com/OfficeDev/microsoft-teams-company-communicator-app/wiki/Deployment-guide) | [展開ガイド certificate](https://github.com/OfficeDev/microsoft-teams-company-communicator-app/wiki/Deployment-guide-certificate) | [アーキテクチャ](https://github.com/OfficeDev/microsoft-teams-company-communicator-app/wiki/Solution-overview) |
| ---- | ---- | ---- | ---- | ---- |

Company Communicatorは、企業チームの複数のチームまたは大勢の従業員向けのメッセージをチャットして作成および送信できるようにするカスタムTeamsアプリであり、組織が共同作業を行うさいに従業員に連絡できるようにします。 このテンプレートは、新しいイニシアチブの発表、従業員のオンボーディング、最新の学習と能力開発、組織全体のブロードキャストなど、複数のシナリオで使用します。

このアプリは、指定されたユーザーがメッセージを作成、プレビュー、共同作業、送信するための簡単なインターフェイスを提供します。また、メッセージに同意または対話したユーザーの数に関するカスタム テレメトリなど、カスタムのターゲットを絞った通信機能を構築するための基盤にもなります。

![Company Communicator compose message screen](https://github.com/OfficeDev/microsoft-teams-company-communicator-app/wiki/images/CompanyCommunicatorCompose.png)

### キーとなる機能
* **メッセージの作成:** [チーム] タブを使用して、アクセス許可を持つチーム メンバーが共同作業やメッセージを簡単に作成できます。

* **オーディエンスの選択:** 対象となるオーディエンスを 4 つのオプションから選択します。選択したチームの一般チャネルに送信するか、選択したチームのメンバーに 1：1 のチャットで送信するか、アプリをインストールしているすべてのユーザーに送信するか、M365グループ、配布リスト、またはセキュリティグループに送信します。
* **メッセージのメトリクス:** メッセージ配信レポートをエクスポートします。
* **ローカライゼーション:** 複数のロケールをサポートしています。
## はじめかた

はじめに [ソリューションの概要](https://github.com/OfficeDev/microsoft-teams-company-communicator-app/wiki/Solution-overview) を使用して、アプリの動作と動作について説明します

会社のコミュニケーターを使ってみる準備ができたら、または自分の組織で使用する準備ができたら、以下のいずれかのガイドを選択することができます。

* [展開ガイド powershell](https://github.com/OfficeDev/microsoft-teams-company-communicator-app/wiki/Deployment-guide-powershell).
    * **推奨** Powershell スクリプトを使用してCompany Communicator v5.0 を展開するには、このオプションを使用します。セットアップ全体は、powershell スクリプトによって行われます。
* [展開ガイド](https://github.com/OfficeDev/microsoft-teams-company-communicator-app/wiki/Deployment-guide).
    * クライアント シークレットを使用してCompany Communicator v5.0 を展開するには、このオプションを使用します。
* [展開ガイド certificate](https://github.com/OfficeDev/microsoft-teams-company-communicator-app/wiki/Deployment-guide-certificate).
    * 証明書を使用してCompany Communicator v5.0 を展開するには、このオプションを使用します。

## 旧バージョンからの移行 

すでに旧バージョンのCompany Communicatorがインストールされている場合は、こちらの [v5 移行ガイド](https://github.com/OfficeDev/microsoft-teams-apps-company-communicator/wiki/v5-migration-guide)を使用してください。Company Communicator バージョン 5.0 のようなメジャー バージョンアップには App Service と Azure Functions の同期以上のものが含まれることを意識し、最新のものに移行する前に移行ガイドを確認することを計画してください。

新しいバージョンへの移行 

 * [v5 移行ガイド](https://github.com/OfficeDev/microsoft-teams-apps-company-communicator/wiki/v5-migration-guide)
 * [v4 移行ガイド](https://github.com/OfficeDev/microsoft-teams-apps-company-communicator/wiki/v4-migration-guide)
 * [v3 移行ガイド](https://github.com/OfficeDev/microsoft-teams-apps-company-communicator/wiki/v3-migration-guide)
 * [v2 移行ガイド](https://github.com/OfficeDev/microsoft-teams-apps-company-communicator/wiki/v2-migration-guide)

## フィードバック

意見？ 質問？ アイデア？ [Teams UserVoice](https://microsoftteams.uservoice.com/forums/555103-public)で共有してください！

バグやその他のコードの問題は [こちら](https://github.com/OfficeDev/microsoft-teams-company-communicator-app/issues/new) に報告してください。

## Legal notice

This app template is provided under the [MIT License](https://github.com/OfficeDev/microsoft-teams-company-communicator-app/blob/master/LICENSE) terms.  In addition to these terms, by using this app template you agree to the following:

- You, not Microsoft, will license the use of your app to users or organization. 

- This app template is not intended to substitute your own regulatory due diligence or make you or your app compliant with respect to any applicable regulations, including but not limited to privacy, healthcare, employment, or financial regulations.

- You are responsible for complying with all applicable privacy and security regulations including those related to use, collection and handling of any personal data by your app. This includes complying with all internal privacy and security policies of your organization if your app is developed to be sideloaded internally within your organization. Where applicable, you may be responsible for data related incidents or data subject requests for data collected through your app.

- Any trademarks or registered trademarks of Microsoft in the United States and/or other countries and logos included in this repository are the property of Microsoft, and the license for this project does not grant you rights to use any Microsoft names, logos or trademarks outside of this repository. Microsoft’s general trademark guidelines can be found [here](https://www.microsoft.com/en-us/legal/intellectualproperty/trademarks/usage/general.aspx).

- If the app template enables access to any Microsoft Internet-based services (e.g., Office365), use of those services will be subject to the separately-provided terms of use. In such cases, Microsoft may collect telemetry data related to app template usage and operation. Use and handling of telemetry data will be performed in accordance with such terms of use.

- Use of this template does not guarantee acceptance of your app to the Teams app store. To make this app available in the Teams app store, you will have to comply with the [submission and validation process](https://docs.microsoft.com/en-us/microsoftteams/platform/concepts/deploy-and-publish/appsource/publish), and all associated requirements such as including your own privacy statement and terms of use for your app.

## このプロジェクトに貢献するには

このプロジェクトでは、寄稿や提案を歓迎します。ほとんどの寄稿では、あなたが寄稿物を使用する権利を有し、実際にそれを認めることを宣言する寄稿者ライセンス契約 (Contributor License Agreement : CLA) に同意することが必要です。 詳しくは https://cla.microsoft.com をご覧ください。

プル リクエストを送信すると、CLA ボットは、CLAを提供し、PRを適切にデコレートする必要があるかどうかを自動的に判断します（例 : ラベル、コメントなど）。 ボットが提供する指示に従うだけなのでシンプルです。CLAを使用して、すべてのリポジトリでこれを1回だけ行う必要があります。 

このプロジェクトは [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/) を採用しています。
詳細については、 [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) を参照するか、追加の質問やコメントを [opencode@microsoft.com](mailto:opencode@microsoft.com) までお問い合わせください。
