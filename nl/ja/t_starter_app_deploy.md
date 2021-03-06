---

copyright:
  years: 2015, 2018
lastupdated: "2018-07-24"

---

<!-- Attribute definitions -->
{:new_window: target="_blank"}
{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:screen: .screen}
{:pre: .pre}

# 入門チュートリアル
{: #starterapps_deploy}

Streaming Analytics は完全マネージド・サービスであり、時間のかかるインストールや管理の作業が不要で、ストリーミング・アプリケーション開発に時間をより多くかけられるようにします。 この入門チュートリアルでは、{{site.data.keyword.streaminganalyticsshort}} スターター・アプリケーションの 1 つを {{site.data.keyword.Bluemix_notm}} にプッシュしてデプロイします。
{:shortdesc}


## 始めに
{: #prereqs}

スターター・アプリをデプロイするには、以下のステップを実行する必要があります。

* [{{site.data.keyword.Bluemix_notm}} アカウント ![外部リンク・アイコン](../../icons/launch-glyph.svg "外部リンク・アイコン")](https://console.{DomainName}/registration){:new_window} に登録します。
* {{site.data.keyword.Bluemix_notm}} 組織に {{site.data.keyword.streaminganalyticsshort}} サービスのインスタンスを作成します。 このインスタンスは、{{site.data.keyword.Bluemix_notm}} サービス・カタログ ![外部リンク・アイコン](../../icons/launch-glyph.svg "外部リンク・アイコン"){:new_window} 内の [**{{site.data.keyword.streaminganalyticsshort}}** ページから直接作成できます。  
* [{{site.data.keyword.Bluemix_notm}} CLI のインストール ![外部リンク・アイコン](../../icons/launch-glyph.svg "外部リンク・アイコン")](https://console.{DomainName}/docs/cli/reference/bluemix_cli/get_started.html#getting-started)(https://console.{DomainName}/catalog/services/streaming-analytics/)]。



## ステップ 1. アプリの作成とサービスへの接続
{: #create_connect}

1. 以下のようにして、{{site.data.keyword.Bluemix_notm}} でアプリケーションを作成します。

    a. **{{site.data.keyword.Bluemix_notm}}** メニューから**「Cloud Foundry アプリ」**を選択し、**「リソースの作成」**をクリックします。

    b. Event Detection または Event Detection v2 スターター・アプリケーション用の {{site.data.keyword.sdk4node}} ランタイムを選択します。

    アプリケーションに指定した名前を覚えておいてください。後で必要になります。
1. {{site.data.keyword.streaminganalyticsshort}} サービス・インスタンスをアプリケーションに接続し、アプリケーションを再ステージします。

## ステップ 2. スターター・アプリケーションのセットアップ
{: #setup_app}

1. [v1 サービス・プラン](/docs/services/StreamingAnalytics/service_plans.html)を使用している場合は [Event Detection ![外部リンク・アイコン](../../icons/launch-glyph.svg "外部リンク・アイコン")](https://streams-github-samples.mybluemix.net/?get=QuickStart/EventDetection) スターター・アプリケーションをダウンロードします。 [v2 サービス・プラン](/docs/services/StreamingAnalytics/service_plans.html)の場合は、[Event Detection v2 ![外部リンク・アイコン](../../icons/launch-glyph.svg "外部リンク・アイコン")](https://streams-github-samples.mybluemix.net/?get=QuickStart%2FBeta201801%2FEventDetectionV2) スターター・アプリケーションをダウンロードします。

1. {{site.data.keyword.Bluemix_notm}} 内のアプリケーションに指定した名前に一致するように、ディレクトリーの名前を変更します。

## ステップ 3. スターター・アプリケーションのデプロイ
{: #deploy_app}

1. 以下を実行して、スターター・アプリケーション・ディレクトリーに移動します。
  <pre><code>cd myapp</code></pre>
  {:pre}

1. {{site.data.keyword.Bluemix_notm}} にログインし、プロンプトが出されたら、ターゲット組織を設定します。
  <pre><code>bx login</code></pre>
  {:pre}

1. 以下を実行して、アプリケーションを {{site.data.keyword.Bluemix_notm}} にプッシュします。
  <pre><code>bx app push myapp</code></pre>
  {:pre}

1. アプリケーション概要ページ ({{site.data.keyword.Bluemix_notm}} ダッシュボードからアクセス可能) に移動し、アプリケーシ
ョンが正常に開始されたことを確認します。
1. アプリケーションを起動して、ブラウザーに表示します。 アプリケーション概要ページに、アプリケーションの URL (または「ルート」) が表示されます。

## 次のステップ
{: #next_steps}

これでアプリケーションが稼働中となったので、{{site.data.keyword.streaminganalyticsshort}} コンソールからアプリケーションをモニターすることができます。 サービス・ダッシュボードに移動し、{{site.data.keyword.streaminganalyticsshort}} サービスを選択し、**「起動」**をクリックします。
