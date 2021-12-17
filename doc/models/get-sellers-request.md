
# Get Sellers Request

## Structure

`GetSellersRequest`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Name` | `String` | Required | - | String getName() | setName(String name) |
| `Document` | `String` | Required | - | String getDocument() | setDocument(String document) |
| `Code` | `String` | Required | - | String getCode() | setCode(String code) |
| `Status` | `String` | Required | - | String getStatus() | setStatus(String status) |
| `Type` | `String` | Required | - | String getType() | setType(String type) |
| `CreatedSince` | `String` | Optional | - | String getCreatedSince() | setCreatedSince(String createdSince) |
| `CreatedUntil` | `String` | Optional | - | String getCreatedUntil() | setCreatedUntil(String createdUntil) |

## Example (as JSON)

```json
{
  "name": "name0",
  "document": "document6",
  "code": "code8",
  "status": "status8",
  "type": "type0",
  "created_Since": null,
  "created_Until": null
}
```

