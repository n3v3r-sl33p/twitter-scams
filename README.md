# twitter-scams
A constantly changing list of known Twitter scams and their many bots involved.

## [View The Dataset](https://gist.github.com/n3v3r-sl33p)



## Parsing Example (Python)

```py
import json
import requests

endpoint = "https://gist.githubusercontent.com/n3v3r-sl33p/23e34a84dc1392e9bf1324fab95e8642/raw"

r = get(endpoint).json()

for report in reports_object:
    print(report["uuid"])
    print(report["status"])
```
