# Sellers

```java
SellersController sellersController = client.getSellersController();
```

## Class Name

`SellersController`

## Methods

* [Create Seller](/doc/controllers/sellers.md#create-seller)
* [Update Seller Metadata](/doc/controllers/sellers.md#update-seller-metadata)
* [Update Seller](/doc/controllers/sellers.md#update-seller)
* [Delete Seller](/doc/controllers/sellers.md#delete-seller)
* [Get Seller by Id](/doc/controllers/sellers.md#get-seller-by-id)
* [Get Sellers](/doc/controllers/sellers.md#get-sellers)


# Create Seller

```java
CompletableFuture<GetSellerResponse> createSeller(
    final CreateSellerRequest request,
    final String idempotencyKey)
```

## Parameters

| Parameter | Type | Tags | Description |
|  --- | --- | --- | --- |
| `request` | [`CreateSellerRequest`](/doc/models/create-seller-request.md) | Body, Required | Seller Model |
| `idempotencyKey` | `String` | Header, Optional | - |

## Response Type

[`GetSellerResponse`](/doc/models/get-seller-response.md)

## Example Usage

```java
CreateSellerRequest request = new CreateSellerRequest();
request.setName("name6");
request.setMetadata(new LinkedHashMap<>());
request.getMetadata().put("key0", "metadata3");

try {
    GetSellerResponse response = sellersController.createSeller(request, null);
} catch (ApiException e) {
    e.printStackTrace();
} catch (IOException e) {
    e.printStackTrace();
}
```


# Update Seller Metadata

```java
CompletableFuture<GetSellerResponse> updateSellerMetadata(
    final String sellerId,
    final UpdateMetadataRequest request,
    final String idempotencyKey)
```

## Parameters

| Parameter | Type | Tags | Description |
|  --- | --- | --- | --- |
| `sellerId` | `String` | Template, Required | Seller Id |
| `request` | [`UpdateMetadataRequest`](/doc/models/update-metadata-request.md) | Body, Required | Request for updating the charge metadata |
| `idempotencyKey` | `String` | Header, Optional | - |

## Response Type

[`GetSellerResponse`](/doc/models/get-seller-response.md)

## Example Usage

```java
String sellerId = "seller_id8";
UpdateMetadataRequest request = new UpdateMetadataRequest();
request.setMetadata(new LinkedHashMap<>());
request.getMetadata().put("key0", "metadata3");

try {
    GetSellerResponse response = sellersController.updateSellerMetadata(sellerId, request, null);
} catch (ApiException e) {
    e.printStackTrace();
} catch (IOException e) {
    e.printStackTrace();
}
```


# Update Seller

```java
CompletableFuture<GetSellerResponse> updateSeller(
    final String id,
    final UpdateSellerRequest request,
    final String idempotencyKey)
```

## Parameters

| Parameter | Type | Tags | Description |
|  --- | --- | --- | --- |
| `id` | `String` | Template, Required | - |
| `request` | [`UpdateSellerRequest`](/doc/models/update-seller-request.md) | Body, Required | Update Seller model |
| `idempotencyKey` | `String` | Header, Optional | - |

## Response Type

[`GetSellerResponse`](/doc/models/get-seller-response.md)

## Example Usage

```java
String id = "id0";
UpdateSellerRequest request = new UpdateSellerRequest();
request.setName("name6");
request.setCode("code4");
request.setDescription("description6");
request.setDocument("document0");
request.setStatus("status8");
request.setType("type4");
request.setAddress(new CreateAddressRequest());
request.getAddress().setStreet("street2");
request.getAddress().setNumber("number0");
request.getAddress().setZipCode("zip_code6");
request.getAddress().setNeighborhood("neighborhood8");
request.getAddress().setCity("city2");
request.getAddress().setState("state8");
request.getAddress().setCountry("country6");
request.getAddress().setComplement("complement8");
request.getAddress().setMetadata(new LinkedHashMap<>());
request.getAddress().getMetadata().put("key0", "metadata7");
request.getAddress().setLine1("line_16");
request.getAddress().setLine2("line_20");
request.setMetadata(new LinkedHashMap<>());
request.getMetadata().put("key0", "metadata3");

try {
    GetSellerResponse response = sellersController.updateSeller(id, request, null);
} catch (ApiException e) {
    e.printStackTrace();
} catch (IOException e) {
    e.printStackTrace();
}
```


# Delete Seller

```java
CompletableFuture<GetSellerResponse> deleteSeller(
    final String sellerId,
    final String idempotencyKey)
```

## Parameters

| Parameter | Type | Tags | Description |
|  --- | --- | --- | --- |
| `sellerId` | `String` | Template, Required | Seller Id |
| `idempotencyKey` | `String` | Header, Optional | - |

## Response Type

[`GetSellerResponse`](/doc/models/get-seller-response.md)

## Example Usage

```java
String sellerId = "sellerId4";

try {
    GetSellerResponse response = sellersController.deleteSeller(sellerId, null);
} catch (ApiException e) {
    e.printStackTrace();
} catch (IOException e) {
    e.printStackTrace();
}
```


# Get Seller by Id

```java
CompletableFuture<GetSellerResponse> getSellerById(
    final String id)
```

## Parameters

| Parameter | Type | Tags | Description |
|  --- | --- | --- | --- |
| `id` | `String` | Template, Required | Seller Id |

## Response Type

[`GetSellerResponse`](/doc/models/get-seller-response.md)

## Example Usage

```java
String id = "id0";

try {
    GetSellerResponse response = sellersController.getSellerById(id);
} catch (ApiException e) {
    e.printStackTrace();
} catch (IOException e) {
    e.printStackTrace();
}
```


# Get Sellers

```java
CompletableFuture<ListSellerResponse> getSellers(
    final Integer page,
    final Integer size,
    final String name,
    final String document,
    final String code,
    final String status,
    final String type,
    final LocalDateTime createdSince,
    final LocalDateTime createdUntil)
```

## Parameters

| Parameter | Type | Tags | Description |
|  --- | --- | --- | --- |
| `page` | `Integer` | Query, Optional | Page number |
| `size` | `Integer` | Query, Optional | Page size |
| `name` | `String` | Query, Optional | - |
| `document` | `String` | Query, Optional | - |
| `code` | `String` | Query, Optional | - |
| `status` | `String` | Query, Optional | - |
| `type` | `String` | Query, Optional | - |
| `createdSince` | `LocalDateTime` | Query, Optional | - |
| `createdUntil` | `LocalDateTime` | Query, Optional | - |

## Response Type

[`ListSellerResponse`](/doc/models/list-seller-response.md)

## Example Usage

```java
try {
    ListSellerResponse response = sellersController.getSellers(null, null, null, null, null, null, null, null, null);
} catch (ApiException e) {
    e.printStackTrace();
} catch (IOException e) {
    e.printStackTrace();
}
```

