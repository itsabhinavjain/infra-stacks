## Simplest method (Local installation)
Local installation using airbyte command line tool (abstl)
https://docs.airbyte.com/using-airbyte/getting-started/oss-quickstart

In case you want to disable https
```values.yaml
global:
  auth:
    enabled: false
```

```
abctl local install
abctl local install --low-resource-mode --port 8001
abctl local install --low-resource-mode --port 8001 --values ./values.yaml

abctl local credentials
abctl local credentials --password YourStrongPasswordExample

abctl local uninstall
abctl local uninstall --persisted
rm -rf ~/.airbyte/abctl
```

## Other methods
- ECommerce Data Pipeline - Open source, Dagster, DBT 
	- https://www.youtube.com/watch?v=PMYxeWeNoX8
