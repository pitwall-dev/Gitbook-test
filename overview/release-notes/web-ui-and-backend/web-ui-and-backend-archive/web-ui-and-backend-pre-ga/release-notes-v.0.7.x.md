---
description: v0.7-alpha family
---

# 🔖 Release Notes v.0.7.x

## v.0.7.30- 02.13.2023

* UI improvement.
* Minor bug fixes.

## v.0.7.28- 02.13.2023

* Studio UI is simplified.&#x20;
* Icons for [1-Click Alert](../../../../../tutorial-get-started./scenario-setup/alert/) scenario and [1-Click Search](../../../../../tutorial-get-started./scenario-setup/instant-lookup/) scenario are added.&#x20;
* Browser Extension [0.2.51](https://ctc-america.box.com/s/fgb9boee5kn4mzmjfe2ka26j5ofq7ymf) released with minor bug fixes.

<figure><img src="../../../../../.gitbook/assets/image (52).png" alt=""><figcaption></figcaption></figure>

## v.0.7.26 & v.0.7.27- 02.08.2023

* Allowing "\_" in the email format in the recipient's setting.
* Browser Extension [0.2.50](https://ctc-america.box.com/s/fgb9boee5kn4mzmjfe2ka26j5ofq7ymf) released with minor bug fixes.
* Bug fixes.

## v.0.7.25 - 02.07.2023

* Studio UI - simplified the studio UI by removing the browser extension lookup column as this is not always necessarily needed.
* SnapView spot-by-spot guidance: Initial demo ROI and explanatory text implemented.

## v.0.7.22 to v.0.7.24 - 02.03.2023

* Design improvement in the annotation feature.
* Browser Extension [0.2.47](https://ctc-america.app.box.com/s/fgb9boee5kn4mzmjfe2ka26j5ofq7ymf).&#x20;
  * Tooltip can be now turned on / off by the option.
  * Status of the snapshot taking is ready.
  * **Screenshots** can be now **downloadable as a zip file**. Better fit for team's reporting (attaching to a document) purpose!
* Minor bug fixes.

## v.0.7.21 - 1.18.2023

* First release of "**annotation**". Now your team can add tips, what needs to be taken a closer look, what differences are compared with the past incidents directly to a screenshot.
* **Camera icon** - Now you can find which lookups you take a screenshot in the studio.
* Timestamp of the email notification is now based on your profile. If you set your timezone to be your local time, you will always receive the email notification with the specified timezone. Otherwise, it'll be UTC.
* Minor wording and bug fixes.

## v.0.7.17 - 1.10.2023

* Cosmetic update to the email format (recipient).
* Lookups are now movable with the drag and drop between groups.

{% embed url="https://drive.google.com/file/d/16P_2VPkrkLorOUxpVJR3SP3oE6r8rXsR/view?usp=share_link" %}

## v.0.7.15 to v.7.16 - 1.9.2023

* Ready to receive PagerDuty alerts. Webhook V2 and V3 supported.&#x20;
* Now, snapview displays "what time the snapshot was taken." As now you can re-take snapshots from the recent release.

{% embed url="https://drive.google.com/file/d/1whypYAylFUYE6AYqJdz2zfj1QYClgxbF/view?usp=share_link" %}

## v.0.7.14 - 1.6.2023

* Browser Extension [0.2.43](https://ctc-america.box.com/s/fgb9boee5kn4mzmjfe2ka26j5ofq7ymf) is released with minor message improvement.
* Added **Email** as a recipient. Now, you can receive the 1-click alert directly to your inbox besides currently supported Slack and MS Teams.

{% embed url="https://drive.google.com/file/d/1HFeYl7cOh_-7c5Zf3_Pjr5ln971Q9AOo/view?usp=share_link" %}

* UI improvements incl. a drag & drop experience in the studio to change the order of lookup.

{% embed url="https://drive.google.com/file/d/1YwAtJPs8uU8z4ZKRSDPJoxTMQyx5d2Av/view?usp=share_link" %}

## v.0.7.13 - 1.4.2023

* Releasing "Snapshot retake", enabling you to retake a snapshot from the snapview.&#x20;
* Bug fixes.

## v.0.7.11 - 1.3.2023

* Browser Extension [0.2.42](https://ctc-america.app.box.com/folder/175310078442?s=fgb9boee5kn4mzmjfe2ka26j5ofq7ym) is released with minor bug fixes.
* UI improvement in the extension view.&#x20;
* Bug fixes.

## v.0.7.9 - 12.22.2022

* UI improvement in the extension view.&#x20;
* Bug fixes.

## v.0.7.8 - 12.16.2022

* **Browser Extension** 0.2.38 is released. Now, you find the results (link / image) in the [Event Log](../../../../../tutorial-get-started./debrief/event-log-insights.md).
* Added **MS Teams as recipient!** Now, you can send the PITWALL intelligent alert to MS Teams as well! See the tutorial here - [3.-recipient.md](../../../../../tutorial-get-started./scenario-setup/alert/3.-recipient.md "mention").
* UI improvement in the snapview and extension.

## v.0.7.7 - 12.14.2022

* UI improvement in the spot-by-spot comparison.

## v.0.7.6 - 12.13.2022

* **Preview feature** released in the studio.&#x20;

{% embed url="https://drive.google.com/file/d/1ui_yMSkemeuYKid4DoqC-n5LlPDdO8Qd/view?usp=share_link" %}
Preview in the studio
{% endembed %}

* **PagerDuty parser** (Alert Parser) for Webhook V1 (experiment).
* For those failed snapshots, you can now **retake** them in the [snapview](../../../../../tutorial-get-started./analyze-an-incident/snapview.md).

## v.0.7.5 - 12.13.2022

* Bug fixes.

## v.0.7.4 - 12.6.2022

* Alert parser for Mackerel ([https://en.mackerel.io/](https://en.mackerel.io/)).
* Bug fixes.

## v.0.7.1 to v.0.7.3 - 12.3-6.2022

* Bug fixes.

## v.0.7.0 - 12.2.2022

* **New webhook endpoint** with the scenario ID enabled - [Tutorial](../../../../../tutorial-get-started./scenario-setup/alert/3.-recipient.md). PITWALL is now ready to support for those alerting tools not allowing users to edit the payload (header / body).&#x20;

<figure><img src="../../../../../.gitbook/assets/image (37).png" alt=""><figcaption><p>Scenario is enabled just with the endpoint URL. No payload edit required.</p></figcaption></figure>

* **Spot-by-spot comparison** powered by computer vision technology is ready in the SnapView / Insights. \
  You can now define what part of snapshot needs to be analyzed by setting a ROI (region of interest). There are 2 types of analysis available.&#x20;
  * Color based analysis\
    analyzing occupancy of colors in the snapshots to detect what differences are.&#x20;
  * Text based analysis\
    extracted texts are now analyzed to detect what differences are.

{% embed url="https://drive.google.com/file/d/1mXZkD8NNzwwxSL4Tze1FEjUaaxRy_rFl/view?usp=sharing" %}
Color and text based analysis.
{% endembed %}

* Bug fixes.
