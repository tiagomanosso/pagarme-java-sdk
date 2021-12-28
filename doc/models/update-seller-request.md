
# Update Seller Request

## Structure

`UpdateSellerRequest`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Name` | `String` | Required | Seller name | String getName() | setName(String name) |
| `Code` | `String` | Required | Seller code | String getCode() | setCode(String code) |
| `Description` | `String` | Required | Seller description | String getDescription() | setDescription(String description) |
| `Document` | `String` | Required | Seller document CPF or CNPJ | String getDocument() | setDocument(String document) |
| `Status` | `String` | Required | - | String getStatus() | setStatus(String status) |
| `Type` | `String` | Required | - | String getType() | setType(String type) |
| `Address` | [`CreateAddressRequest`](/doc/models/create-address-request.md) | Required | - | CreateAddressRequest getAddress() | setAddress(CreateAddressRequest address) |
| `Metadata` | `Map<String, String>` | Required | - | Map<String, String> getMetadata() | setMetadata(Map<String, String> metadata) |

## Example (as JSON)

```json
{
  "name": "name0",
  "code": "code8",
  "description": "description0",
  "document": "document6",
  "status": "status8",
  "type": "type0",
  "address": {
    "street": "street6",
    "number": "number4",
    "zip_code": "zip_code0",
    "neighborhood": "neighborhood2",
    "city": "city6",
    "state": "state2",
    "country": "country0",
    "complement": "complement2",
    "metadata": {
      "key0": "metadata3",
      "key1": "metadata2",
      "key2": "metadata1"
    },
    "line_1": "line_10",
    "line_2": "line_24"
  },
  "metadata": {
    "key0": "metadata3",
    "key1": "metadata4",
    "key2": "metadata5"
  }
}
```

