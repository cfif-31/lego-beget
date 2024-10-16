---
title: "Beget.com"
date: 2019-03-03T16:39:46+01:00
draft: false
slug: beget
dnsprovider:
  since:    "v1.0.0"
  code:     "beget"
  url:      "https://beget.com/"
---

<!-- THIS DOCUMENTATION IS AUTO-GENERATED. PLEASE DO NOT EDIT. -->
<!-- providers/dns/beget/beget.toml -->
<!-- THIS DOCUMENTATION IS AUTO-GENERATED. PLEASE DO NOT EDIT. -->


Configuration for [Beget.com](https://beget.com/).


<!--more-->

- Code: `beget`
- Since: v1.0.0


Here is an example bash command using the Beget.com provider:

```bash
BEGET_USERNAME=xxxxxx \
BEGET_PASSWORD=yyyyyy \
lego --email you@example.com --dns beget --domains my.example.org run
```




## Credentials

| Environment Variable Name | Description |
|-----------------------|-------------|
| `BEGET_PASSWORD` | API password |
| `BEGET_USERNAME` | API username |

The environment variable names can be suffixed by `_FILE` to reference a file instead of a value.
More information [here]({{< ref "dns#configuration-and-credentials" >}}).


## Additional Configuration

| Environment Variable Name | Description |
|--------------------------------|-------------|
| `BEGET_HTTP_TIMEOUT` | API request timeout |
| `BEGET_POLLING_INTERVAL` | Time between DNS propagation check |
| `BEGET_PROPAGATION_TIMEOUT` | Maximum waiting time for DNS propagation |
| `BEGET_TTL` | The TTL of the TXT record used for the DNS challenge |

The environment variable names can be suffixed by `_FILE` to reference a file instead of a value.
More information [here]({{< ref "dns#configuration-and-credentials" >}}).




## More information

- [API documentation](https://beget.com/ru/kb/api/funkczii-upravleniya-dns)

<!-- THIS DOCUMENTATION IS AUTO-GENERATED. PLEASE DO NOT EDIT. -->
<!-- providers/dns/beget/beget.toml -->
<!-- THIS DOCUMENTATION IS AUTO-GENERATED. PLEASE DO NOT EDIT. -->
