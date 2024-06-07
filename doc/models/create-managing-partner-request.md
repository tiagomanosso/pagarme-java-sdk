
# Create Managing Partner Request

Managing Partner Request

## Structure

`CreateManagingPartnerRequest`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Name` | `String` | Required | - | String getName() | setName(String name) |
| `Email` | `String` | Required | - | String getEmail() | setEmail(String email) |
| `Document` | `String` | Required | - | String getDocument() | setDocument(String document) |
| `MotherName` | `String` | Optional | - | String getMotherName() | setMotherName(String motherName) |
| `Birthdate` | `String` | Required | - | String getBirthdate() | setBirthdate(String birthdate) |
| `MonthlyIncome` | `int` | Required | - | int getMonthlyIncome() | setMonthlyIncome(int monthlyIncome) |
| `ProfessionalOccupation` | `String` | Required | - | String getProfessionalOccupation() | setProfessionalOccupation(String professionalOccupation) |
| `SelfDeclaredLegalRepresentative` | `boolean` | Required | - | boolean getSelfDeclaredLegalRepresentative() | setSelfDeclaredLegalRepresentative(boolean selfDeclaredLegalRepresentative) |
| `Address` | [`CreateRegisterInformationAddressRequest`](../../doc/models/create-register-information-address-request.md) | Required | - | CreateRegisterInformationAddressRequest getAddress() | setAddress(CreateRegisterInformationAddressRequest address) |
| `PhoneNumbers` | [`List<CreateRegisterInformationPhoneRequest>`](../../doc/models/create-register-information-phone-request.md) | Required | - | List<CreateRegisterInformationPhoneRequest> getPhoneNumbers() | setPhoneNumbers(List<CreateRegisterInformationPhoneRequest> phoneNumbers) |

## Example (as JSON)

```json
{
  "name": "name4",
  "email": "email2",
  "document": "document2",
  "birthdate": "birthdate8",
  "monthly_income": 70,
  "professional_occupation": "professional_occupation8",
  "self_declared_legal_representative": false,
  "address": {
    "street": "street6",
    "complementary": "complementary8",
    "street_number": "street_number6",
    "neighborhood": "neighborhood2",
    "city": "city6",
    "state": "state2",
    "zip_code": "zip_code0",
    "reference_point": "reference_point0"
  },
  "phone_numbers": [
    {
      "ddd": "ddd4",
      "number": "number2",
      "type": "type0"
    }
  ],
  "mother_name": "mother_name0"
}
```

