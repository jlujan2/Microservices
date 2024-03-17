# Microservices E-Commerce

Basic E-Commerce backend using Java, Spring Boot, MongDB, PostGres, KeyCloak, microservices principals.




## Deployment

To deploy this project run

```bash
  docker-compose up
```
## Endpoints
Get available Products
```bash
  http://localhost:8081/api/product
```

Make an Order
```bash
  http://localhost:8181/api/order
  {
    "orderLineItemsDtoList":[
        {
            "skuCode":"iphone_13",
            "price":1200,
            "quantity":1
        }
    ]
}
```
