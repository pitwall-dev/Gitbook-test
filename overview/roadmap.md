# 🏎️ Roadmap

## Feature

* [x] Team account
* [x] Studio
  * [ ] Copying scenario.
  * [x] Drag & drop experience. :tada:
* [x] Asset
* [x] Scenario
  * [x] 1-Click Alert
  * [x] 1-Click Search
  * [x] Periodic Check - Screenshots taken periodically sent to recipients.
* [x] Automation & Insights
  * [x] [**Enabling scenarioID in the webhook endpoint**](release-notes/web-ui-and-backend/web-ui-and-backend-archive/web-ui-and-backend-pre-ga/release-notes-v.0.7.x.md) **-**:tada:
  * [ ] Triage room
    * [ ] Clipper
  * [ ] Onprem Connect
    * [ ] Fixing the PITWALL source IP&#x20;
    * [ ] CloudFlare&#x20;
* [x] Event Log & Insight
  * [x] PIN, TAG and Comment
  * [x] PITWALL AI (Computer Vision / Chart analysis)
    * [x] Similarity (Color based analysis)- :tada:
    * [x] Text analysis - :tada:
    * [ ] Baseline
    * [ ] Anomaly Detection
  * [x] Snapview
    * [x] Snapshot retake :tada:
* [x] Debrief
  * [x] Event Log
    * [x] Alert logging&#x20;
    * [x] Lookup logging of On-demand lookups (browser extension) :tada:&#x20;
  * [x] PIN, TAG and Comment
    * [x] Loopup Level
    * [x] Event Level
    * [x] Search events by PIN, TAG and Comment :tada:
  * [x] Annotation :tada:
    * [x] Surrounding :tada:
    * [x] Comment :tada:
    * [x] Arrow :tada:
  * [ ] Feedback loop to studio.
* [x] Asset
* [x] PITWALL dashboard
  * [x] Asset registration.
  * [x] Date / Time commander
  * [x] Key commander
  * [x] Dynamic resizing

## Security & Scalability

* [x] RBAC
* [ ] MFA
* [ ] SSO / SAML
* [ ] Retention period

## Plugins & Extensions

{% tabs %}
{% tab title="Alert Schema" %}
Enhancement the coverage of the monitoring tools (where alerts are triggered).

Driven by Driven by "**Open Alert**" Open Source Community

* [ ] Launching "Open Alert Project".
* [x] AWS SNS (Simple Notification Service)
* [x] Backlog
* [x] Coralogix
* [ ] Cisco AppDynamics
* [ ] Cisco ThousandEyes
* [x] Datadog
* [ ] Dynatrace
* [ ] Google Monitoring
* [x] Grafana
* [ ] IBM Instana
* [x] Mackerel&#x20;
* [x] New Relic
* [x] PagerDuty
  * [x] V1
  * [x] V2&#x20;
  * [x] V3&#x20;
* [ ] Splunk
* [x] Splunk Oncall (VictorOps)
* [ ] Zabbix
* [x] General Parser
  * [x] OpsRamp
{% endtab %}

{% tab title="Recipient" %}
Enhancing the coverage of where PITWALL sends stitched information to.

* [x] Slack
* [x] MS Teams :tada:
* [x] Email :tada:
* [ ] Webhook
* [ ] Opsgenie
* [ ] Jira
* [ ] Miro
{% endtab %}

{% tab title="Browser Ext." %}
Snapshot

* [x] Single / Multi sites :tada:
* [x] Lookup Logging :tada:

Enhancement of the coverage

* [x] Chrome Extension
* [ ] MS Edge
* [ ] Firefox

Official release to AppStores.

* [ ] Chrome Extension
* [ ] MS Edge
* [ ] Firefox
{% endtab %}

{% tab title="Extensions" %}

{% endtab %}
{% endtabs %}

## Open Source Project

<details>

<summary>Open Alert </summary>

For the better standardization across different tool stacks in each organization from Saas, self-hosted open source & proprietary software or homegrown tools. This project will address current challenges every single tool has different namings of information all organizations would like to simply consume much more easier way.

Targeted project launch - CQ4 / 2022.

</details>

<details>

<summary>WebQL (Open Web Query)</summary>

We are in the web & api economy as we all see sites like travel booking sites where we can specify itinerary e.g. date, airport, name of the hotel etc. is now URL itself is constructed as a query. This is for everyone's good easily shareable, extensible and customizable. This project is initiated to accelerate this momentum to standardize how we get what you would like to see from a single URL.

Targeted project launch - Q1, 2023

</details>

## Compliance

* [ ] SOC2
* [ ] GDPR
* [ ] ISO27001
* [ ] ISO27017
* [ ] HIPPA
