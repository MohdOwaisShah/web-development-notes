# Type Script
### 1. Typescript is a advance version of javascript

* `javascript made in 10 days thats why there is some problems:`

<strong>- redeclaration the same variable </strong>

```javascript
var a = 10
var a = 12
// this will show error in another language
```

* `2nd example:`
```javascript
// this is also works in js
var a = 10
a = 'owais'
```
* `etc..`
* `In typescript it is providing a layer in js like its advance version where these types of things is not working and TS also provides more features.`


###  2. Data types

<ol>
<li>premitive</li>
<li>non-premitive</li>
<li>refrence</li>
</ol>

<strong>note: every three bracets are refrence that effects on parent </strong> 

* `example:`
```javascript
  let a = [1,2,3,4,5];
  let b = a;
  b.pop() // this will effect on variable (a) too.
  console.log(a, b)
```