# 🖥️ For Security Operation

## Overview

Today's enterprise IT operation, there are always new threats everyday. When a security product sends an alert with variety types of information listed below, the security team needs to research if they are suspicious, how risky they would be and collect evidences as a record.

## Categories

* IP reputation
* Site reputation (Malware)
* CVE
* File check (hash)

## Examples

There are widely used well known sites where you check these categories. Here is the list of examples and how these lookups can be configured in the PITWALL studio. For more details, please go to [#create-a-new-ondemand-lookup](../tutorial-get-started./scenario-setup/instant-lookup/2.-ondemand-lookup.md#create-a-new-ondemand-lookup "mention")

&#x20; &#x20;

{% tabs %}
{% tab title="IP Reputation" %}
<table><thead><tr><th width="152">Site</th><th width="358">PITWALL URL (Parameterized)</th><th>Key sample</th></tr></thead><tbody><tr><td>AbuseIPDB</td><td><a href="https://www.abuseipdb.com/check/202.14.122.217">https://www.abuseipdb.com/check/{$key}</a></td><td>202.14.122.217<br>(This IP is real. Be careful.)</td></tr><tr><td>VirusTOTAL</td><td><a href="https://www.virustotal.com/gui/ip-address/210.209.125.142">https://www.virustotal.com/gui/ip-address/{$key}</a></td><td>210.209.125.142<br>(This IP is real. Be careful.)</td></tr></tbody></table>


{% endtab %}

{% tab title="Site Reputation (Malware)" %}
<table><thead><tr><th width="196">Site</th><th>PITWALL URL (Parameterized)</th></tr></thead><tbody><tr><td>URLhaus</td><td><a href="https://urlhaus.abuse.ch/browse.php?search=222.139.79.18">https://urlhaus.abuse.ch/browse.php?search={$key</a>}</td></tr><tr><td>IBM X-Force Exchange</td><td><a href="https://exchange.xforce.ibmcloud.com/url/222.139.79.18">https://exchange.xforce.ibmcloud.com/url/{$key}</a></td></tr></tbody></table>
{% endtab %}
{% endtabs %}
