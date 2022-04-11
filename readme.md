# Azure Synapse Analytics

> see https://aka.ms/autorest

This is the AutoRest configuration file for Azure Synapse Analytics.

---

## Getting Started

To build the SDK for Azure Synapse Analytics, simply [Install AutoRest](https://aka.ms/autorest/install) and in this folder, run:

> `autorest`

To see additional help and options, run:

> `autorest --help`

---

## Configuration

### Basic Information

These are the global settings for the Azure Synapse Analytics API.

```yaml
use-extension:
  "@autorest/modelerfour": "4.23.1"

modelerfour:
  lenient-model-deduplication: true
openapi-type: data-plane
input-file:
  - artifacts.json
  - artifacts-v2.json
```
