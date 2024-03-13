
# Get Movement Object Settlement Response

Generic response object for getting a MovementObjectSettlement.

## Structure

`GetMovementObjectSettlementResponse`

## Inherits From

[`GetMovementObjectBaseResponse`](../../doc/models/get-movement-object-base-response.md)

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Product` | `String` | Optional | - | String getProduct() | setProduct(String product) |
| `Brand` | `String` | Optional | - | String getBrand() | setBrand(String brand) |
| `PaymentDate` | `String` | Optional | - | String getPaymentDate() | setPaymentDate(String paymentDate) |
| `RecipientId` | `String` | Optional | - | String getRecipientId() | setRecipientId(String recipientId) |
| `DocumentType` | `String` | Optional | - | String getDocumentType() | setDocumentType(String documentType) |
| `Document` | `String` | Optional | - | String getDocument() | setDocument(String document) |
| `ContractObligationId` | `String` | Optional | - | String getContractObligationId() | setContractObligationId(String contractObligationId) |
| `LiquidationArrangementId` | `String` | Optional | - | String getLiquidationArrangementId() | setLiquidationArrangementId(String liquidationArrangementId) |
| `ExternalEnginePaymentId` | `String` | Optional | - | String getExternalEnginePaymentId() | setExternalEnginePaymentId(String externalEnginePaymentId) |

## Example (as JSON)

```json
{
  "id": "id2",
  "status": "status4",
  "amount": "amount4",
  "created_at": "created_at0",
  "product": "product2",
  "brand": "brand6",
  "payment_date": "payment_date4",
  "recipient_id": "recipient_id2",
  "document_type": "document_type0"
}
```

