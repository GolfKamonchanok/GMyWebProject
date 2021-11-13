# QUEUIE
โปรเจคระบบคอยแถวสำหรับบริการของมหาวิทยาลัย จัดทำโดย กมลชนก กล่ำทอง
## Features
* จองคิวเข้าใช้บริการต่างๆของมหาวิทยาลัย
* ลดการแอดอัด ลดการเพิ่มการติดเชื้อ Covid-19
* ใช้งานได้ผ่านทางโทรศัพท์มือถือ
## Example code
``` 
child:
    const Text("โทร", style: TextStyle(fontSize: 20)),
onPressed: () async {
   const Url = 'tel:+ 089 415 0834';
   if (await canLaunch(Url)) {
     await launch(Url);
   } else {
     throw 'Could not launch $Url';
   }
 ``` 
 ## Credit
 610107030006@dpu.ac.th
 ## License
