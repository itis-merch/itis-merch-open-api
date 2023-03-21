# Itis.Merch OpenAPI спецификация

<a name="documentation-for-api-endpoints"></a>
## API Endpoints 


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
