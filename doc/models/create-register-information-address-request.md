
# Create Register Information Address Request

Register Information Address

## Structure

`CreateRegisterInformationAddressRequest`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Street` | `String` | Required | - | String getStreet() | setStreet(String street) |
| `Complementary` | `String` | Required | - | String getComplementary() | setComplementary(String complementary) |
| `StreetNumber` | `String` | Required | - | String getStreetNumber() | setStreetNumber(String streetNumber) |
| `Neighborhood` | `String` | Required | - | String getNeighborhood() | setNeighborhood(String neighborhood) |
| `City` | `String` | Required | - | String getCity() | setCity(String city) |
| `State` | `String` | Required | - | String getState() | setState(String state) |
| `ZipCode` | `String` | Required | - | String getZipCode() | setZipCode(String zipCode) |
| `ReferencePoint` | `String` | Required | - | String getReferencePoint() | setReferencePoint(String referencePoint) |

## Example (as JSON)

```json
{
  "street": "street8",
  "complementary": "complementary0",
  "street_number": "street_number8",
  "neighborhood": "neighborhood4",
  "city": "city8",
  "state": "state4",
  "zip_code": "zip_code2",
  "reference_point": "reference_point2"
}
```

