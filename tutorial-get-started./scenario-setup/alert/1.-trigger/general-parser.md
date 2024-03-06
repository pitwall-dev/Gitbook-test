# ℹ️ General Parser

### Overview

General Parser allows you to receive an alert based on a custom webhook. This is good for your inhouse monitoring tool, a tool which doesn't have a default payload for the alert.

### Set up

1.  Select "General Parser" as a trigger.\


    <figure><img src="../../../../.gitbook/assets/image (2).png" alt=""><figcaption></figcaption></figure>
2.  Click "Manage Alert"\




    <figure><img src="../../../../.gitbook/assets/image (3).png" alt=""><figcaption></figcaption></figure>



    <figure><img src="../../../../.gitbook/assets/image (81).png" alt=""><figcaption></figcaption></figure>
3.  Review pre-requisition and create your custom payload.\
    &#x20;

    | KEY         | VALUE  | NOTE                                                                |
    | ----------- | ------ | ------------------------------------------------------------------- |
    | timestamp   | string | <p>Unix time in msec.</p><p>(ex.) “1695256040174”</p>               |
    | alertUrl    | string | URL format                                                          |
    | alertId     | string |                                                                     |
    | description | string |                                                                     |
    | severity    | string | <p>Available options<br>DEBUG | INFO | WARN | ERROR | CRITICAL </p> |
    | title       | string |                                                                     |

#### Sample payload

"timestamp", "alertId", "title", "severity", "alertURL" are required keys.&#x20;

```
{
  “timestamp”: “1695256040174”,
  “alertId”: “1234567890abcd”,
  “title”: “Dummy Alert”,
  “severity”: “INFO”,
  “alertUrl”: “https://xxx.com/alert?id=0123456789abcd”,
  “hostname”: “abc.xxx.com”,
  “ip”: “10.10.10.10”,
  “customFields”: [
    {
      “key”: “incidentTitle”,
      “value”: “dummy incident”
    }
  ]
}

```

