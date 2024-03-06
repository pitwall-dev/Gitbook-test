# ✨ Features

## Studio

Studio adding what you need to see across different tools in alerts, enabling ad-hoc research depending on the context of the incident and standardizing the process in your organization.

* Construct what to look up.&#x20;
* Enabling Snapshot for Instant triage+analysis.&#x20;
* No change to current tools.

<figure><img src="https://lh7-us.googleusercontent.com/7y1ps6PAy_YUwi_FifO_BggULmAUTTSO1yksSdRvfF8ODiDQrzEjwA8CWKzqjqCo_IksRcaMn6A736d8nLdGo9SMIc1KV9QZzdHYDqgx9ShSOtUNSQL2_WMCjbrtV-yERDfLW8lIVE-zzs8dum95sLFInw=s2048" alt=""><figcaption></figcaption></figure>

## Alert Manager

PITWALL stitches what you would like to review across different tools as clickable links when you receive an alert from your monitoring tool such as Coralogix, Splunk, New Relic ....

This will provide an instant access to obtain what you need instead of manually opening a browser, switching one tool to another, adjusting the time range of the dashboard back to the time of an alert.  The process is defined in the Studio without making any changes to your current tools.

&#x20;

<figure><img src="../.gitbook/assets/image (46).png" alt=""><figcaption><p>Alert in Slack</p></figcaption></figure>

## Browser Extension

Browser extension gives you an ability to run a research using a text in the browser as a key. This lightweight lookup tool saves your time of manual look up(s) of variety of data. For example :&#x20;

* DevOps
  * Tracing data for a specific application performance.&#x20;
* Security
  * IP reputation
  * Malware site check
  * Phishing site check
  * File hash check
* General
  * Google search

<figure><img src="../.gitbook/assets/image (53).png" alt=""><figcaption><p>Browser Extension</p></figcaption></figure>

{% embed url="https://drive.google.com/file/d/1BEEYkK2UUlHN-OfNpkXtMpKki2NeA0Lg/view?usp=sharing" %}

## Event log / Insights

Event log (Snapview) and Insights help you to compare and analyze an incident with the followings. PITWALL gives devops teams to correlate data among different tools such as logs, metrics, tracing... However, these correlations are for AT the time of an alert or an incident, but the correlated data at the time of incident alone sometimes won’t give an instant analysis of where the problem is. SnapView gives those devops team to help identify where the issue is by providing three different angles per destination tools. Comparing with

1. Look back (time in the past)
2. Past events
3. Baseline

<figure><img src="../.gitbook/assets/image (63).png" alt=""><figcaption><p>SnapView</p></figcaption></figure>

### Look back <a href="#other-times" id="other-times"></a>

This allows users to view the same destination with different time range based on what you need.\
For example, the same dashboard for the same time but sometime in the past. There are preset look back options or you can compare any particular time on-demand basis.

### Past events <a href="#past-evemts" id="past-evemts"></a>

Users can view the same destination at the time of past events (alerts / incidents) based on what you need. For example if your event is #125, you will have an access to past event(s).

* \#125 - event you need to analyze.
* \#120 - event from sometime in the past
* \#081 - event from sometime in the past.

### Baseline <a href="#baselines" id="baselines"></a>

This will require a set of ML and data (captured snapshots), but this will give what’s usual to the devops team at the time of troubleshooting. The example is from AWS synthetic analysis, which is constantly accessing a website to record its response times and set a baseline. PITWALL does provide this for actual snapshots you defined (dashboard images).

{% hint style="info" %}
Baseline is in the roadmap and scheduled to be released in 2024
{% endhint %}
