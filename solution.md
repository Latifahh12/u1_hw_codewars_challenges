## Return Negative\

```js
function makeNegative(num) {
  if (num <= 0) {
    return num
  } else {
    return -Math.abs(num)
  }
}
```

## Sum of Positive

```js
function positiveSum(arr) {
  let sum = 0
  arr.forEach((num) => num > 0 && (sum += num))
  return sum
}
```

## Function 2

```js
square = (arg) => arg ** 2
```

## Sum Arrays

```js
sum = (numbers) => numbers.reduce((actual, expected) => actual + expected, 0)
//This solution gave me errors but when the test were ran it did return back [10, -65] in terminal. I did look up the solution but i wanted to include my code of what was giving me back errors.
```

## Reversed Strings

```js
function solution(str) {
    let answer = []
    for(let i = 0; i < str.length; i++) {
        answer.unshift(str[i])
    }
    return answer.join('')
}
// I answered the question for a simple string reversal no valid answer so here was my solution 
```
