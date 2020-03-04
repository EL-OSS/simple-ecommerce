# simple-ecommerce
Simple e-commerce boilerplate with JS and React

## Some parameters to use immediately:

### TOTAL PRODUCTS
> Line 240
```
/*======
IF < 20 PRODUCTS, ENTER THE AMOUNT. 	(eg 0 - 19)
IF > 20 PRODUCTS, PUT ANY NUMBER > 20. 	(eg 20 ...)
 ======*/
var totalProducts=21;
```

### PRODUCTS LIST
> Line 242 - 412 in following JSON format
```
var products = [{
  "title":"",
  "desc":"",
  "categ":"",
  "price":,
  "adver":"",
  "pic":"",
  "ref":""
}];
```

### TOTAL PRODUCTS
> Line 446 - 467
```
if(totalProducts >=20) {
}
else {
```

### HOW MANY "LOAD MORE" PRODUCTS
> Line 474 - 477
```
_this.state= {
index: 1, placeholder: productArray, itemPerPage: 10, products: products, value: "Sort"
}
```
