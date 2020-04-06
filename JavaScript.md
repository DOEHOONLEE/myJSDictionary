# myJSDictionary


## QUICK VIEW


 #### convert to string  
```js
const val = 21 + ""; // -> "21"; typeof val -> "string";
```

 #### filter unique values
```js
const arr = [1, 2, 2, 4, 7, 2, 1];
const uni = [...new Set(array)]; // -> uni = [1, 2, 4, 7];
const unique = arr.filter((v, i, a) => a.indexOf(v) === i); // -> unique = [1, 2, 4, 7];
```


 #### methods 

| methods | Description | Returns | Argument
| --- | --- | --- | --- |
| `every()` | EVERY item has to pass the test | TRUE/FALSE | 
| `some()` | SOME item has to pass the test | TRUE/FALSE | `function`
| `includes()` | checks if the array has certain string | TRUE/FALSE | `string`
| `filter()` | check for elements that pass the test | `new array` | 
| `map()` | similar to filter(), but modifies items | `new array`| 


 ### 


***
## **E_**

(1) every()
```js
// every() method goes through an array and returns TRUE if ALL items pass the test or FALSE if not.
// EVERY ITEM has to pass the test
  // ex. var IQ = [99, 105, 138, 89]; or const IQ = [99, 105, 138, 89];
IQ.every(function(intelligence) {
  return intelligence >= 100;
})
// false
// ES6
IQ.every(intelligence => intelligence >= 75);
// true
```

***
## **F_**

(1) filter()
```js
// filter() returns a new array with elements that pass the certain condition
  // ex. return a new array with integers only
filter_list function(l) {
  l.filter(function(c) {
    return (typeof c == "number");
  })
}
// ES6
const filter_list = l => l.filter(c => (typeof c == "number"));
```
***
## **P_**

(1) power a number
```js
Math.pow(base, exponent)
```
***
## **R_**

(1) replace()
```js
// remove commas
replace(/,/g, "")
```

(2) reverse()
```js
// this method reverses the order of elements in the array - original array affected
const IQ = [99, 105, 138, 89];
const.reverse(); // IQ = [89, 138, 105, 99];
```
***
## **S_**

(1) some()

```js
// checks if some elements are in the array and returns TRUE/FALSE - similar to `incldues()`
  // ex. var IQ = [99, 105, 138, 89]; or const IQ = [99, 105, 138, 89];
const IQ = [99, 105, 138, 89];
IQ.some(pass => pass > 100);
// true
```

(2) sort()

```js
// sorts items in the array -> can be alphabetical or numerical + ascending/descending - original array affected
const IQ = [99, 105, 138, 89];
IQ.sort((a,b) => a-b); // 89, 99, 105, 138
IQ.sort((a,b) => b-a); // 138, 105, 99, 89
```
