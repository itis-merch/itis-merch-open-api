# CartOrder

## Description
Модель корзина-заказ. У каждого пользователя может быть только одна такая модель, помеченная как корзина. После оформления заказа модель меняет свой статус и становится заказом. В этот момент создается новая сущность cart_order, помеченная как корзина.

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
| **id** | **Integer** |  | [default to null] |
| **user\_id** | **Integer** |  | [default to null] |
| **item\_id** | **Integer** |  | [default to null] |
| **total\_price** | **BigDecimal** |  | [default to null] |
| **status** | **String** |  | [default to null] |

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

