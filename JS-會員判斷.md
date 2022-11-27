# 會員判斷
const isLoggedIn = true;
const role = 'menber';//admin,vip,menber
const points = 0;

//未登入印出:請登入
//登入印出:已登入
//管理者印出:Admin
//vip會員印出:歡迎光臨
//一般會員印出:Hello
//只要是會員，還有點數則印出:還有 XXX 點
//只要是會員，沒有點數則印出:請買點
if(isLoggedIn){
  console.log("已登入")  
  if(role == 'admin'){
    console.log("Admin")
    //管理者
  }else{
    //非管理者
    if(role == 'vip'){
      console.log("歡迎光臨")
    }else if(role == 'menber'){
      console.log("Hello")
    }else{
      console.log("訪客")
    }
    //template string
    if(points > 0){
      console.log(`還有${points}點`);
    }else{
      console.log("請買點")
    }
  }
}else{
  console.log("請登入!!")
}