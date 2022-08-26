# code_snippets
##List of basic JavaScript programs
### Find the Maximum number in the given Array
function maxNumber(arr) {
  let max = 0;
  for(let i = 0; i < arr.length; i++) {
    if(arr[i] > max)
      max = arr[i];
  }
     return max;
}
let arr = [3,5,0,1,20,6,17,30];
console.log(maxNumber(arr));
