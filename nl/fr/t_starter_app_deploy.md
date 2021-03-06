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

# Tutoriel d'initiation
{: #starterapps_deploy}

Streaming Analytics est un service entièrement géré qui vous évite d'avoir à effectuer des tâches d'installation, d'administration et de gestion chronophages et vous permet de consacrer plus de temps au développement d'applications de diffusion en flux. Au cours de ce tutoriel d'initiation, vous allez envoyer et déployer l'une des applications de démarrage {{site.data.keyword.streaminganalyticsshort}} dans {{site.data.keyword.Bluemix_notm}}.
{:shortdesc}


## Avant de commencer
{: #prereqs}

Pour déployer les applications de démarrage, procédez comme suit :

* Vous enregistrer pour un compte [{{site.data.keyword.Bluemix_notm}} ![Icône de lien externe](../../icons/launch-glyph.svg "Icône de lien externe")](https://console.{DomainName}/registration){:new_window}
* Créer une instance du service {{site.data.keyword.streaminganalyticsshort}} dans votre organisation {{site.data.keyword.Bluemix_notm}}. Vous pouvez créer l'instance directement depuis la [**page {{site.data.keyword.streaminganalyticsshort}}** dans le catalogue des services {{site.data.keyword.Bluemix_notm}}![Icône de lien externe](../../icons/launch-glyph.svg "Icône de lien externe")](https://console.{DomainName}/catalog/services/streaming-analytics/){:new_window}.  
* [Installer l'interface de ligne de commande {{site.data.keyword.Bluemix_notm}} ![Icône de lien externe](../../icons/launch-glyph.svg "Icône de lien externe")](https://console.{DomainName}/docs/cli/reference/bluemix_cli/get_started.html#getting-started).



## Etape 1. Création et connexion de l'application à votre service
{: #create_connect}

1. Créez une application dans {{site.data.keyword.Bluemix_notm}} :

    a. Dans le menu **{{site.data.keyword.Bluemix_notm}}**, sélectionnez **Applis Cloud Foundry** et cliquez sur **Créer une ressource**.

    b. Sélectionnez l'exécution {{site.data.keyword.sdk4node}} pour les applications de démarrage Event Detection ou Event Detection v2.

    Mémorisez le nom que vous attribuez à votre application ; vous en aurez besoin ultérieurement.
1. Connectez l'instance de service {{site.data.keyword.streaminganalyticsshort}} à votre application et reconstituez l'application en préproduction.

## Etape 2. Configuration de l'application de démarrage
{: #setup_app}

1. Si vous utilisez les [plans de service version 1](/docs/services/StreamingAnalytics/service_plans.html), téléchargez l'application de démarrage [Event Detection ![Icône de lien externe](../../icons/launch-glyph.svg "Icône de lien externe")](https://streams-github-samples.mybluemix.net/?get=QuickStart/EventDetection). Téléchargez l'application de démarrage[Event Detection v2 ![Icône de lien externe](../../icons/launch-glyph.svg "Icône de lien externe")](https://streams-github-samples.mybluemix.net/?get=QuickStart%2FBeta201801%2FEventDetectionV2) pour [les plans de service version 2](/docs/services/StreamingAnalytics/service_plans.html).

1. Renommez le répertoire avec le nom que vous avez attribué à votre application dans {{site.data.keyword.Bluemix_notm}}.

## Etape 3. Déploiement de l'application de démarrage
{: #deploy_app}

1. Accédez au répertoire de l'application de démarrage :
  <pre><code>cd mon_app</code></pre>
  {:pre}

1. Connectez-vous à {{site.data.keyword.Bluemix_notm}} et définissez votre organisation cible quand vous y êtes invité :
  <pre><code>bx login</code></pre>
  {:pre}

1. Envoyez votre application par commande push dans {{site.data.keyword.Bluemix_notm}} :
  <pre><code>bx app push myapp</code></pre>
  {:pre}

1. Accédez à la page de présentation de votre application, accessible depuis le tableau de bord {{site.data.keyword.Bluemix_notm}}, afin de vérifier que votre application a bien démarré.
1. Lancez votre application pour l'afficher dans votre navigateur. Vous trouverez l'adresse URL (ou "route") de votre application dans la page de
présentation de l'application.

## Etapes suivantes
{: #next_steps}

Maintenant que votre application est en cours d'exécution, vous pouvez la surveiller depuis la console {{site.data.keyword.streaminganalyticsshort}}. Accédez au tableau de bord des services, sélectionnez votre service {{site.data.keyword.streaminganalyticsshort}}, puis cliquez sur **Lancer**.
