# JS-質數判斷
let x=10;

// mod % 求餘數
// 整除mod完=0不是質數

//for迴圈
let isNotPrime = false;//flag 標記
 for(i=2;i<=x-1;i++){
   if(x % i ===0){
     isNotPrime = true;
     break
   }
 }

 if(isNotPrime == false){
   console.log(`${x}是質數`)
 }else{
   console.log(`${x}是因數`)
 }
 
//while迴圈
let isNotPrime = false;
let i = 2;
while(i<=x){
  if(x % i === 0)
    isNotPrime = true;
    i++
    break
}
if(isNotPrime == false){
  console.log(`${x}是質數`)
}else{
  console.log(`${x}是因數`)
}