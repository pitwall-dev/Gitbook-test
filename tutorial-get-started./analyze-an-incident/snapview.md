---
description: Basic comparison.
---

# SnapView

## Overview

Snapview help you to compare and analyze an incident with the followings to help identify where the issue is by providing three different angles per destination tools. Comparing with :&#x20;

1. Look back (time in the past)
2. Past events
3. Baseline

<figure><img src="../../.gitbook/assets/image (50).png" alt=""><figcaption></figcaption></figure>

### Look back <a href="#other-times" id="other-times"></a>

This allows users to check the same view with different time range on-demand basis.\
For example, the same dashboard for the same time but sometime in the past. There are preset look back options or select any particular date / time.

### Past events <a href="#past-evemts" id="past-evemts"></a>

Users can also check the same view at the time of past events (alerts / incidents). \
For example if your event is #125, you will have an access to the same view of past event(s).

* \#125 - event you need to troubleshoot.
* \#120 - past event you would like to review.
* \#081 - past event you would like to review.

### Baseline <a href="#baselines" id="baselines"></a>

This will require a set of ML and data (captured snapshots), but this will give what’s usual to the devops team at the time of troubleshooting. The example is from AWS synthetic analysis, which is constantly accessing a website to record its response times and set a baseline. PITWALL does provide this for actual snapshots you defined (dashboard images).

{% hint style="info" %}
Baseline is in the roadmap and scheduled to be released in 2024.&#x20;
{% endhint %}
