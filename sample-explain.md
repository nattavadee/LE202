# อธิบายโปรแกรม

### การทดลองที่1

- ตัวอย่างโปรแกรมอยู่ในโฟลเดอร์ pattani โดยโปรแกรมนี้มีทั้งหมด 15 บรรทัด 2ฟังก์ชั่น คือ set up(รันครั้งเดียว) และloop(วนลูปไปเรื่อยๆ)     โดยในการทดลองนี้จะใช้คำสั่งcount เริ่มนับตั้งแต่0และนับไปเรื่อยๆ หรือถ้ากดปุ่มรีเซ็ต(ปุ่มสีแดง)ก็จะเริ่มนับใหม่
  
### การทดลองที่2

- การทดลองนี้มมี 2 ส่วน 1.set up- set wifi ให้พร้อมทำงาน   2.loop- วนลูปต่อไป โดยแสดงผลว่าเริ่มค้นหา wifi พอจับหาได้แล้วก็จะแสดงว่ามีwifiรอบตัวๆไหนบ้าง
  
### การทดลองที่3

- เป็นโปรแกรมที่ทดลองเอาoutputออกไปเป็นสัญญาณภายนอก โดยใช้คำสั่งpinMode เพื่อset port0 เป็น output และมัฟังก์ชันวนลูปทุกครึ่งวินาที และมีคำสั่งcount เมื่อเป็นเลขคี่-ไฟติด  เลขคู่-ไฟไม่ติด
  
### การทดลองที่4

- โดยการทดลองนี้จะนำสัญญาณinputจากภายนอกเข้ามาในmicrocontroller  โดยให้input เป็น port0 และ outputป็นport2 เมื่อinputเป็น0ไฟจะติด จากนั้นนำไปต่อกับเซนเซอร์แสง เมื่อเอานิ้วปิดเซนเซอร์ไฟจะดับแต่ถ้าเปิดไว้ไฟจะติด
  
### การทดลองที่5

- การสร้างเว็บเซิฟเวอร์ผ่านwifi  โดยต้องใส่ชื่อwifiและรหัสลงไปในโปรแกรมจากนั้นอัปโหลดลงmicrocontroller ในการทดสอบโปรแกรมต้องใช้เว็บเบราว์เซอร์

### การทดลองที่6

- สร้างwifi access point ขึ้นมาเอง โดยต้องกำหมดชื่อและพาสเวิดของwifi และกำหนดip address ของmicrocontroller โดยอุปกรณ์อื่นสามารถเช่อต่อกับwifiตัวนี้ได้
