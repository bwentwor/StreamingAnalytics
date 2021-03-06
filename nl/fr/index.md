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


# Présentation de Streaming Analytics
{: #gettingstarted}

{{site.data.keyword.streaminganalyticsfull}} tire sa puissance d'{{site.data.keyword.streamsshort}}, une plateforme d'analyse avancée que vous pouvez utiliser pour recevoir, analyser et mettre en corrélation les informations au fur et à mesure qu'elles arrivent depuis différentes sources de données en temps réel. Lorsque vous créez une instance du service {{site.data.keyword.streaminganalyticsshort}}, vous obtenez votre propre instance d'{{site.data.keyword.streamsshort}} s'exécutant dans {{site.data.keyword.Bluemix_short}}, prête à exécuter vos applications {{site.data.keyword.streamsshort}}.
{:shortdesc}

Utilisez directement {{site.data.keyword.streaminganalyticsshort}} en exécutant les [applications de démarrage](/docs/services/StreamingAnalytics/t_starter_app_deploy.html){:new_window}.

Pour commencer à vous servir de {{site.data.keyword.streaminganalyticsshort}}, utilisez l'une des méthodes ci-après pour soumettre le bundle d'applications (fichier .sab) associé à votre application SPL, Java™, Python ou Scala Streams :
* Utilisez le bouton **Soumettre un travail** dans la console {{site.data.keyword.streaminganalyticsshort}}.
* Développez une application dans {{site.data.keyword.Bluemix_notm}} et ajoutez-y l'application {{site.data.keyword.streamsshort}}. Contrôlez-la à l'aide de l'[API REST v1 {{site.data.keyword.streaminganalyticsshort}} ![Icône de lien externe](../../icons/launch-glyph.svg "Icône de lien externe")](https://console.bluemix.net/apidocs/streaming-analytics-v1){:new_window} pour les [plans de service version 1](/docs/services/StreamingAnalytics/service_plans.html) ou de l'[API REST v2 {{site.data.keyword.streaminganalyticsshort}} ![Icône de lien externe](../../icons/launch-glyph.svg "Icône de lien externe")](https://console.bluemix.net/apidocs/streaming-analytics-v2){:new_window} pour les plans de service version 2.

Utilisez {{site.data.keyword.streaminganalyticsshort}} avec d'autres services, dont {{site.data.keyword.cloudant}}. Voir les [tutoriels traitant de l'intégration à d'autres services {{site.data.keyword.Bluemix_short}}](/docs/services/StreamingAnalytics/r_integrating_cloudant_rest.html){:new_window} pour des exemples permettant d'être directement opérationnel.

Si vous voulez aller plus loin avec vos propres applications, vous pouvez obtenir un environnement de développement {{site.data.keyword.streamsshort}} et vous devez faire en sorte que votre application soit prête pour le cloud. Si vous ne disposez pas d'un environnement {{site.data.keyword.streamsshort}}, vous pouvez télécharger le produit [{{site.data.keyword.streamsshort}} Quick Start Edition avec Docker](https://www-01.ibm.com/marketing/iwm/iwm/web/preLogin.do?source=swg-ibmistvi) pour les [plans de service version 2](/docs/services/StreamingAnalytics/service_plans.html) ou, si vous utilisez les [plans de service version 1](/docs/services/StreamingAnalytics/service_plans.html), vous pouvez télécharger l'[image de machine virtuelle {{site.data.keyword.streamsshort}} Quick Start Edition ![Icône de lien externe](../../icons/launch-glyph.svg "Icône de lien externe")](http://ibmstreams.github.io/streamsx.documentation/docs/4.2/qse-intro/){:new_window}.

Si vous ne maîtrisez pas le développement d'applications {{site.data.keyword.streamsshort}}, des ressources vous permettent de vous familiariser. Pour plus d'informations, voir le [Knowledge Center d'{{site.data.keyword.streamsshort}} ![Icône de lien externe](../../icons/launch-glyph.svg "Icône de lien externe")](https://www.ibm.com/support/knowledgecenter/en/SSCRJU_4.2.1/com.ibm.streams.welcome.doc/doc/kc-homepage.html){:new_window}

Si vous possédez déjà une application SPL que vous exécutez sur site, vous devez [préparer votre application pour le cloud.![Icône de lien externe](../../icons/launch-glyph.svg "Icône de lien externe")](https://developer.ibm.com/streamsdev/docs/getting-spl-application-ready-cloud/){:new_window}

**Remarque :** Vous devez compiler vos applications sous Red Hat Enterprise Linux (RHEL) 7.x si vous utilisez les plans de service version 2 ou avec RHEL 6.5 si vous utilisez des plans de service version 1.
