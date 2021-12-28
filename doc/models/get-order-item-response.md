
# Get Order Item Response

Response object for getting an order item

## Structure

`GetOrderItemResponse`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Id` | `String` | Required | Id | String getId() | setId(String id) |
| `Amount` | `int` | Required | - | int getAmount() | setAmount(int amount) |
| `Description` | `String` | Required | - | String getDescription() | setDescription(String description) |
| `Quantity` | `int` | Required | - | int getQuantity() | setQuantity(int quantity) |
| `GetSellerResponse` | [`GetSellerResponse`](/doc/models/get-seller-response.md) | Optional | Seller data | GetSellerResponse getGetSellerResponse() | setGetSellerResponse(GetSellerResponse getSellerResponse) |
| `Category` | `String` | Required | Category | String getCategory() | setCategory(String category) |
| `Code` | `String` | Required | Code | String getCode() | setCode(String code) |

## Example (as JSON)

```json
{
  "id": "id0",
  "amount": 46,
  "description": "description0",
  "quantity": 68,
  "GetSellerResponse": null,
  "category": "category2",
  "code": "code8"
}
```

