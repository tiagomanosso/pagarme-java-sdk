
# Create Seller Request

## Structure

`CreateSellerRequest`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Name` | `String` | Required | Name | String getName() | setName(String name) |
| `Code` | `String` | Optional | Seller's code identification | String getCode() | setCode(String code) |
| `Description` | `String` | Optional | Description | String getDescription() | setDescription(String description) |
| `Document` | `String` | Optional | Document number (individual / company) | String getDocument() | setDocument(String document) |
| `Address` | [`CreateAddressRequest`](/doc/models/create-address-request.md) | Optional | Address | CreateAddressRequest getAddress() | setAddress(CreateAddressRequest address) |
| `Type` | `String` | Optional | Person type (individual / company) | String getType() | setType(String type) |
| `Metadata` | `Map<String, String>` | Required | Metadata | Map<String, String> getMetadata() | setMetadata(Map<String, String> metadata) |

## Example (as JSON)

```json
{
  "name": "name0",
  "code": null,
  "description": null,
  "document": null,
  "address": null,
  "type": null,
  "metadata": {
    "key0": "metadata3",
    "key1": "metadata4",
    "key2": "metadata5"
  }
}
```

