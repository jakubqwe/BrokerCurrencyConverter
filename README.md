# Currency Converter

A framework to convert currencies and transaction history from brokers' APIs 

## `CurrencyConverter`

- Allows converting currencies using specified provider

## Rates providers:

- `NbpCurrencyProvider`
  - Provides currency conversion rates from Polish central bank
  - Source: http://api.nbp.pl/
- `EbcCurrencyProvider`
  - Provides currency conversion rates from European central bank
  - Source: https://sdw-wsrest.ecb.europa.eu/
  
## Transaction providers:

- `IbkrFileTransactionProvider`
  - Provides transactions from Interactive Brokers' statement in CSV format
