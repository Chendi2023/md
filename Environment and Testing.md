## Environment Details for DataCloud System API

To support integration with **DataCloud System API**, please set up and maintain your own development, test, and production environments, following the standard software development lifecycle.

| Environment Name      | Purpose                              | API Endpoint URL                                                                |
|-----------------------|--------------------------------------|---------------------------------------------------------------------------------|
| Development Environment | For development and unit testing    | https://datacloud-system-api-dev.cloudhub.io/XXXXXX                     |
| Production Environment | For live data operations            | https://datacloud-system-api.cloudhub.io/XXXXXX                          |

------

## Pre-requisites

To consume the DataCloud System API, you must request access and generate your **Client ID** and **Client Secret**. Please refer to the **How to Request Access** section on the portal.

------

## Testing Your Integration

Below are some example test cases to help validate your integration with the **DataCloud System API**. You are encouraged to expand upon these with test cases relevant to your specific use cases.

| Test Case                    | API URL Example                                                                | Expected Outcome                          |
|------------------------------|-------------------------------------------------------------------------------|-------------------------------------------|
| Retrieve account by ID       | `/accounts/{customerid}`  with `GET` method                                                    | The specified account details are returned. |
| Insert bulk account data     | `/batchaccounts`                                                              | Bulk data is inserted and response status confirms success. |
|Delete records of accounts by list of id      | `/accounts`   with `DELETE` method                                                           | Bulk deletion is successful and response confirms deleted records. |
| Verify order by ID           | `/orders/{orderid}`  with `GET` method                                                          | The specified order details are returned. |
| Stream post for `aeras` object | `/aeras` with `POST`Method                                             | Streamed data is successfully posted to the `aeras` object. |
| Delete records of surveys by list of id | `/surveys/{surveysid}` with `DELETE` method                                     | The specified survey record is successfully deleted. |

**Note**: Modify each test case to include values relevant to your specific data objects in the **DataCloud System API**
