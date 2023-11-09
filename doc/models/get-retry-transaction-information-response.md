
# Get Retry Transaction Information Response

Response object for getting an RetryTransactionInformation

## Structure

`GetRetryTransactionInformationResponse`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `BrandFailureReturnCode` | `String` | Required | - | String getBrandFailureReturnCode() | setBrandFailureReturnCode(String brandFailureReturnCode) |
| `TransactionLimit` | `Integer` | Required | - | Integer getTransactionLimit() | setTransactionLimit(Integer transactionLimit) |
| `TransactionDateLimit` | `LocalDateTime` | Required | - | LocalDateTime getTransactionDateLimit() | setTransactionDateLimit(LocalDateTime transactionDateLimit) |

## Example (as JSON)

```json
{
  "brand_failure_return_code": "brand_failure_return_code2",
  "transaction_limit": 44,
  "transaction_date_limit": "2016-03-13T12:52:32.123Z"
}
```

