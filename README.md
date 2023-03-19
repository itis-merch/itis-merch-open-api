# Документация Itis.Merch OpenAPI спецификация

![](https://img.shields.io/badge/api-v0.0.1-green?style=flat-square)

Это документация к Itis Merch OpenAPI. Пока она еще находится в разработке и с точки зрения проектирования, и с точки зрения документации.

На данный момент вся документация генерируется с помощью [openapi-generator](https://github.com/OpenAPITools/openapi-generator/tree/master).

All URIs are relative to *http://localhost:8080/api/v1*

| Class | Method | HTTP request | Description |
|------------ | ------------- | ------------- | -------------|
| *CategoriesApi* | [**createCategory**](Apis/CategoriesApi.md#createcategory) | **POST** /categories | Метод создания новой категории. |
*CategoriesApi* | [**getCategories**](Apis/CategoriesApi.md#getcategories) | **GET** /categories | Метод получения всех категорий. |
*CategoriesApi* | [**getCategoryById**](Apis/CategoriesApi.md#getcategorybyid) | **GET** /categories/{category_id} | Метод получения категории по идентификатору. |
*CategoriesApi* | [**updateCategoryById**](Apis/CategoriesApi.md#updatecategorybyid) | **POST** /categories/{category_id} | Метод изменения / обновления существующей категории. |
| *ProductsApi* | [**createProduct**](Apis/ProductsApi.md#createproduct) | **POST** /products | Метод создания нового продукта. |
*ProductsApi* | [**getProductById**](Apis/ProductsApi.md#getproductbyid) | **GET** /products/{product_id} | Метод получения продукта по идентификатору. |
*ProductsApi* | [**getProductsFromAllCategories**](Apis/ProductsApi.md#getproductsfromallcategories) | **GET** /products | Метод получения продуктов всех категорий. |
*ProductsApi* | [**updateProductById**](Apis/ProductsApi.md#updateproductbyid) | **POST** /products/{product_id} | Метод изменения / обновления существующего продукта. |


<a name="documentation-for-models"></a>
## Documentation for Models

 - [ApiResponse](./Models/ApiResponse.md)
 - [CartOrder](./Models/CartOrder.md)
 - [Category](./Models/Category.md)
 - [Option](./Models/Option.md)
 - [Product](./Models/Product.md)
 - [ShoppingCartItem](./Models/ShoppingCartItem.md)
 - [User](./Models/User.md)


<a name="documentation-for-authorization"></a>
## Documentation for Authorization

All endpoints do not require authorization.
