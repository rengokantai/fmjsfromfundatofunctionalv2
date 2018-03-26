# fmjsfromfundatofunctionalv2

## Property Access
###### 11:46
rules:
- primitive type passed by value
- nonprimitive value passed by reference

dots vs brackets  


|Dots|Brackets|
|--- | ---|
|strings | strings|
|| numbers|
||variables|
|| weird characters|
|| expressions|



## List transformations
### Looping solution
```
const game = {
  'suspects':[
    {
      name:"rusty",
      color:"orange"
    },{
      name:"miss",
      color:"red"
    }
  ]
}
function foo(){
  for(let i=0;i<game.suspects.length;i++){
    console.log(game.suspects[i]);  //you cannot use game.suspects.i because i is a variable
  }
}
```
```
for(let p in obj) obj[prop]
```

