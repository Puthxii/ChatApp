# การสร้าง Chat App โดย React native
   บทความนี้สอนการสร้าง Chat App โดยใช้ Firebase เป็นที่เก็บข้อมูล ให้สามารถนำ Package firebase มาใช้ทำ Chat App แบบพื้นฐาน ให้คนที่กำลังจะเริ่มทำ Application เอาไปปรับใช้ได้จริง

## สิ่งที่ใช้
   * Program Visual Studio Code
   * Mobile Phone (Android V.4++)
  
## Package ที่ใช้

* โดยใช้ npm / yarn ในการติดตั้ง Package
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
