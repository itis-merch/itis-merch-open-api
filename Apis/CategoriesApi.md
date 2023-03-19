# CategoriesApi

All URIs are relative to *http://localhost:8080/api/v1*

| Method | HTTP request | Description |
|------------- | ------------- | -------------|
| [**createCategory**](CategoriesApi.md#createCategory) | **POST** /categories | Метод создания новой категории. |
| [**getCategories**](CategoriesApi.md#getCategories) | **GET** /categories | Метод получения всех категорий. |
| [**getCategoryById**](CategoriesApi.md#getCategoryById) | **GET** /categories/{category_id} | Метод получения категории по идентификатору. |
| [**updateCategoryById**](CategoriesApi.md#updateCategoryById) | **POST** /categories/{category_id} | Метод изменения / обновления существующей категории. |


<a name="createCategory"></a>
# **createCategory**
> ApiResponse createCategory(Category)

Метод создания новой категории.

    Создает новую категорию.

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **Category** | [**Category**](../Models/Category.md)|  | |

### Return type

[**ApiResponse**](../Models/ApiResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

<a name="getCategories"></a>
# **getCategories**
> List getCategories()

Метод получения всех категорий.

    Возвращает массив всех категорий.

### Parameters
This endpoint does not need any parameter.

### Return type

[**List**](../Models/Category.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="getCategoryById"></a>
# **getCategoryById**
> Category getCategoryById(category\_id)

Метод получения категории по идентификатору.

    Возвращает категории по ее идентификатору.

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **category\_id** | **Integer**| Идентификатор категории | [default to null] |

### Return type

[**Category**](../Models/Category.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="updateCategoryById"></a>
# **updateCategoryById**
> ApiResponse updateCategoryById(category\_id, Category)

Метод изменения / обновления существующей категории.

    Обновляет существующую категорию по ее идентификатору, меняф некоторые ее свойства.

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **category\_id** | **Integer**| Идентификатор категории | [default to null] |
| **Category** | [**Category**](../Models/Category.md)|  | |

### Return type

[**ApiResponse**](../Models/ApiResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

