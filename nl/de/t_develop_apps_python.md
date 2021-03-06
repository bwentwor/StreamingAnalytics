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

# Python-Anwendungen in Streaming Analytics entwickeln
{: #t_develop_apps_python}

Sie können nun Python-Anwendungen in {{site.data.keyword.DSX_full}} oder in der lokalen Python-Entwicklungsumgebung entwickeln und diese Anwendungen in {{site.data.keyword.streaminganalyticsshort}} bereitstellen.
{:shortdesc}

Entwickeln Sie Python-Anwendungen und stellen Sie sie in {{site.data.keyword.Bluemix_short}} bereit, indem Sie den {{site.data.keyword.streaminganalyticsshort}}-Service verwenden. Verwenden Sie dazu eine der folgenden Methoden:


## Streams-Python-Anwendungen in Watson Studio entwickeln
{: #t_develop_python_dsx}

Wenn Sie nicht über eine Python-Entwicklungsumgebung verfügen, besteht der einfachste Einstieg darin, dass Sie die {{site.data.keyword.streamsshort}}-Notebooks in {{site.data.keyword.DSX_short}} verwenden und Python-Beispielanwendungen erstellen. Mit diesen Notebooks stehen die Schritte und Codebeispiele zur Verfügung, mit denen einfache Python-Anwendungen für den {{site.data.keyword.streaminganalyticsshort}}-Service innerhalb der {{site.data.keyword.DSX_short}}-Python-Umgebung erstellt und bereitgestellt werden können.

* [Hello World! ![Symbol für externen Link](../../icons/launch-glyph.svg "Symbol für externen Link")](https://apsportal.ibm.com/exchange/public/entry/view/9fc33ce7301f10e21a9f92039ca9c6e8): Erstellen Sie als ersten Schritt eine einfache 'Hello World!'- Anwendung und stellen Sie dann die Anwendung in einer Instanz des {{site.data.keyword.streaminganalyticsshort}}-Service bereit.

* [Demo über das Gesundheitswesen ![Symbol für externen Link](../../icons/launch-glyph.svg "Symbol für externen Link")](https://apsportal.ibm.com/exchange/public/entry/view/9fc33ce7301f10e21a9f92039cad29a6): Erstellen Sie eine Anwendung, die Streaming-Daten aus einem Feed aufnimmt und analysiert und dann die Daten im Notebook visualisiert. Übergeben Sie diese Anwendung anschließend an die {{site.data.keyword.streaminganalyticsshort}}-Serviceinstanz.

* [Demo zum neuronalen Netz ![Symbol für externen Link](../../icons/launch-glyph.svg "Symbol für externen Link")](https://apsportal.ibm.com/exchange/public/entry/view/9fc33ce7301f10e21a9f92039ca60bb7): Erstellen Sie ein Beispieldataset, erstellen Sie ein Datenmodell, verwenden Sie dieses Modell in einer Streaming-Anwendung, visualisieren Sie die Streaming-Daten und übergeben Sie die Streaming-Anwendung an den Service.

## Anwendungen in der lokalen Python-Umgebung entwickeln
 {: #t_develop_python_api}

Mit der [{{site.data.keyword.streamsshort}}-Python-Anwendungs-API ![Symbol für externen Link](../../icons/launch-glyph.svg "Symbol für externen Link")](http://ibmstreams.github.io/streamsx.documentation/docs/python/python-appapi-devguide/#50-api-features), die im 'streamsx'-Paket enthalten ist, können Sie Streamverarbeitungsanwendungen mithilfe von aufrufbaren Python-Klassen oder -Funktionen erstellen. Dann verwenden Sie die Python-Anwendungs-API, um die Anwendung zu definieren und an den Service zu übergeben.

Zuerst führen Sie die beschriebenen Schritte im Lernprogramm [Entwicklung für den {{site.data.keyword.streaminganalyticsshort}}-Service ![Symbol für externen Link](../../icons/launch-glyph.svg "Symbol für externen Link")](http://ibmstreams.github.io/streamsx.documentation/docs/python/1.6/python-appapi-devguide-2a/index.html) aus. In diesem Lernprogramm erstellen Sie eine Beispielanwendung in der lokalen Python-Umgebung und stellen diese im {{site.data.keyword.streaminganalyticsshort}}-Service bereit.

Einen detaillierteren Einblick in die {{site.data.keyword.streamsshort}}-Python-Anwendungs-API erhalten Sie, wenn Sie [diesen Onlinekurs ![Symbol für externen Link](../../icons/launch-glyph.svg "Symbol für externen Link")](https://developer.ibm.com/courses/all/streaming-analytics-basics-python-developers/){:new_window} ausführen; hier können Sie sich mit den Grundlagen von {{site.data.keyword.streaminganalyticsshort}} für Python-Entwickler vertraut machen.
