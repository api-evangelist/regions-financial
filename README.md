# Regions Financial

Regions Financial Corporation is a member of the S&P 500 Index and one of the nation's largest full-service providers of consumer and commercial banking, wealth management, and mortgage products and services. Regions Bank is implementing open banking capabilities through a partnership with Axway Amplify Open Banking, building FDX-compliant APIs enabling secure financial data sharing. Regions joined FDX in 2021 and is targeting full CFPB compliance by April 2027.

**Website:** [https://www.regions.com](https://www.regions.com)
**Commercial Banking:** [https://www.regions.com/commercial-banking](https://www.regions.com/commercial-banking)

## APIs

### Regions Open Banking API

FDX-compliant open banking APIs enabling consent-based access to account information, transactions, customer data, payment initiation, and consent management. Built on Axway Amplify Open Banking with OAuth 2.0 authorization.

- **Press Release:** [Regions Bank Selects Axway to Accelerate Open Banking](https://ir.regions.com/news-events/press-releases/news-details/2025/Enhancing-Customer-Control-of-Financial-Data-Regions-Bank-Selects-Axway-to-Accelerate-Open-Banking-Services/default.aspx)

## OpenAPI Specifications

| API | File |
|-----|------|
| Regions Open Banking API | [openapi/regions-open-banking-openapi.yml](openapi/regions-open-banking-openapi.yml) |

## JSON Schemas

| Schema | File |
|--------|------|
| Account | [json-schema/regions-account-schema.json](json-schema/regions-account-schema.json) |
| Transaction | [json-schema/regions-transaction-schema.json](json-schema/regions-transaction-schema.json) |

## JSON Structures

| Structure | File |
|-----------|------|
| Account | [json-structure/regions-account-structure.json](json-structure/regions-account-structure.json) |
| Transaction | [json-structure/regions-transaction-structure.json](json-structure/regions-transaction-structure.json) |

## JSON-LD Context

| Context | File |
|---------|------|
| Regions Financial | [json-ld/regions-financial-context.jsonld](json-ld/regions-financial-context.jsonld) |

## Examples

| Example | File |
|---------|------|
| List Accounts | [examples/regions-list-accounts-example.json](examples/regions-list-accounts-example.json) |
| List Transactions | [examples/regions-list-transactions-example.json](examples/regions-list-transactions-example.json) |

## Spectral Rules

| Ruleset | File |
|---------|------|
| Regions Financial Rules | [rules/regions-financial-rules.yml](rules/regions-financial-rules.yml) |

## Capabilities

### Shared Definitions

| API | File |
|-----|------|
| Regions Open Banking | [capabilities/shared/regions-open-banking.yaml](capabilities/shared/regions-open-banking.yaml) |

### Workflow Capabilities

| Workflow | Description | File |
|----------|-------------|------|
| Open Banking | Account aggregation, transactions, payments, and consent management | [capabilities/open-banking.yaml](capabilities/open-banking.yaml) |

## Vocabulary

| Vocabulary | File |
|------------|------|
| Regions Financial | [vocabulary/regions-financial-vocabulary.yml](vocabulary/regions-financial-vocabulary.yml) |
