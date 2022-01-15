# Number-library-converter
Convert values between break eternity, OmegaNum and ExpantaNum number libraries.
this repository includes these number lobraries already.
you can't convert single value like 
```js 

new Decimal(100)
```
or objects and arrays like 
```js 
var x = {
1: new Decimal(10),
2: [new Decimal(100), new Decimal(1000)]
   }
   ```
Type 
```js 
convert(value, newNumberLibrary
```
to convert. value is a variable/object/array you want to convert.
newNumberLibrary is Decimal/OmegaNum/ExpantaNum.
you need to have bteak_eternity.js, OmegaNum.js, and ExpantaNum.js code in your projrct for this to work.


 
 
