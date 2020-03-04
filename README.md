# simple-ecommerce
Simple e-commerce boilerplate with JS and React

![alt text](https://github.com/EL-OSS/simple-ecommerce/blob/master/simple-ecommerce-preview.png)

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

### HOW MANY PRODUCTS PER PAGE
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

## License
This project is licensed under the GNU License - see the LICENSE.md file for details
