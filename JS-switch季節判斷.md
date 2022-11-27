# switch季節判斷
// 春天 : 3 4 5
// 夏天 : 6 7 8
// 秋天 : 9 10 11
// 冬天 : 12 1 2
const month = 1
switch(month){
  case 3:
  case 4:
  case 5:
    console.log("春天")
    break
    
  case 6:
  case 7:
  case 8:
    console.log("夏天")
    break
    
  case 9:
  case 10:
  case 11:
    console.log("秋天")
    break
    
  case 12:
  case 1:
  case 2:
    console.log("冬天")
    break
    
  default:
    console.log("不合法月份")
}