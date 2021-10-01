# E-Commerce-Using-Spring-Boot-Angular
A Simple E-Commerce Project using Spring Boot &amp; Angular

<h4> Functionalities Added : </h4>

* Rest API Support using Spring Boot to retrieve products, categories, products by categories
* View products and product by categories
* View a product detail
* Add & remove items in cart 

<h4> REST Api Links </h4>

- "productCategories" : "http://localhost:8080/api/productCategories{?page,size,sort,projection}"
- "products" : "http://localhost:8080/api/products{?page,size,sort,projection}"
  - "findBycategoryId" : "http://localhost:8080/api/products/search/findBycategoryId{?id,page,size,sort,projection}"
  -  "findByNameContaining" : "http://localhost:8080/api/products/search/findByNameContaining{?keyword,page,size,sort,projection}"
