---

copyright:
  years:  2017
lastupdated: "2018-07-24"

---

{:new_window: target="_blank"}
{:shortdesc: .shortdesc}
{:screen: .screen}
{:pre: .pre}
{:table: .aria-labeledby="caption"}
{:codeblock: .codeblock}
{:tip: .tip}
{:download: .download}


# Autenticação de Gerenciamento de Identidade e Acesso

O acesso às instâncias de serviço do {{site.data.keyword.streaminganalyticsshort}} para usuários em
sua conta é controlado pelo {{site.data.keyword.Bluemix_notm}} Identity and Access Management (IAM). Para gerenciar o serviço do {{site.data.keyword.streaminganalyticsshort}}, deve-se usar um token de autenticação.

## Recuperar tokens de acesso IAM

### Pré-requisitos

a. Você deve ter um IBMid válido.

b. Faça download e instale o [{{site.data.keyword.Bluemix_notm}} CLI](https://console.bluemix.net/docs/cli/reference/bluemix_cli/get_started.html#getting-started).

### Etapa 1. Efetue login na CLI do {{site.data.keyword.Bluemix_notm}}.

```
bx api https://api.ng.bluemix.net bx login <insira suas credenciais>

<Se você fizer parte de múltiplas contas do {{site.data.keyword.Bluemix_notm}}, deverá escolher uma conta para a sessão atual. Além disso, será necessário escolher uma organização e um espaço em
{{site.data.keyword.Bluemix_notm}}.>
```

### Etapa 2. Busque o token de acesso do IAM.

```
bx iam oauth-tokens
```

Dois tokens são produzidos: um chamado `IAM token` e o outro chamado `UAA token`. Use
`IAM token` para fazer chamadas API de REST.
