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


# Identity and Access Management authentication

Access to {{site.data.keyword.streaminganalyticsshort}} service instances for users in your account is controlled by {{site.data.keyword.Bluemix_notm}} Identity and Access Management (IAM). To manage your {{site.data.keyword.streaminganalyticsshort}} service, you must use an authentication token.

## Retrieving IAM access tokens

### Prerequisites

a. You must have a valid IBMid.

b. Download and install the [{{site.data.keyword.Bluemix_notm}} CLI](https://console.bluemix.net/docs/cli/reference/bluemix_cli/get_started.html#getting-started).

### Step 1. Log into the {{site.data.keyword.Bluemix_notm}} CLI.

```
bx api https://api.ng.bluemix.net
bx login
<enter your credentials>

<If you are part of multiple {{site.data.keyword.Bluemix_notm}} accounts, you'll be asked to choose an account for the current session. Also, you'll need to choose an organization and space in {{site.data.keyword.Bluemix_notm}}.>
```

### Step 2. Fetch the IAM access token.

```
bx iam oauth-tokens
```

Two tokens are produced: one named `IAM token` and the other one named `UAA token`. Use `IAM token` for making REST API calls.
