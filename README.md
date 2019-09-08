# การสร้าง Chat App โดย React native
   การสร้าง Chat App แบบพื้นฐาน สำหรับบุคคลที่กำลังจะเริ่มทำ Application การ Chat สามารถเอาไปปรับใช้ได้จริง โดยใช้ Firebase เก็บข้อมูล ด้วยการนำ Package firebase มาใช้

# ขั้นตอนการสร้างโปรเจค
1. npm install -g react-native-cli
2. react-native init testchat1
3. cd testchat1
4. react-native run-android

### สิ่งที่ใช้
   * Program Visual Studio Code
   * Mobile Phone (Android V.4++)   **ใช้โทรศัพท์ มากกว่า 1 เครื่องในการลอง เนื่องจากเราจะได้ทดสอบการสื่อสารกันระหว่าง เครื่องได้
  
### Package ที่ใช้

* โดยใช้ npm / yarn ในการติดตั้ง Package
  * npm install @react-native-community/async-storage
  * npm I firebase	
  * npm I  react-native-gesture-handler
  * npm I react-navigation
#### การใช้งาน Firebase เบื้องต้น คุณต้องมี User ใน Firebase ก่อน โดยไปสมัคร Firebase [https://firebase.google.com](www.google.com)

#### ตัวอย่างการใช้งาน Firebase

1. import Firebase
#### ![Alt text](https://www.img.in.th/images/7061c5a843d64d7ab5f90ae4f08bea86.png)
2. ส่วน Config Firebase
#### ![Alt text](https://www.img.in.th/images/af52f51d20939184e3e320bccc14d8b4.png)

## ตัวอย่าง Chat App 
### cmd
        git clone https://github.com/kittophop1998/ChatApp.git $$ cd testchat1 $$ npm install
### Config Firebase 
   * นำข้อมูลของ Firebase เราไปใส่ใน AuthLoading.js
   #### ![Alt text](https://www.img.in.th/images/1db94a236e8349a467871a3c7110f80e.png)

### RUN
   * react-native run-android
### Example App
   # เมื่อ Run โปรแกรมแล้ว หน้าจอจะแสดงผลหน้า login จากนั้นให้ผู้ใช้ใส่ Phone number และ name แล้วกด login
โปรแกรมจะแสดงหน้า Chat โดยแสดงรายชื่อเพื่อนทั้งหมดที่มี เมื่อต้องการ chat กับเพื่อนคนใดให้กดที่ชื่อบุคคลคนนั้น จากนั้นหน้าจอจะเข้าไปยัง Chat
ของบุคคลที่จะคุยด้วย หากผู้ใช้ต้องการดูโปรไฟล์ของผู้ใช้เองให้กดที่รูปคนด้านบนขวา

![Alt text](https://www.img.in.th/images/303de65b813dcdce84c13e2e6358dd6d.png)
### By 
     # kittophop1998
     # Seena98p
     # sirilaknew
     # Fareeda   
