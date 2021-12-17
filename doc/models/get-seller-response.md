
# Get Seller Response

## Structure

`GetSellerResponse`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Id` | `String` | Required | Identification | String getId() | setId(String id) |
| `Name` | `String` | Required | - | String getName() | setName(String name) |
| `Code` | `String` | Required | - | String getCode() | setCode(String code) |
| `Document` | `String` | Required | - | String getDocument() | setDocument(String document) |
| `Description` | `String` | Required | Description | String getDescription() | setDescription(String description) |
| `Status` | `String` | Required | Status | String getStatus() | setStatus(String status) |
| `CreatedAt` | `String` | Required | Creation date | String getCreatedAt() | setCreatedAt(String createdAt) |
| `UpdatedAt` | `String` | Required | Updated date | String getUpdatedAt() | setUpdatedAt(String updatedAt) |
| `Address` | [`GetAddressResponse`](/doc/models/get-address-response.md) | Required | Address | GetAddressResponse getAddress() | setAddress(GetAddressResponse address) |
| `Metadata` | `Map<String, String>` | Required | Metadata | Map<String, String> getMetadata() | setMetadata(Map<String, String> metadata) |
| `DeletedAt` | `String` | Optional | Deleted date | String getDeletedAt() | setDeletedAt(String deletedAt) |

## Example (as JSON)

```json
{
  "id": "id0",
  "name": "name0",
  "code": "code8",
  "document": "document6",
  "description": "description0",
  "Status": "Status8",
  "CreatedAt": "CreatedAt2",
  "UpdatedAt": "UpdatedAt6",
  "Address": {
    "id": "id8",
    "street": "street8",
    "number": "number6",
    "complement": "complement4",
    "zip_code": "zip_code2",
    "neighborhood": "neighborhood4",
    "city": "city8",
    "state": "state4",
    "country": "country2",
    "status": "status0",
    "created_at": "2016-03-13T12:52:32.123Z",
    "updated_at": "2016-03-13T12:52:32.123Z",
    "customer": null,
    "metadata": {
      "key0": "metadata5",
      "key1": "metadata4"
    },
    "line_1": "line_12",
    "line_2": "line_26",
    "deleted_at": null
  },
  "Metadata": {
    "key0": "Metadata2",
    "key1": "Metadata3"
  },
  "DeletedAt": null
}
```

