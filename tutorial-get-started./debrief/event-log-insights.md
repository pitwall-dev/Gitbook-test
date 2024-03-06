# Event log / Insights

## Overview

Event log (Snapview) and Insights help you to compare and analyze an incident with the followings. PITWALL gives devops teams to correlate data among different tools such as logs, metrics, tracing... However, these correlations are for AT the time of an alert or an incident, but the correlated data at the time of incident alone sometimes won’t give an instant analysis of where the problem is. SnapView gives those devops team to help identify where the issue is by providing three different angles per destination tools. Comparing with

1. Look back (time in the past)
2. Past events
3. Baseline

<figure><img src="../../.gitbook/assets/image (63).png" alt=""><figcaption><p>SnapView</p></figcaption></figure>

### Look back <a href="#other-times" id="other-times"></a>

This allows users to view the same destination with different time range based on what you need.\
For example, the same dashboard for the same time but sometime in the past. There are preset look back options or you can compare any particular time on-demand basis.

* 1 hour ago
* 1 day before
* 1 week before
* 1 month before

### Past events <a href="#past-evemts" id="past-evemts"></a>

Users can view the same destination at the time of past events (alerts / incidents) based on what you need. For example if your event is #125, you will have an access to the same dashboard of past event(s).

* \#125 - event you need to troubleshoot.
* \#120 - event from sometime in the past
* \#081 - event from sometime in the past.

### Baseline <a href="#baselines" id="baselines"></a>

This will require a set of ML and data (captured snapshots), but this will give what’s usual to the devops team at the time of troubleshooting. The example is from AWS synthetic analysis, which is constantly accessing a website to record its response times and set a baseline. PITWALL does provide this for actual snapshots you defined (dashboard images).

{% hint style="info" %}
Baseline is in the roadmap and scheduled to be released in beta towards the beginning of 2023.&#x20;
{% endhint %}

