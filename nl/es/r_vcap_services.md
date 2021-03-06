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

# Credenciales de servicio y variable de entorno VCAP_SERVICES
{: #vcap_services}

Las credenciales de servicio de {{site.data.keyword.streaminganalyticsshort}} y la variable de entorno VCAP_SERVICES incluye la información VCAP necesaria para utilizar la API REST de servicio de {{site.data.keyword.streaminganalyticsshort}}. La información VCAP proporciona el URL de REST, el ID de instancia de servicio, el ID de enlace y las credenciales de cada API REST de servicio de {{site.data.keyword.streaminganalyticsshort}}.  
{:shortdesc}


El servicio de {{site.data.keyword.streaminganalyticsshort}} sigue el comportamiento y la interacción típicos del servicio de {{site.data.keyword.Bluemix_short}}. Cuando una instancia de servicio de {{site.data.keyword.streaminganalyticsshort}} se suministra y se enlaza con una aplicación de {{site.data.keyword.Bluemix_notm}}, la instancia del servicio de información VCAP está disponible en el entorno de Bluemix a través de la variable de entorno VCAP_SERVICES. Cuando una instancia de servicio de {{site.data.keyword.streaminganalyticsshort}} se suministra sin especificar ninguna aplicación de {{site.data.keyword.Bluemix_notm}} con la que vincularse, se crean automáticamente las credenciales de servicio. Se puede acceder a las credenciales de servicio de {{site.data.keyword.streaminganalyticsshort}} desde el panel de control del servicio.


Las credenciales de servicio de {{site.data.keyword.streaminganalyticsshort}} y la variable de entorno VCAP_SERVICES incluye información tal como se presenta en el siguiente ejemplo:

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

Para obtener más información sobre la API REST, consulte la [documentación de la API REST de {{site.data.keyword.streaminganalyticsshort}} ![Icono de enlace externo](../../icons/launch-glyph.svg "Icono de enlace externo")](https://console.ng.bluemix.net/apidocs/220){:new_window}.
