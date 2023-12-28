---
demo:
  title: 'デモ 01: ストレージ アカウントを作成して構成する'
  module: Guided Project - Azure Files and Azure Blobs
---
## デモ – ストレージ アカウントを作成して構成する 

このデモでは、ストレージ アカウントについて説明します。

1. [補助スライド] このデモを開始する前に、ストレージの編成方法と考慮すべき要素について説明する必要があります。 

1. **Azure portal** にアクセスします。

1. 検索ボックスに、「**ストレージ アカウント**」と入力します。 入力を始めると、入力内容に基づいて、一覧がフィルター処理されます。

1. **[ストレージ アカウント]** を選択します。

1. **［作成］** を選択します

1. Azure portal が使いやすいウィザード インターフェイスを提供する方法について説明します。 赤いアスタリスク (*) が付いた項目は必須であることを学生に注意します。

1. **[サブスクリプション]** を選択します。

1. **[リソース グループ]** を選択します。

1. ストレージ アカウントの名前を入力します。 ストレージ アカウントの名前付けの制限事項について説明します。

1. ストレージ アカウントのリージョンを選択します。 ラボで学生が使用するリージョンを確認します。 [Azure 地域](https://azure.microsoft.com/explore/global-infrastructure/geographies/)に関する詳細を確認します。

1. [補助スライド] **標準**パフォーマンスを選択します。 [ストレージ アカウントの種類](https://learn.microsoft.com/azure/storage/common/storage-account-overview)に関する詳細を確認します。

1. [補助スライド] **ローカル冗長**ストレージとして **[冗長性]** を選択します。 [Azure Storage の冗長性](https://docs.microsoft.com/azure/storage/common/storage-redundancy)に関する詳細を確認します。

1. **[詳細設定]** タブに移動します。**[セキュリティ]** セクションで、これらの設定を強調表示します。 ここでは、学生が最初のラボを開始できるよう、いくつかのことだけを説明していることに注意してください。 

    - **REST API 操作の安全な転送を必須にする。** 既定では、ストレージ アカウントで、セキュリティで保護された接続からの要求のみを受け入れる必要があります。 [安全な転送](https://learn.microsoft.com/azure/storage/common/storage-require-secure-transfer)に関する詳細を確認します。

    - **ストレージ アカウント キーへのアクセスを有効にする**。 この設定でストレージ アカウントへのアクセスを無効にする方法について説明します。 たとえば、IT 部門のストレージ アカウントへのアクセスを無効にすることができます。 キーを保護することの重要性について説明します。 [ストレージ アカウントのアクセス キーの管理](https://learn.microsoft.com/azure/storage/common/storage-account-keys-manage?tabs=azure-portal)に関する詳細を確認します。

    - **TLS の最小バージョン**。 トランスポート層サービスは、ネットワーク経由の通信をセキュリティで保護するためのものであることを説明します。 TLS は SSL の改善されたバージョンです。 開発者から、使用できるバージョンを尋ねられる場合があります。 [トランスポート層サービス](https://learn.microsoft.com/azure/storage/common/transport-layer-security-configure-minimum-version)に関する詳細を確認します。

1. 学生がラボを進めるとき、他のタブがカバーされることを説明します。

1. **[確認]** を選択し、検証エラーがないことを確認します。 考えられる検証エラーについて説明します。 

1. **[作成]** を選択し、ストレージ アカウントがデプロイされるまで待ちます。 通知メッセージを指摘します。

1. **リソースに移動する**方法を示します。 リソースにアクセスするその他の方法について説明します。

>**注**: 学生は LAB_01 を完了できるようになりました。