# Database กลุ่ม ตูมตาม สะท้านฟ้า

วิธีต่อ node MCU กับ จอ LCD


![alttext](https://github.com/jokermarkk/Database/blob/master/%E0%B8%A7%E0%B8%B4%E0%B8%98%E0%B8%B5%E0%B8%95%E0%B9%88%E0%B8%AD%20node%20MCU%20%E0%B8%81%E0%B8%B1%E0%B8%9A%20%E0%B8%88%E0%B8%AD%20LCD.jpg?raw=true)
.......................................................................................................................................
 
DHT11

<a href="http://www.mx7.com/view2/A2v6md22PxdZfQLa" target="_blank"><img border="0" src="http://www.mx7.com/i/0a4/5pnkIF.png" /></a>
.......................................................................................................................................

วิธีการต่อใช้งานครับ

<a href="http://www.mx7.com/view2/A2v75Wi1ptvOEn2u" target="_blank"><img border="0" src="http://www.mx7.com/i/05d/GjLehl.gif" /></a>

ในการการต่อวัดแบบปกติ คือ ระยะห่างระหว่าง Sensor กับตัว Arduino ห่างกันไม่เกิน 20 เมตร จะต้องใช้ Pull up resistor ขนาด 5kohm 
   Pin 1  ต่อกับ VDD

   Pin 2  ต่อเป็นขา DATA

   Pin 3  ไม่ได้ใช้

   Pin 4  ลงกราวด์

โดยใช้แหล่งจ่ายแรงดัน VDD ขนาด 3-5.5 VDC ครับ  ซึ่งข้อดีคือจะทำให้ DHT11 นี้สามารถใช้งานได้กับ Arduino หลายรุ่น แต่ในที่นี้เราจะใช่ Arduno NodeMCU
   
.......................................................................................................................................

วิธี ดู fingerprint ของเว็บเรา ครับ แต่ต้องเป็นตัวใหญ่ ทั้งหมด

![alttext](https://github.com/jokermarkk/Database/blob/master/1%20fingerprint.jpg)

![alttext](https://github.com/jokermarkk/Database/blob/master/2%20fingerprint.jpg)
