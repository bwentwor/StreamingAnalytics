---

copyright:
  years: 2015, 2018
lastupdated: "2018-02-14"

---

<!-- Attribute definitions -->
{:new_window: target="_blank"}
{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:screen: .screen}
{:pre: .pre}

# サービス資格情報および VCAP_SERVICES 環境変数
{: #vcap_services}

{{site.data.keyword.streaminganalyticsshort}} サービス資格情報および VCAP_SERVICES 環境変数には、{{site.data.keyword.streaminganalyticsshort}} サービス REST API を使用するために必要な VCAP 情報が含まれています。 VCAP 情報は、各 {{site.data.keyword.streaminganalyticsshort}} サービス REST API の REST URL、サービス・インスタンス ID、バインディング ID、および資格情報を提供します。  
{:shortdesc}


{{site.data.keyword.streaminganalyticsshort}} サービスは、標準的な {{site.data.keyword.Bluemix_short}} サービスの動作および相互作用に従っています。 {{site.data.keyword.streaminganalyticsshort}} サービス・インスタンスをプロビジョンして {{site.data.keyword.Bluemix_notm}} でアプリケーションにバインドすると、このサービス・インスタンスの VCAP 情報は、VCAP_SERVICES 環境変数を使用して Bluemix アプリケーション環境で使用可能になります。 バインド先の {{site.data.keyword.Bluemix_notm}} のアプリケーションを指定せずに {{site.data.keyword.streaminganalyticsshort}} サービス・インスタンスをプロビジョンした場合は、サービス資格情報が自動的に作成されます。 {{site.data.keyword.streaminganalyticsshort}} サービス資格情報には、サービス・ダッシュボードからアクセスできます。


{{site.data.keyword.streaminganalyticsshort}} サービス資格情報および VCAP_SERVICES 環境変数には、以下の例に示されているような情報が含まれています。

<pre><code>
{
  "streaming-analytics": [
    {
      "name": "NYCTrafficStreaming Analytics-t6",
      "label": "streaming-analytics",
      "plan": "Standard",
      "credentials": {
        "status_path": "/jax-rs/streams/status/service_instances/9e86b8e6-f606-4a1a-9800-26b96d2bc923/service_bindings/83c9d52e-3069-46bf-a1e3-655cf95fb627",
        "size_path": "/jax-rs/streams/size/service_instances/0fb17393-90eb-4066-96b6-df1ac9860743/service_bindings/b37b89df-b0d7-464e-b7d9-3db607a26550",
        "start_path": "/jax-rs/streams/start/service_instances/9e86b8e6-f606-4a1a-9800-26b96d2bc923/service_bindings/83c9d52e-3069-46bf-a1e3-655cf95fb627",
        "stop_path": "/jax-rs/streams/stop/service_instances/9e86b8e6-f606-4a1a-9800-26b96d2bc923/service_bindings/83c9d52e-3069-46bf-a1e3-655cf95fb627",
        "resources_path": "/jax-rs/resources/service_instances/9e86b8e6-f606-4a1a-9800-26b96d2bc923/service_bindings/83c9d52e-3069-46bf-a1e3-655cf95fb627",
        "jobs_path": "/jax-rs/jobs/service_instances/9e86b8e6-f606-4a1a-9800-26b96d2bc923/service_bindings/83c9d52e-3069-46bf-a1e3-655cf95fb627",
        "rest_host": "streams-app-service.ng.bluemix.net",
        "rest_port": "443",
        "rest_url": "https://streams-app-service.ng.bluemix.net",
        "userid": "xxx",
        "password": "yyy"
      }
    }
  ]
}	  
</code></pre>

REST API について詳しくは、[{{site.data.keyword.streaminganalyticsshort}} REST API 資料 ![外部リンク・アイコン](../../icons/launch-glyph.svg "外部リンク・アイコン")](https://console.ng.bluemix.net/apidocs/220){:new_window} を参照してください。
