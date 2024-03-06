# 1. Trigger

## Configure the Trigger

The following tutorial enables a scenario by using an example here. \
An alert is triggered by a monitoring tool (Coralogix) and based on the scenario created by PITWALL, the lookups are stitched together and you will receive it in Slack.\
&#x20;

<figure><img src="../../../../.gitbook/assets/image (34).png" alt=""><figcaption></figcaption></figure>

After naming your scenario, you will define the source. There are types of scenarios. Pick the "**Incoming alert**" to build a dynamic scenario by a triggered alert. You will define what monitoring tool you are sending an alert from.&#x20;

{% tabs %}
{% tab title="Alert" %}
Team starts troubleshooting and analysis process from a triggered alert. This gives a team to correlate and stitch all the data you need to see across different tools.&#x20;
{% endtab %}

{% tab title="Instant lookup" %}
This will give a simple but robust “look up” capability across what you would like to see. This is for more specific use cases such as [for-security-operation.md](../../../../use-cases/for-security-operation.md "mention")and [for-researchers.md](../../../../use-cases/for-researchers.md "mention"). Please refer to each use cases as well as another tutorial about configuring the "Text in browser" scenario here.
{% endtab %}

{% tab title="Scheduled" %}
Scheduled monitoring allows you to periodically generate links and capture screenshots.
{% endtab %}
{% endtabs %}

<figure><img src="../../../../.gitbook/assets/image (6).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
We will make this "alert parser" to be open sourced as a part of [roadmap](../../../../overview/roadmap.md) to incorporate variety of tools to be handled with PITWALL.
{% endhint %}
