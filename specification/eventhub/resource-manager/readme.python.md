## Python

These settings apply only when `--python` is specified on the command line.
Please also specify `--python-sdks-folder=<path to the root directory of your azure-sdk-for-python clone>`.

``` yaml $(python)
title: EventHubManagementClient
azure-arm: true
license-header: MICROSOFT_MIT_NO_VERSION
package-name: azure-mgmt-eventhub
namespace: azure.mgmt.eventhub
package-version: 1.0.0b1
clear-output-folder: true
```

``` yaml $(python)
no-namespace-folders: true
output-folder: $(python-sdks-folder)/eventhub/azure-mgmt-eventhub/azure/mgmt/eventhub
```

``` yaml $(python)
modelerfour:
  lenient-model-deduplication: true
```
