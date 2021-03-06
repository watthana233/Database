# Database กลุ่ม ตูมตาม สะท้านฟ้า

# อุปกรณ์

1.node MCU (ช่วยประมวณผล)

2.จอ LCD (แสดงผล)

3.DHT11 (วัดอุณหภูมิ)

4.หลอด LED 

5.สายไฟ 

.......................................................................................................................................

# วิธีต่อ node MCU กับ จอ LCD


![alttext](https://github.com/jokermarkk/Database/blob/master/%E0%B8%A7%E0%B8%B4%E0%B8%98%E0%B8%B5%E0%B8%95%E0%B9%88%E0%B8%AD%20node%20MCU%20%E0%B8%81%E0%B8%B1%E0%B8%9A%20%E0%B8%88%E0%B8%AD%20LCD.jpg?raw=true)

.......................................................................................................................................
 
# DHT11

<a href="http://www.mx7.com/view2/A2v6md22PxdZfQLa" target="_blank"><img border="0" src="http://www.mx7.com/i/0a4/5pnkIF.png" /></a>
.......................................................................................................................................

# วิธีการต่อใช้งานครับ

<a href="http://www.mx7.com/view2/A2v75Wi1ptvOEn2u" target="_blank"><img border="0" src="http://www.mx7.com/i/05d/GjLehl.gif" /></a>

ในการการต่อวัดแบบปกติ คือ ระยะห่างระหว่าง Sensor กับตัว Arduino ห่างกันไม่เกิน 20 เมตร จะต้องใช้ Pull up resistor ขนาด 5kohm 
   Pin 1  ต่อกับ VDD

   Pin 2  ต่อเป็นขา DATA

   Pin 3  ไม่ได้ใช้

   Pin 4  ลงกราวด์

โดยใช้แหล่งจ่ายแรงดัน VDD ขนาด 3-5.5 VDC ซึ่งข้อดีคือจะทำให้ DHT11 นี้สามารถใช้งานได้กับ Arduino หลายรุ่น แต่ในที่นี้เราจะใช่ Arduno NodeMCU

.......................................................................................................................................


# วิธี ดู fingerprint ของเว็บเรา ครับ แต่ต้องเป็นตัวใหญ่ ทั้งหมด

![alttext](https://github.com/jokermarkk/Database/blob/master/1%20fingerprint.jpg)

![alttext](https://github.com/jokermarkk/Database/blob/master/2%20fingerprint.jpg)

.......................................................................................................................................


# ความคิดสร้างสรรค์

เปิด - ปิด หลอด LED ผ่าน Firebase

วิธีการต่อขาหลอดLED

![alttext](https://github.com/jokermarkk/Database/blob/master/%E0%B8%AB%E0%B8%A5%E0%B8%AD%E0%B8%94%E0%B9%84%E0%B8%9F.jpg)

นำขา + ของ Led เชื่อมต่อกับ data ที่กำหนดไว้เช่น 

นำขา + Led ต่อกับ ขา D6 ของ NodeMCU และขา - ของ Led ต่อกับ กราวด์(Gnd)ของ NodeMCU

ในการสั่ง เปิด-ปิด ไฟ Led จะรับคำสั่งจาก Firebase ถ้าเป็น 0 = ปิดไฟ ,1 = เปิดไฟ 

![alttext](https://github.com/jokermarkk/Database/blob/master/%E0%B8%A7%E0%B8%B4%E0%B8%98%E0%B8%B5%E0%B8%95%E0%B9%88%E0%B8%AD%20node%20MCU%20%E0%B8%81%E0%B8%B1%E0%B8%9A%20LED.jpg)

.......................................................................................................................................

# วงจรรวม

![alttext](https://github.com/jokermarkk/Database/blob/master/%E0%B8%A7%E0%B8%B4%E0%B8%98%E0%B8%B5%E0%B8%95%E0%B9%88%E0%B8%AD%20node%20MCU%20%E0%B8%81%E0%B8%B1%E0%B8%9A%20%E0%B8%88%E0%B8%AD%20LCD%20LED%20dht11.jpg)

# รายชื่อ สมาชิก
1. นาย ชัยพร สุรินทร์ตะ
2. นาย พลวสิษฐ์ ศรีปทุมวงศ์
3. นาย ธีรนัย ปุณวัตร์
4. นาย นธี จายปาตาล
5. นาย ภาสกร กางาม

![alttext](https://github.com/jokermarkk/Database/blob/master/20883953_1462810363785994_1496489983_o.jpg)
