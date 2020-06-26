### Code JS 8 kyu

* [Fuel Calculator](https://www.codewars.com/kata/57b58827d2a31c57720012e8/train/javascript)
```javascript
function fuelPrice(litres, pricePerLiter) {
  for (let i = 2; i <= 10; i +=2) {
    if (litres >= i) {
      pricePerLiter -= 0.05;
    }
  }
  return Math.round(litres * pricePerLiter * 100) / 100;
}
```


* [Holiday VI - Shark Pontoon](https://www.codewars.com/kata/57e921d8b36340f1fd000059/train/javascript)
```javascript
function shark(pontoonDistance, sharkDistance, youSpeed, sharkSpeed, dolphin){

  sharkSpeed = dolphin ? sharkSpeed/2 : sharkSpeed

  return pontoonDistance/youSpeed <= sharkDistance/sharkSpeed ? 'Alive!' : 'Shark Bait!'
}
```


* [Area or Perimeter](https://www.codewars.com/kata/5ab6538b379d20ad880000ab/train/javascript)
```javascript
const areaOrPerimeter = function(l , w) {
  return l == w? Math.pow(l,2) : l*2 + w*2; 
};
```



