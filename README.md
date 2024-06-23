# playing-with-java-microservices-monolith-example
Monolith sample code for Amazon Q Monolith to Microservices (Containers)

# Code Structure

```
src/
└── main
    ├── java
    │   └── com
    │       └── targa
    │           └── labs
    │               └── myboutique
    │                   ├── MyboutiqueApplication.java
    │                   ├── common
    │                   │   └── Web.java
    │                   ├── configuration
    │                   │   └── SwaggerConfiguration.java
    │                   ├── domain
    │                   │   ├── AbstractEntity.java
    │                   │   ├── Address.java
    │                   │   ├── Cart.java
    │                   │   ├── Category.java
    │                   │   ├── Customer.java
    │                   │   ├── Order.java
    │                   │   ├── OrderItem.java
    │                   │   ├── Payment.java
    │                   │   ├── Product.java
    │                   │   ├── Review.java
    │                   │   └── enumeration
    │                   │       ├── CartStatus.java
    │                   │       ├── OrderStatus.java
    │                   │       ├── PaymentStatus.java
    │                   │       └── ProductStatus.java
    │                   ├── repository
    │                   │   ├── CartRepository.java
    │                   │   ├── CategoryRepository.java
    │                   │   ├── CustomerRepository.java
    │                   │   ├── OrderItemRepository.java
    │                   │   ├── OrderRepository.java
    │                   │   ├── PaymentRepository.java
    │                   │   ├── ProductRepository.java
    │                   │   └── ReviewRepository.java
    │                   ├── service
    │                   │   ├── AddressService.java
    │                   │   ├── CartService.java
    │                   │   ├── CategoryService.java
    │                   │   ├── CustomerService.java
    │                   │   ├── OrderItemService.java
    │                   │   ├── OrderService.java
    │                   │   ├── PaymentService.java
    │                   │   ├── ProductService.java
    │                   │   └── ReviewService.java
    │                   └── web
    │                       ├── CartResource.java
    │                       ├── CategoryResource.java
    │                       ├── CustomerResource.java
    │                       ├── OrderItemResource.java
    │                       ├── OrderResource.java
    │                       ├── PaymentResource.java
    │                       ├── ProductResource.java
    │                       ├── ReviewResource.java
    │                       └── dto
    │                           ├── AddressDto.java
    │                           ├── CartDto.java
    │                           ├── CategoryDto.java
    │                           ├── CustomerDto.java
    │                           ├── OrderDto.java
    │                           ├── OrderItemDto.java
    │                           ├── PaymentDto.java
    │                           ├── ProductDto.java
    │                           └── ReviewDto.java
    └── resources
        ├── application.properties
        └── db
            └── migration
                └── V1__init_app.sql
```
