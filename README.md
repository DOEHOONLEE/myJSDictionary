# myJSDictionary

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
***
## **S_**

(1) some()
```js

```
