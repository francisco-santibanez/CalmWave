Video som förklarar hur sensor fungerar
https://www.youtube.com/watch?v=YjM_bvzwwRc

## Olika variation av Moduler:

1. MAX30101 eller MAX30105
- Använder röd (660nm) och IR-ljus (880nm) samt har gröntljus (530 nm)
- Fungerar bättre till handled med hänsyn till människans anatomi.

2. MAX30102 eller MH-ET LIVE MAX30102
- Använder enbart rött (660nm) och infrarött (880nm) och kostnadseffektiv moduler
	
3. HW-605 eller GY-MAX30102
- Detta är en klon av MAX30102 men annan PCB-bräda

4. DFRobot SEN0203
- Nybörjare vänligt då det tillkommer band med.
- Enkel att installera med snabba lösning

### Saker och ting att tänka på
2 approach 

### Alternativ 1 (Mobilitet). Tillverka mobilt 3d band som ligger på handleden
*Generel info*
- Ljusskärmning
	Att blockera omgiven ljus så att det inte läcker in i sensorn för att optimera resultatet (om vi ska använda verkstan och tillverka ett 3d band av plast där 		Mikrokontroller är placerad med sensor och batteri)

- Rörelse
  Med hänsyn till rörelse så kommer antigen MAX30101 eller MAX30105 behövs då det har grönt Ljus som hjälper till på så sätt att våglängden är bredare men kortare 	som senare ger en mer ytlig effekt

- Passform
  Att bandet till 3d modulen som Mikrokontroller ska vara i inte är för elastisk då enheten inte kommer ge tydligt resultat, samt att den inte ska vara för spänd.

*Elektronik info*
- Accelerometer
  Implementera accelerometer som känner av handrörelse så när handleden är i “viloläge” eller är en mer stabil position så känner accelerometern av detta och registrera vidare till pulssensor att den kan börja mäta.

- Mikrokontroller storlek
  Begränsad utrymme att jobba med så det behövs en mindre variation av mikrokontroller som kan har WIFI (internt uppkoppling)
  (Alternativ på wifi Mikrokontroller skulle kunna vara XIAO ESP32-C3 )

- Batteri storlek och säkerhet
  Att batteriet har en säker position med det andra komponenterna så att den inte blir skadad eller förstörs med handrörelse.

### Alternativ 2 (stationär prototyp) Använda universitet mikrokontroller med breadboard
*Generel info*
- Ljusskärmning
  -||- samma kriterier som ovanför 
  
- Fast position
   Så MAX30102 eller MH-ET LIVE MAX30102 kommer säkert fungera utmärkt samt (kostnadseffektiv och enklare projekt)

*Elektronik info*
- Ingen Accelerometer
- Mikrokontroller storlek spelar mindre roll då formatet ska vara på plats
- Ingen batteri där ström istället kommer från usb porten
  
### Definitioner
Inter-Integrated Circuit = 2 vägars kommunikation eller (bidirektionell)
SCL (Serial clock) = I vilken takt kommunikationen ska gå i alltså hastighet
SDA (Serial Data) = kanalen som överför själva datan som är i bits
V = Volt antigen 3.3v eller 5v (mest normala )

### Funderingar
(Kanske att lägga till Accelerometer är överkurs)
(Men om vi ska använda ESP exempelvis göra en prototyp med universitetet Mikrokontroller som är ESP8266 NodeMCU och sedan använda MPU6050 som är en modul för  accelerometer, kommunikationen kommer vara genom I2C som är Inter-Integrated Circuit)


### Amazon
Pulssensor med Röd & IR & grön ljus (MAX30105)
https://www.amazon.se/s?k=MAX30105&crid=1YL2FIKZ87JY0&sprefix=max30105%2Caps%2C152&ref=nb_sb_noss_1

Pulssensor med Röd & IR (MAX30102)
https://www.amazon.se/s?k=MAX30102&crid=2AG1O88LR6P34&sprefix=mpu6050%2Caps%2C403&ref=nb_sb_noss_1

Mini mikrokontroller (XIAO ESP32-C3)
https://www.amazon.se/s?k=XIAO+ESP32-C3&crid=1WVO6IAKP0BFJ&sprefix=%2Caps%2C368&ref=nb_sb_noss_2

Mini mikrokontroller (esp32-c3)
https://www.amazon.se/s?k=ESP32-C3+SuperMini&crid=14TNW9XKK2K07&sprefix=esp32-c3+supermini%2Caps%2C262&ref=nb_sb_noss_2

Mini mikrokontroller (waveshare esp32-c6)
https://www.amazon.se/s?k=waveshare+esp32-c6&crid=2RR2T0H1P4V77&sprefix=waveshare+esp32-c6%2Caps%2C187&ref=nb_sb_noss_2

3 axis Accelerometer Module (MSA311)
https://www.amazon.se/s?k=MSA311&crid=2MM7LJI8POKWB&sprefix=msa311%2Caps%2C252&ref=nb_sb_noss_1

6 axis Accelerometer module (MPU6050)
https://www.amazon.se/s?k=MPU6050&crid=1H7MIQCL34XMS&sprefix=mpu6050%2Caps%2C165&ref=nb_sb_noss_1
