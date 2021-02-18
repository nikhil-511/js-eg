# js-eg

### Functions

Functions without parameters
```javascript 
function addition(){
    var a=5
    var b=6
    return a+b;
}

addition()
```

Functions with parameters

```javascript
function addition(a,b){
    return a+b 
}

addition(1,2)

```

Function with no name/ anonymous function

```javascript
var sub=function(a,b){
    return a-b 
}

sub(1,2)
```

Function without name and functoin keyword/ Arrow function
```javascript
var mul=(a,b)=>{
    return (a*b)
}

mul(2,3)
```

Function using map
```javascript
var arr=[1,2,3,4,5,6]

arr.map(function(i){
    console.log(i)
})
```
###Higher Order Functions (HDF)
*A function that accepts another functions as an argument.*

```javascript
arr.map((item,index)=>{
   console.log(item+"is having index of : "+index)
})
```
