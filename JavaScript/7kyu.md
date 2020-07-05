### Code JS 7 kyu

* [lucky number](https://www.codewars.com/kata/55afed09237df73343000042/train/javascript)

```javascript
function isLucky(n) {
return n % 9==0;
};
```

* [Return the closest number multiple of 10](https://www.codewars.com/kata/58249d08b81f70a2fc0001a4/train/javascript)

```javascript
const closestMultiple10 = num => {
    let x = Math.round(num/10);
    return ((x).toFixed(1) * 10);
};
```

* [How many times should I go?](https://www.codewars.com/kata/57efcb78e77282f4790003d8/train/javascript)
```javascript
function howManyTimes(annualPrice, individualPrice) {
    return  Math.ceil(annualPrice / individualPrice);
  };
```

*[Basic Calculator](https://www.codewars.com/kata/5296455e4fe0cdf2e000059f/train/javascript)
```javascript
function calculate(num1, operation, num2) {
  if (num1 == 0 || num2 == 0 && operation == '/' ) return null;
 switch (operation) {
  case '+': return (num1 + num2); 
  break;
  case '-': return (num1 - num2); 
  break;
  case '*': return (num1 * num2); 
  break;
  case '/': return (num1 / num2); 
  break;  
  default: return null; 
}
}
```


*[Calculate Two People's Individual Ages](https://www.codewars.com/kata/58e0bd6a79716b7fcf0013b1/train/javascript)
```javascript
function getAges(sum,difference){
if (difference<0||sum<0) return null;
   sum=sum/2
   difference/=2
   if (sum+difference<0||sum-difference<0) return null;
   return [sum+difference,sum-difference]
}
```

*[Breaking chocolate problem](https://www.codewars.com/kata/534ea96ebb17181947000ada/train/javascript)
```javascript
function breakChocolate(n,m) { 
 return n == 0 || m == 0 || n == 1 && m == 1 ? 0 : n*m-1  
}
```

*[Sum of angles](https://www.codewars.com/kata/5a03b3f6a1c9040084001765/train/javascript)
```javascript
function angle(n) {
  return 180*(n-2);
}
```




