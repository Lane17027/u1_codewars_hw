## Return Negative

function makeNegative(num){
    if(num<=0){
        return num
    }
    else return num/-1
}

## Sum of Positive

nums = [1, 2, 5, -7, -8, 10];

function sumOfPositive(nums) {
  let sum = 0;
  for (let num of nums) {
    if (num >= 1) {
      sum += num;
    }
  }
  return sum;
}

## Function 2

function squaringAnArgument(num) {
  return num ** 2;
}

## Sum Arrays

function sumArrays(numbers) {
  let sum = 0;
  if (numbers.length == 0) {
    return sum;
  } else {
    for (let num of numbers) {
      sum += num;
    }
  }
  return sum;
}

## Reversed Strings

function reversed(string){
    let arr=string.split('')
    return arr.reverse().join('')
}
