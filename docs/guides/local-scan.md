---
sidebar_position: 1
---

# Local Scan

The local scan allows you to recursively scan a directory for secrets. We will use the `-p` or `--path` option to specify the directory to scan.

Below we are going to scan our `mock` test folder for secrets.

```bash
$ bogu -p mock
Bogu v0.0.14

Starting local path scan...

File: mock/aws-id-secret.txt
Found AWS Access ID: AKIAIOSFODNN7EXAMPLE
Found AWS Access Secret: wJalrXUtnFEMI/K7MDENG/bPxRfiCYEXAMPLEKEY

File: mock/aws-session-id-token.txt
Found AWS Session ID: ASIAIOSFODNN7EXAMPLE
Found AWS Session Token: FwoGZXIvYXdzEIT//////////wEaDDa5f+4m90Dc2H7eQiK9AXCnXpAgi0u7A+o1RpO5Q5GtMnv8oR+0V8GyHc7bGx1FP2bR7Bm2PqO7vXWzD9Y5DpKpG3j1gPv5mP0kIr4G3X/0dJGvMx0RQxfUq5u2cpWnJ5Z9J2Lm2P0RpTQaGwR5tNc7XJ0nFCaUJhLJi4c1naqfwpKyA5b43YzE3Iw8WMTIzNDU2Nzg5QUJDREVGR0g

File: mock/gcp-api-key.txt
Found GCP API Key: AIzaSyDmmR-dGZ9xuRIjBxyBDfiFcS64k2aIuc0
Found GCP API Key: AIzaSyCtZfvomdJjZ7n0PusqP8tgS9VV0Pn7DmQ
Found GCP API Key: AIzaSyCCjcctnCEr_2bj8Km2kbvp1Y1eHAitSNA
Found GCP API Key: AIzaSyB-v48SFeG1_70_BoV9ap0WwHfr5OaAPsc
Found GCP API Key: AIzaSyDfYh7FKz9reETkNaOT6TY0wujDduxfJko
Found GCP API Key: AIzaSyCeex60KPsQnlZZv2yn_Te_44WvCTRiuZ4

File: mock/gcp-oauth.json
Found GCP OAuth file: mock/gcp-oauth.json
File: mock/gcp-service-credentials.json
Found GCP service credentials file: mock/gcp-service-credentials.json
```

By default bogu will output information about the file it is scanning and the secrets it finds. You can turn this output off by using the `s` or `--silent` option.

```bash
$ bogu -p mock -s
Bogu v0.0.14

Starting local path scan...

$
```
