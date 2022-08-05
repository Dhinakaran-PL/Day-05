# Day-05
1.
// let arr = [1,2,3,4,5,6,7,8,9,10,11,12]

// let odds = arr.filter(n => n%2)

// console.log(odds)

2.
// var str = "hi how are you";
// var newStr = str.split(' ').map(ele => ele[0].toUpperCase() + ele.substring(1).toLowerCase());
// console.log(newStr);

3.
// var arr = [1,2,3,4,5,6,7,8,9,10,11,12]

// var res=arr.reduce((acc,ele)=>acc+ele,0);
// console.log(res)

4.
// var numArray = [2, 3, 4, 5, 6, 7, 8, 9, 10]

// numArray = numArray.filter((number) => {
//   for (var i = 2; i <= Math.sqrt(number); i++) {
//     if (number % i === 0) return false;
//   }
//   return true;
// });

// console.log(numArray);

5.
// var str =(121)
// var Palindrome=(ele=> ele.split("").reverse().join(""));
// console.log(Palindrome)


1.
var ele=function(arr){
var odd=[]
 
for(var i=0;i<arr.length;i++)

if(arr[i]%2===1){

odd.push(arr[i])
  
 }
return odd;
  }
console.log(ele([1,2,3,4,5,6,7,8,9,10,11,12].map(Number)))



