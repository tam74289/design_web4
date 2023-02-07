# AW-SCRIPT-V3
 # Local Installation

 - ติดตั้ง Nodejs Version TLS ให้เรียบร้อย (https://nodejs.org/en/)
 - ดาวน์โหลด aw-script-v3 (https://github.com/Kittipob-K/aw-script-v3)
 - ทำการแตกไฟล์ aw-script-v3-main.zip
 - เข้าไปที่ โฟลเดอร์ aw-script-v3-main
 - เข้าไปที่ไฟล์ .env เข้าไปทำการตั้งค่าจากนั้นให้กดบันทึก
 - เปิด script_start.bat จะเป็นหน้าต่างการทำงานสคริปต์
 - เปิดหน้าเว็บเบาเซอร์แล้วเข้าไปที่ http://localhost:4050/

| ประเภท | สิ่งที่ต้องการ |
| ------ | ------ |
| SECRET_KEY_1 | ให้สร้างคีล์ขึ้นมาจำนวน `50` ตัว |
| SECRET_KEY_2 | ให้สร้างคีล์ขึ้นมาจำนวน `25` ตัว |
| SYSTEMS | ให้ตั้งค่าเป็น `local` เท่านั้น |

[VDO สอนการติดตั้งแบบ Localhost](https://fb.watch/iydbkILY5i/)

 # Cloud Installation

 - ให้ทำการก๊อปปี้ url ด้านล่าง
 ```sh
https://github.com/Kittipob-K/aw-script-v3.git
```
 - แล้วเข้าไปยัง Cloud ที่ท่านต้องการ ยกตัวอย่างเช่น replit
 - จากนั้นให้ทำการโคนตัวสคริปเข้ามาไว้ใน Cloud ของท่าน
 - ต้องทำการสร้างตัวเข้ารหัส เข้าไปที่สคริปต์ที่ทานติดตั้งจากนั้นมองหา Tools แล้วเลือก Secrets แล้วทำการตั้งรหัส

| ประเภท | สิ่งที่ต้องการ |
| ------ | ------ |
| SECRET_KEY_1 | ให้สร้างคีล์ขึ้นมาจำนวน `50` ตัว |
| SECRET_KEY_2 | ให้สร้างคีล์ขึ้นมาจำนวน `25` ตัว |
| SYSTEMS | ให้ตั้งค่าเป็น `cloud` เท่านั้น |


[VDO สอนการติดตั้งแบบ Cloud](https://fb.watch/iydYvh56x9/)

 ## Config

 ไปที่ไฟล์ config.json

 ```json
 {
   "port": 4050, # กำหนดพอร์ตให้สำหรับสคริป
   "time_zone": "Asia/Ho_Chi_Minh", # กำหนดขอบเขตเวลาที่จะแสดง
   "api_nonce_localhost": false # true = ให้สคริปสร้าง nonce / false = ให้ api-nonce สร้าง nonce (แก้ไข url ใน api-nonce.json ด้วย)
 }
 ```