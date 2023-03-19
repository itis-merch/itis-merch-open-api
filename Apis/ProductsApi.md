# ProductsApi

All URIs are relative to *http://localhost:8080/api/v1*

| Method | HTTP request | Description |
|------------- | ------------- | -------------|
| [**createProduct**](ProductsApi.md#createProduct) | **POST** /products | Метод создания нового продукта. |
| [**getProductById**](ProductsApi.md#getProductById) | **GET** /products/{product_id} | Метод получения продукта по идентификатору. |
| [**getProductsFromAllCategories**](ProductsApi.md#getProductsFromAllCategories) | **GET** /products | Метод получения продуктов всех категорий. |
| [**updateProductById**](ProductsApi.md#updateProductById) | **POST** /products/{product_id} | Метод изменения / обновления существующего продукта. |


<a name="createProduct"></a>
# **createProduct**
> ApiResponse createProduct(Product)

Метод создания нового продукта.

    Создает новый продукт.

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **Product** | [**Product**](../Models/Product.md)|  | |

### Return type

[**ApiResponse**](../Models/ApiResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

<a name="getProductById"></a>
# **getProductById**
> Product getProductById(product\_id)

Метод получения продукта по идентификатору.

    Возвращает продукт по его идентификатору.

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **product\_id** | **Integer**| Идентификатор продукта | [default to null] |

### Return type

[**Product**](../Models/Product.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="getProductsFromAllCategories"></a>
# **getProductsFromAllCategories**
> List getProductsFromAllCategories()

Метод получения продуктов всех категорий.

    Возвращает массив всех продуктов независимо от принадлежности к конкретной категории.

### Parameters
This endpoint does not need any parameter.

### Return type

[**List**](../Models/Product.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="updateProductById"></a>
# **updateProductById**
> ApiResponse updateProductById(product\_id, Product)

Метод изменения / обновления существующего продукта.

    Обновляет существующий продукт по его идентификатору, меня некоторые его свойства.

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **product\_id** | **Integer**| Идентификатор продукта | [default to null] |
| **Product** | [**Product**](../Models/Product.md)|  | |

### Return type

[**ApiResponse**](../Models/ApiResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

