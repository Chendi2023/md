# Welcome to the API Portal for DataCloud System API
データクラウド システム API ポータルへようこそ

## Overview

The DataCloud System API provides streamlined access to core data objects within Salesforce Data Cloud. Users can leverage this API to:

1. Retrieve data from key objects: **accounts**, **aeras**, **orders**, **surveys**, and **webAccounts**.
2. Integrate and interact with data through various methods, including:
    - Fetching records by ID
    - Streaming data into the Data Cloud with `POST` and `DELETE` methods
    - Performing bulk data insertions for efficient data processing

This portal provides a comprehensive guide to the API resources and their expected behavior, allowing you to incorporate this API seamlessly into your **Application Network**.

---

## Use Case and API Architecture
ユースケースと API アーキテクチャ

Below is an example of how the DataCloud System API can be utilized within a layered API architecture using MuleSoft's **3-layered API approach**: **Experience API**, **Process API**, and **System API**.

![MuleSoft Three-Layered API](https://anypoint.mulesoft.com/static/img/mulesoft-3-tiered-architecture.png)

---

## Functional Overview
機能概要

| Object        | Methods                           | Description                                           |
|---------------|-----------------------------------|-------------------------------------------------------|
| **accounts**  | `GET by ID`, `POST`, `DELETE`, `Bulk Insert` | Retrieve and manage account records in bulk or individually. |
| **aeras**     | `GET by ID`, `POST`, `DELETE`, `Bulk Insert` | Access and manage address records.                    |
| **orders**    | `GET by ID`, `POST`, `DELETE`, `Bulk Insert` | Integrate and monitor customer orders.                |
| **surveys**   | `GET by ID`, `POST`, `DELETE`, `Bulk Insert` | Handle survey data for feedback and analysis.         |
| **webAccounts** | `GET by ID`, `POST`, `DELETE`, `Bulk Insert` | Manage web-based account records.                   |

Refer to the **API Summary** section for further details on each resource and their behavior.

---

This portal is hosted on the Anypoint Platform, leveraging RAML version 1.0 for API definition.
Anypoint Platform上でホストされ、RAMLバージョン1.0で定義されています。

For more information on OAS, see [OAS](https://anypoint.mulesoft.com/designcenter/designer/#/exchange/a91bafe6-0a6c-487c-b253-718722cba3b1/data-cloud-integration-api-2/1.1.20).
