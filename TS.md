# Type Script
### 1. Typescript is a advance version of javascript

<strong>javascript made in 10 days thats why there is some problems: </strong>

* `- redeclaration the same variable:`

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


<details>
<summary>Primitive</summary>

<p>there are 7 primitive data types: </p>

* `1. String`
* `2. Number`
* `3. Bolean`
* `4. Null`
* `5. Undefined`
* `6. Symbol`
* `7. BigInt`
</details>

<details>
<summary>Non-primitive or refrence (both are not same in some cases)</summary>
<strong>note: every three bracets are refrence that effects on parent <b>() {} [] <b> </strong> 

* `example:`
```javascript
  let a = [1,2,3,4,5];
  let b = a;
  b.pop() // this will effect on variable (a) too.
  console.log(a, b)
```
</details>

###  3. Tuples
<strong>We are declaring the tuples like this:</strong>

*`Using tuple we have full control`

```javascript
// using []
let user: [string, number] = ["Owais", 20]; // A name and an age
```

*`If the value is not matching the types it gives error`

```javascript
// ❌ it gives error
let user: [string, number] = [20, "Owais"]; 
let user: [string, number] = ["Owais", "Owais"]; // A name and an age
```
