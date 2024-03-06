# 🔩 PITWALL Extensions

## What is Extension?

Extension is a set of components that can be used to implement additional capability on top of what PITWALL is equipped by default such as :&#x20;

1. Adding icons of your tools to enrich the studio UI.
2. Adding time format(s) to detect timestamps from the URL you would like to parameterize in the studio.

### 1. Adding icons of your tools to enrich the studio UI.

PITWALL has a wide variety of tools / sites available contributed by community members. However, there are always new tools, sites and your own assets keep coming up, so when you add a new destination in the studio, this may look like this with an empty icon. That's not fun...

<figure><img src="../.gitbook/assets/image (56).png" alt=""><figcaption><p>AWS Health Status without an icon.</p></figcaption></figure>

Let's now register a new extension helps enrich the UI with a few steps.

1. Prepare an icon image to be uploaded.
2. Go to "extensions" to add a new "extension".
3. Name and paste a key part of the URL. It will allow PITWALL to pattern-match and detect a site / tool in the studio.

{% embed url="https://drive.google.com/file/d/1VcpnIMNnW6FsJK-8Dw2sbflfKghpAhuc/view?usp=sharing" %}

Now, your scenario looks much better with the icon in the studio. As this is now contributed as a public extension, this is now available for everyone! You can also register an extension in your tenant only when you register the extension as a private extension.

<figure><img src="../.gitbook/assets/image (62).png" alt=""><figcaption></figcaption></figure>

### 2. Adding time format(s) to detect timestamps from the URL you would like to parameterize in the studio.

Here is one of the extensions contributed by one of the PITWALL users to accommodate a timestamp format of Coralogix's tracing view. This extension is defining how to detect timestamps for "from" and "to" in the URL.

`from%3A[0-9]{4}-[0-9]{2}-[0-9]{2}T[0-9]{2}%3A[0-9]{2}%3A[0-9]{2}.[0-9]{3}Z`

`to%3A[0-9]{4}-[0-9]{2}-[0-9]{2}T[0-9]{2}%3A[0-9]{2}%3A[0-9]{2}.[0-9]{3}Z`

<figure><img src="../.gitbook/assets/image (68).png" alt=""><figcaption></figcaption></figure>

Then, PITWALL can detect the timestamp(s) from the Coralogix's tracing view.&#x20;

[https://YOURTENANT.coralogix.com/#/query-new/tracing?metadataFilters=%5B%7B%22metadataField%22%3A1%2C%22values%22%3A%5B%5D%7D%2C%7B%22metadataField%22%3A2%2C%22values%22%3A%5B%5D%7D%2C%7B%22metadataField%22%3A3%2C%22values%22%3A%5B%5D%7D%2C%7B%22metadataField%22%3A4%2C%22values%22%3A%5B%5D%7D%5D\&tagFilters=%5B%5D\&traceId=null\&time=%22from%3A2022-10-01T18%3A04%3A00.000Z%2Cto%3A2022-10-01T18%3A19%3A00.000Z%22](https://tocaro-prod.coralogix.com/#/query-new/tracing?metadataFilters=%5B%7B%22metadataField%22%3A1%2C%22values%22%3A%5B%5D%7D%2C%7B%22metadataField%22%3A2%2C%22values%22%3A%5B%5D%7D%2C%7B%22metadataField%22%3A3%2C%22values%22%3A%5B%5D%7D%2C%7B%22metadataField%22%3A4%2C%22values%22%3A%5B%5D%7D%5D\&tagFilters=%5B%5D\&traceId=null\&time=%22from%3A2022-10-01T18%3A04%3A00.000Z%2Cto%3A2022-10-01T18%3A19%3A00.000Z%22)

<figure><img src="../.gitbook/assets/image (16).png" alt=""><figcaption></figcaption></figure>

This approach can scale across many different tools either your own tools or newly born cloud services.
