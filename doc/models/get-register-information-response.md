
# Get Register Information Response

Response object for getting an RegisterInformationResponse

## Structure

`GetRegisterInformationResponse`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Email` | `String` | Optional | - | String getEmail() | setEmail(String email) |
| `Document` | `String` | Optional | - | String getDocument() | setDocument(String document) |
| `Type` | `String` | Optional | - | String getType() | setType(String type) |
| `SiteUrl` | `String` | Optional | - | String getSiteUrl() | setSiteUrl(String siteUrl) |
| `PhoneNumbers` | [`List<GetPhoneNumberResponse>`](../../doc/models/get-phone-number-response.md) | Optional | - | List<GetPhoneNumberResponse> getPhoneNumbers() | setPhoneNumbers(List<GetPhoneNumberResponse> phoneNumbers) |
| `Name` | `String` | Optional | - | String getName() | setName(String name) |
| `MotherName` | `String` | Optional | - | String getMotherName() | setMotherName(String motherName) |
| `Birthdate` | `String` | Optional | - | String getBirthdate() | setBirthdate(String birthdate) |
| `MonthlyIncome` | `String` | Optional | - | String getMonthlyIncome() | setMonthlyIncome(String monthlyIncome) |
| `ProfessionalOccupation` | `String` | Optional | - | String getProfessionalOccupation() | setProfessionalOccupation(String professionalOccupation) |
| `Address` | [`GetRegisterInformationAddressResponse`](../../doc/models/get-register-information-address-response.md) | Optional | - | GetRegisterInformationAddressResponse getAddress() | setAddress(GetRegisterInformationAddressResponse address) |
| `CompanyName` | `String` | Optional | - | String getCompanyName() | setCompanyName(String companyName) |
| `TradingName` | `String` | Optional | - | String getTradingName() | setTradingName(String tradingName) |
| `AnnualRevenue` | `String` | Optional | - | String getAnnualRevenue() | setAnnualRevenue(String annualRevenue) |
| `CorporationType` | `String` | Optional | - | String getCorporationType() | setCorporationType(String corporationType) |
| `FoundingDate` | `String` | Optional | - | String getFoundingDate() | setFoundingDate(String foundingDate) |
| `Cnae` | `String` | Optional | - | String getCnae() | setCnae(String cnae) |
| `MainAddress` | [`GetRegisterInformationAddressResponse`](../../doc/models/get-register-information-address-response.md) | Optional | - | GetRegisterInformationAddressResponse getMainAddress() | setMainAddress(GetRegisterInformationAddressResponse mainAddress) |
| `ManagingPartners` | [`List<GetManagingPartnerResponse>`](../../doc/models/get-managing-partner-response.md) | Optional | - | List<GetManagingPartnerResponse> getManagingPartners() | setManagingPartners(List<GetManagingPartnerResponse> managingPartners) |

## Example (as JSON)

```json
{
  "email": "email2",
  "document": "document2",
  "type": "type6",
  "site_url": "site_url6",
  "phone_numbers": [
    {
      "ddd": "ddd4",
      "number": "number2",
      "type": "type0"
    },
    {
      "ddd": "ddd4",
      "number": "number2",
      "type": "type0"
    }
  ]
}
```

