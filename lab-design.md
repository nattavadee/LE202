# ออกแบบการทดลอง

### การเปิด-ปิดไฟด้วยเสียงตบมือ

#### อุปกรณ์การทดลอง
- Arduino UNO R3
- Sound Detection Sensor Module LM393
- สาย Jumper 
- Prototype PCB Board 4x6 cm Double Sides
- สกรูหัวกลม+น็อตตัวเมีย ขนาด 3มม ยาว 12มม
- Relay 1 Channel DC 5V Module
- SMD LED Lighting G4 AC DC 12V
- รางถ่าน AA 8 ก้อน

#### การต่อเซ็นเซอร์เสียง LM393 กับ Arduino UNO

LM393 <--> UNO

+5V <--> 5V (สีแดง)

GND <--> GND (สีดำ)

OUT <--> D4 (สีฟ้า)

#### การต่อระหว่าง Relay และ Arduino UNO

Relay <--> UNO

5V <--> 5V (สีแดง)

GND <--> GND (สีดำ)

IN <--> D5 (สีฟ้า)

#### การต่อวงจรระหว่าง UNO+ Relay + LED + รางถ่าน

- ต่อ LED กับ PCB Board ด้านล่างต้องใช้ ตะกั่วบัดกรี Jumper กับ ขา LED ให้เชื่อมต่อกัน ทั้ง 2 ขา
-LED เป็น LED แบบไม่มีขั้ว ต่อเข้าด้านไหนก็ได้

#### การปรับค่าเซนเซอร์เสียง
- เอาไขควงหมุนตัว R  สีฟ้า

#### เว็บไซต์อ้างอิง

https://www.robotsiam.com/
