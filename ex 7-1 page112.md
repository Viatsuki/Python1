# Python1
from datetime import

holiday = {"2019-07-16","2019-07-17","2019-07-29"}
daylist = {0: "วันจันทร์", 1: "วันอังคาร", 2: "วันพุธ", 3: "วันพฤหัสบดี", 4: "วันศุกร์", 5: "วันเสาร์", 6: "วันอาทิตย์"}
checkday = date(2019, 7, 28)
dayno = checkday.weekday()
  print("วันที่ต้องการตรวจสอบ",checkday.strftime("%d/%m/%Y"),"คือ",daylist[dayno],end=" ")
  for hday in holiday:
    hday = hday.split("-",5)
    hday = date(int(hday[0],int(hday[1],int(hday[2]))
    if hday == checkday or dayno == 5 or dayno == 6:
      print("เป็นวันหยุด")
      break
    else:
      print("ไม่ใช่วันหยุด")
     
