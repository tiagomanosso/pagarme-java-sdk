
# Create Google Pay Request

The GooglePay Token Payment Request

## Structure

`CreateGooglePayRequest`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `Version` | `String` | Optional | Informação sobre a versão do token. Único valor aceito é EC_v2 | String getVersion() | setVersion(String version) |
| `Data` | `String` | Optional | Dados de pagamento criptografados. Corresponde ao encryptedMessage do token Google. | String getData() | setData(String data) |
| `IntermediateSigningKey` | [`CreateGooglePayIntermediateSigningKeyRequest`](../../doc/models/create-google-pay-intermediate-signing-key-request.md) | Optional | The GooglePay intermediate signing key request | CreateGooglePayIntermediateSigningKeyRequest getIntermediateSigningKey() | setIntermediateSigningKey(CreateGooglePayIntermediateSigningKeyRequest intermediateSigningKey) |
| `Signature` | `String` | Optional | Assinatura dos dados de pagamento. Verifica se a origem da mensagem é o Google. Corresponde ao signature do token Google. | String getSignature() | setSignature(String signature) |
| `SignedMessage` | `String` | Optional | - | String getSignedMessage() | setSignedMessage(String signedMessage) |
| `MerchantIdentifier` | `String` | Optional | - | String getMerchantIdentifier() | setMerchantIdentifier(String merchantIdentifier) |

## Example (as JSON)

```json
{
  "version": "version6",
  "data": "data0",
  "intermediate_signing_key": {
    "signed_key": "signed_key0",
    "signatures": [
      "signatures2",
      "signatures3",
      "signatures4"
    ]
  },
  "signature": "signature8",
  "signed_message": "signed_message6"
}
```

