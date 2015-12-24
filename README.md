# Arduino OLED weather station
โปรแกรมรายงานอุณหภูมิและความชื้นในอากาศจาก DHT11 แสดงผลบน OLED SPI module

## อุปกรณ์
- Arduino รุ่นที่รองรับ Digital Output ได้อย่างน้อย 5 พิน (ในที่นี้ใช้ Arduino Mega เพราะไม่มีตัวอื่นให้ลอง :v )
- DHT22 หรือ DHT11 (จริงๆ มี DHT22 แต่ขี้เกียจงัดขา/บัดกรี)
- OLED ที่สามารถแสดง Bitmap Display ได้ (ในที่นี้ใช้ 0.96" SPI 128x64 pixel OLED Display module หาซื้อได้ตามร้านขายอุปกรณ์ Arduino ทั่วไป ราคาประมาณ 3xx)

## Software ที่ต้องใช้ประกอบ
1. อุปกรณ์สร้างภาพ
  1.1. โปรแกรมสร้างรูปแบบ 1-bit BMP ได้ (เพราะลองแบบ 8bit แล้วภาพไม่ขึ้น ในที่นี้ใช้ Photoshop)
  1.2. โปรแกรมแปลงภาพ BMP เป็น array of character (ในที่นี้ใช้ [link=http://www.electrodragon.com/w/0.96%27%27_128*64_OLED_Display]LCD Assistance[/link])
2. โปรแกรมสำหรับเขียนคำสั่ง ใช้ Arduino IDE

## วิธีการ
เดี๋ยวกลับมา
