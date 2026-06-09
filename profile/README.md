# Crypto Chief — Web3 Infrastructure for Developers

**Crypto Chief** builds high-performance Web3 infrastructure for developers, fintech products, wallets, exchanges, payment companies, SaaS platforms, marketplaces, gaming projects, and blockchain applications.

We provide developer-friendly APIs and SDKs for **crypto payment processing**, **multichain RPC**, **blockchain data**, **real-time webhooks**, **wallet infrastructure**, **stablecoin payments**, **payout automation**, and **AML intelligence**.

Our goal is simple: help engineering teams build blockchain products faster, without spending months on custom crypto infrastructure.

---

## What is Crypto Chief?

Crypto Chief is a Web3 infrastructure platform designed for production backend systems.

With Crypto Chief, developers can:

- accept crypto payments and create PayIn invoices
- send crypto payouts and automate mass payouts
- manage static deposit addresses
- monitor wallets and transactions
- verify payment webhooks
- connect to 70+ blockchain networks over multichain RPC
- access normalized blockchain data APIs
- build AML and risk-scoring workflows

Crypto Chief helps teams build reliable crypto products using clean APIs, SDKs, webhooks, and production-ready infrastructure.

---

## Products

### Crypto Processing

Crypto Chief Processing is a **non-custodial** payment stack to accept crypto payments, send payouts, manage wallets, and automate stablecoin payment flows.

Use cases:

- crypto payment gateway and merchant checkout
- PayIn invoices and customer deposits
- static deposit addresses
- crypto, mass, and stablecoin payouts (USDT, USDC)
- wallet infrastructure and treasury automation
- webhook-based payment confirmation

Built for exchanges, wallets, SaaS products, fintech platforms, marketplaces, gaming, and B2B payment systems.

---

### Multichain RPC Gateway

Crypto Chief RPC Gateway provides reliable RPC access across **70+ blockchain networks**, with multichain routing and fallback logic.

Use cases:

- wallet backends, dApps, and DeFi products
- explorers, indexers, and analytics systems
- trading bots and NFT platforms
- on-chain monitoring and Web3 backends

It lets developers connect to dozens of chains without running infrastructure for each one separately — designed for teams that need scalable RPC, fallback, and production-ready connectivity.

---

### Unified Blockchain API

Crypto Chief Unified API provides normalized blockchain data across multiple networks through one consistent layer.

Use cases:

- balances, transactions, and token transfers
- wallet activity and contract interactions
- historical and analytics-ready blockchain data
- multichain portfolio views and backend automation

This makes it easier to build products that work across many chains using a single API.

---

### EventStream Webhooks

Crypto Chief EventStream lets developers subscribe to blockchain events and receive real-time webhook notifications.

Use cases:

- payment confirmations and deposit monitoring
- payout status updates
- address and token-transfer monitoring
- wallet activity tracking and backend automation

EventStream helps backend teams react to on-chain activity without constant polling.

---

### AML Intelligence

Crypto Chief AML Intelligence analyzes wallets, monitors transactions, detects risk, and powers compliance workflows.

Use cases:

- wallet risk scoring and AML screening
- transaction monitoring and fraud detection
- suspicious-activity and cross-chain investigation
- compliance automation and merchant/user risk checks

Designed for crypto businesses that need clear visibility into transaction risk and wallet behavior.

---

## Open-source SDKs

Crypto Chief SDKs help developers integrate Crypto Chief APIs faster using native language clients.

### Available SDKs

| Language | Repository | Status |
| --- | --- | --- |
| Go | [cryptochief-crypto-processing-go](https://github.com/crypto-chiefs/cryptochief-crypto-processing-go) | Available |
| JavaScript / TypeScript | [cryptochief-crypto-processing-node](https://github.com/crypto-chiefs/cryptochief-crypto-processing-node) | Available |
| Python | [cryptochief-crypto-processing-python](https://github.com/crypto-chiefs/cryptochief-crypto-processing-python) | Available |
| PHP | [cryptochief-crypto-processing-php](https://github.com/crypto-chiefs/cryptochief-crypto-processing-php) | Available |
| Kotlin / JVM | [cryptochief-crypto-processing-kotlin](https://github.com/crypto-chiefs/cryptochief-crypto-processing-kotlin) | Available |
| .NET / C# | [cryptochief-crypto-processing-dotnet](https://github.com/crypto-chiefs/cryptochief-crypto-processing-dotnet) | Available |
| Java | [cryptochief-crypto-processing-java](https://github.com/crypto-chiefs/cryptochief-crypto-processing-java) | Available |

---

## Go SDK for Crypto Processing

The official Go SDK for the Crypto Chief Processing API helps backend developers integrate crypto payment processing into Go applications.

- Repository: https://github.com/crypto-chiefs/cryptochief-crypto-processing-go
- SDK guide & docs: https://docs-sdk.crypto-chief.com/processing/go

Install:

```bash
go get github.com/crypto-chiefs/cryptochief-crypto-processing-go@latest
```

The Go SDK covers crypto payment processing across 25+ chains — PayIn invoices, payouts and mass payouts, static deposits, wallet management, transaction signing, webhook verification, and stablecoin (USDT / USDC) flows on Ethereum, Tron, TON, Solana, and Bitcoin.

Typical use cases:

- accepting crypto payments and building a crypto payment gateway in Go
- automating merchant and stablecoin payouts
- verifying crypto payment webhooks
- integrating blockchain payments into SaaS, fintech, and Web3 backends

---

## Node.js / TypeScript SDK for Crypto Processing

The official Node.js / TypeScript SDK for the Crypto Chief Processing API helps backend developers integrate crypto payment processing into Node.js applications.

- Repository: https://github.com/crypto-chiefs/cryptochief-crypto-processing-node
- SDK guide & docs: https://docs-sdk.crypto-chief.com/processing/js
- Package (npm): https://www.npmjs.com/package/@cryptochiefs/cryptochief-crypto-processing-node

Install:

```bash
npm install @cryptochiefs/cryptochief-crypto-processing-node
```

The Node.js SDK covers crypto payment processing across 25+ chains — PayIn invoices, payouts and mass payouts, static deposits, wallet management, transaction signing, webhook verification, and stablecoin (USDT / USDC) flows on Ethereum, Tron, TON, Solana, and Bitcoin. Written in TypeScript with full type definitions, it works in plain JavaScript too and ships both ESM and CommonJS builds (Node.js 18+).

Typical use cases:

- accepting crypto payments and building a crypto payment gateway in Node.js / TypeScript
- automating merchant and stablecoin payouts
- verifying crypto payment webhooks
- integrating blockchain payments into SaaS, fintech, and Web3 backends

---

## Python SDK for Crypto Processing

The official async Python SDK for the Crypto Chief Processing API helps backend developers integrate crypto payment processing into Python applications.

- Repository: https://github.com/crypto-chiefs/cryptochief-crypto-processing-python
- SDK guide & docs: https://docs-sdk.crypto-chief.com/processing/python
- Package (PyPI): https://pypi.org/project/cryptochief-crypto-processing-python/

Install:

```bash
pip install cryptochief-crypto-processing-python
```

The Python SDK covers crypto payment processing across 25+ chains — PayIn invoices, payouts and mass payouts, static deposits, wallet management, transaction signing, webhook verification, and stablecoin (USDT / USDC) flows on Ethereum, Tron, TON, Solana, and Bitcoin. Async-first (built on asyncio and httpx) with fully typed dataclass requests and responses (Python 3.10+).

Typical use cases:

- accepting crypto payments and building a crypto payment gateway in Python
- automating merchant and stablecoin payouts
- verifying crypto payment webhooks
- integrating blockchain payments into SaaS, fintech, and Web3 backends

---

## PHP SDK for Crypto Processing

The official PHP SDK for the Crypto Chief Processing API helps backend developers integrate crypto payment processing into PHP applications, including Laravel and Symfony projects.

- Repository: https://github.com/crypto-chiefs/cryptochief-crypto-processing-php
- SDK guide & docs: https://docs-sdk.crypto-chief.com/processing/php
- Package (Packagist): https://packagist.org/packages/crypto-chiefs/cryptochief-crypto-processing-php

Install:

```bash
composer require crypto-chiefs/cryptochief-crypto-processing-php
```

The PHP SDK covers crypto payment processing across 25+ chains — PayIn invoices, payouts and mass payouts, static deposits, wallet management, transaction signing, webhook verification, and stablecoin (USDT / USDC) flows on Ethereum, Tron, TON, Solana, and Bitcoin. Built for PHP 8.1+ with strict types, readonly DTOs, backed enums, and a PSR-18 HTTP client (Guzzle by default), so it drops straight into Laravel, Symfony, Slim, and any modern PHP backend.

Typical use cases:

- accepting crypto payments and building a crypto payment gateway in PHP
- automating merchant and stablecoin payouts from Laravel or Symfony backends
- verifying crypto payment webhooks
- integrating blockchain payments into SaaS, fintech, e-commerce, and Web3 backends

---

## Kotlin / JVM SDK for Crypto Processing

The official Kotlin / JVM SDK for the Crypto Chief Processing API helps backend developers integrate crypto payment processing into Kotlin and Java services, Spring Boot apps, and Android backends.

- Repository: https://github.com/crypto-chiefs/cryptochief-crypto-processing-kotlin
- SDK guide & docs: https://docs-sdk.crypto-chief.com/processing/kotlin
- Package (Maven Central): https://central.sonatype.com/artifact/com.crypto-chief/cryptochief-crypto-processing-kotlin

Install (Gradle Kotlin DSL):

```kotlin
dependencies {
    implementation("com.crypto-chief:cryptochief-crypto-processing-kotlin:0.1.0")
}
```

The Kotlin SDK covers crypto payment processing across 25+ chains — PayIn invoices, payouts and mass payouts, static deposits, wallet management, transaction signing, webhook verification, and stablecoin (USDT / USDC) flows on Ethereum, Tron, TON, Solana, and Bitcoin. Coroutines-first (every API method is a `suspend fun`), built on OkHttp and kotlinx.serialization, with a self-contained Keccak / BoC / Borsh layer — zero BouncyCastle or external blockchain libraries. JVM 11+.

Typical use cases:

- accepting crypto payments and building a crypto payment gateway in Kotlin
- automating merchant and stablecoin payouts from Spring Boot, Ktor, or Android backends
- verifying crypto payment webhooks
- integrating blockchain payments into SaaS, fintech, and Web3 backends on the JVM

---

## .NET / C# SDK for Crypto Processing

The official .NET / C# SDK for the Crypto Chief Processing API helps backend developers integrate crypto payment processing into ASP.NET Core, Azure Functions, and other .NET applications.

- Repository: https://github.com/crypto-chiefs/cryptochief-crypto-processing-dotnet
- SDK guide & docs: https://docs-sdk.crypto-chief.com/processing/dotnet
- Package (NuGet): https://www.nuget.org/packages/CryptoChief.Processing

Install:

```bash
dotnet add package CryptoChief.Processing
```

The .NET SDK covers crypto payment processing across 25+ chains — PayIn invoices, payouts and mass payouts, static deposits, wallet management, transaction signing, webhook verification, and stablecoin (USDT / USDC) flows on Ethereum, Tron, TON, Solana, and Bitcoin. Built for .NET 6 and .NET 8 with full async/await, `System.Text.Json` source-generated DTOs, `IHttpClientFactory` integration, and `AddCryptoChief()` DI extensions for Microsoft.Extensions.DependencyInjection.

Typical use cases:

- accepting crypto payments and building a crypto payment gateway in C#
- automating merchant and stablecoin payouts from ASP.NET Core or Azure Functions
- verifying crypto payment webhooks
- integrating blockchain payments into SaaS, fintech, and Web3 backends on .NET

---

## Java SDK for Crypto Processing

The official Java SDK for the Crypto Chief Processing API helps backend developers integrate crypto payment processing into Java applications — Spring Boot, Quarkus, Micronaut, and any modern JVM stack.

- Repository: https://github.com/crypto-chiefs/cryptochief-crypto-processing-java
- SDK guide & docs: https://docs-sdk.crypto-chief.com/processing/java
- Package (Maven Central): https://central.sonatype.com/artifact/com.crypto-chief/cryptochief-crypto-processing-java

Install (Maven):

```xml
<dependency>
  <groupId>com.crypto-chief</groupId>
  <artifactId>cryptochief-crypto-processing-java</artifactId>
  <version>0.1.0</version>
</dependency>
```

The Java SDK covers crypto payment processing across 25+ chains — PayIn invoices, payouts and mass payouts, static deposits, wallet management, transaction signing, webhook verification, and stablecoin (USDT / USDC) flows on Ethereum, Tron, TON, Solana, and Bitcoin. Pure Java 17+ with records for all DTOs, OkHttp transport, Jackson canonical JSON, and a self-contained Keccak / BoC / Borsh layer — no Kotlin runtime, no BouncyCastle, no reactive bridges.

Typical use cases:

- accepting crypto payments and building a crypto payment gateway in Java
- automating merchant and stablecoin payouts from Spring Boot, Quarkus, or Micronaut backends
- verifying crypto payment webhooks
- integrating blockchain payments into SaaS, fintech, and Web3 backends on the JVM

---

## Who uses Crypto Chief?

Crypto Chief is built for engineering teams working on:

- crypto payment gateways and merchant payment systems
- fintech platforms, wallets, and exchanges
- SaaS products and marketplaces
- GameFi, betting, and gaming platforms
- trading platforms and blockchain analytics
- AML / compliance tools
- DeFi, NFT, and cross-chain applications

---

## Supported blockchain ecosystem

Crypto Chief's RPC Gateway reaches **70+ blockchain networks**, and Crypto Processing supports payments and payouts across **25+ of them** — including major ecosystems:

- Ethereum
- BNB Smart Chain
- Polygon
- Tron
- Solana
- TON
- Bitcoin
- EVM-compatible and Layer-2 networks

Crypto Chief is especially useful for products built on stablecoins such as USDT and USDC.

---

## Why developers choose Crypto Chief

- Developer-first API and SDK design
- Non-custodial payment architecture
- Webhook-based automation
- 70+ blockchain networks via multichain RPC
- Stablecoin-ready PayIns and Payouts
- Static deposit and wallet infrastructure
- Blockchain data APIs and AML / compliance tools
- Production-ready backend architecture for fintech, Web3, SaaS, and payment products

---

## Links

- Website: https://crypto-chief.com/
- Crypto Processing: https://crypto-chief.com/processing/
- RPC Gateway: https://crypto-chief.com/rpc/
- AML Intelligence: https://crypto-chief.com/aml/
- White Label: https://crypto-chief.com/whitelabel/
- Documentation: https://docs.crypto-chief.com/
- Go SDK: https://github.com/crypto-chiefs/cryptochief-crypto-processing-go
- Go SDK docs: https://docs-sdk.crypto-chief.com/processing/go
- Node.js / TypeScript SDK: https://github.com/crypto-chiefs/cryptochief-crypto-processing-node
- Node.js / TypeScript SDK docs: https://docs-sdk.crypto-chief.com/processing/js
- Python SDK: https://github.com/crypto-chiefs/cryptochief-crypto-processing-python
- Python SDK docs: https://docs-sdk.crypto-chief.com/processing/python
- PHP SDK: https://github.com/crypto-chiefs/cryptochief-crypto-processing-php
- PHP SDK docs: https://docs-sdk.crypto-chief.com/processing/php
- Kotlin / JVM SDK: https://github.com/crypto-chiefs/cryptochief-crypto-processing-kotlin
- Kotlin / JVM SDK docs: https://docs-sdk.crypto-chief.com/processing/kotlin
- .NET / C# SDK: https://github.com/crypto-chiefs/cryptochief-crypto-processing-dotnet
- .NET / C# SDK docs: https://docs-sdk.crypto-chief.com/processing/dotnet
- Java SDK: https://github.com/crypto-chiefs/cryptochief-crypto-processing-java
- Java SDK docs: https://docs-sdk.crypto-chief.com/processing/java
