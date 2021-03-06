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


# Streaming Analytics overview
{: #gettingstarted}

{{site.data.keyword.streaminganalyticsfull}} is powered by {{site.data.keyword.streamsshort}}, an advanced analytic platform that you can use to ingest, analyze, and correlate information as it arrives from different types of data sources in real time. When you create an instance of the {{site.data.keyword.streaminganalyticsshort}} service, you get your own instance of {{site.data.keyword.streamsshort}} running in {{site.data.keyword.Bluemix_short}}, ready to run your {{site.data.keyword.streamsshort}} applications.
{:shortdesc}

Get started with {{site.data.keyword.streaminganalyticsshort}} right away by running the [starter applications](/docs/services/StreamingAnalytics/t_starter_app_deploy.html){:new_window}.

To get started with {{site.data.keyword.streaminganalyticsshort}}, use one of the following methods to submit the application bundle (.sab file) that is associated with your SPL, Java™, Python or Scala Streams application:
* Use the **Submit Job** button in the {{site.data.keyword.streaminganalyticsshort}} console.
* Develop an application in {{site.data.keyword.Bluemix_notm}} and add the {{site.data.keyword.streamsshort}} application to it. Control it by using the [{{site.data.keyword.streaminganalyticsshort}} v1 REST API ![External link icon](../../icons/launch-glyph.svg "External link icon")](https://console.bluemix.net/apidocs/streaming-analytics-v1){:new_window} for [v1 service plans](/docs/services/StreamingAnalytics/service_plans.html) or the [{{site.data.keyword.streaminganalyticsshort}} v2 REST API ![External link icon](../../icons/launch-glyph.svg "External link icon")](https://console.bluemix.net/apidocs/streaming-analytics-v2){:new_window} for v2 service plans.

Use {{site.data.keyword.streaminganalyticsshort}} with other services, including {{site.data.keyword.cloudant}}. See the [Tutorials to integrate with other {{site.data.keyword.Bluemix_short}} services](/docs/services/StreamingAnalytics/r_integrating_cloudant_rest.html){:new_window} for examples to get you up and running.

If you want to go further with your own applications, you can get a {{site.data.keyword.streamsshort}} development environment and you must get your application cloud-ready. If you don’t have an {{site.data.keyword.streamsshort}} environment, you can download the [{{site.data.keyword.streamsshort}} Quick Start Edition with Docker](https://www-01.ibm.com/marketing/iwm/iwm/web/preLogin.do?source=swg-ibmistvi) for [v2 service plans](/docs/services/StreamingAnalytics/service_plans.html) or if you are using [v1 service plans](/docs/services/StreamingAnalytics/service_plans.html), you can download the [{{site.data.keyword.streamsshort}} Quick Start Edition VM image ![External link icon](../../icons/launch-glyph.svg "External link icon")](http://ibmstreams.github.io/streamsx.documentation/docs/4.2/qse-intro/){:new_window}.

If you are not familiar with {{site.data.keyword.streamsshort}} application development, there are resources to help you learn. For more information, see [{{site.data.keyword.streamsshort}} Knowledge Center ![External link icon](../../icons/launch-glyph.svg "External link icon")](https://www.ibm.com/support/knowledgecenter/en/SSCRJU_4.2.1/com.ibm.streams.welcome.doc/doc/kc-homepage.html){:new_window}

If you already have an SPL application that you run on premise, you must [get your application ready for the cloud.![External link icon](../../icons/launch-glyph.svg "External link icon")](https://developer.ibm.com/streamsdev/docs/getting-spl-application-ready-cloud/){:new_window}

**Note:** You must compile your applications in Red Hat Enterprise Linux (RHEL) 7.x if you are using the v2 service plans or with RHEL 6.5 if you're using v1 service plans.
