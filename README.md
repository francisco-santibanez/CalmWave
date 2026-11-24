# ❤️ CalmWave | Projektbeskrivning


## Syfte

CalmWave är ett digitalt stödsystem som utvecklas för ungdomar med ADHD. Syftet är att hjälpa lärare att uppmärksamma fysiologiska förändringar som kan vara kopplade till stress eller överbelastning under skoldagen. Genom att samla in och visualisera kroppsliga signaler kan systemet ge lärare bättre förutsättningar att förstå nä en elev eventuellt behöver en paus, anpassning eller extra stöd.

CalmWave ska fungera som ett kompletterande stöd och inte som ett verktyg för att diagnotisera ADHD.

## Sensorer och teknik

Systemet ska använda sensorer för att samla in information om kropppens reaktioner:

- Pulssensor: mäter hjärtfrekvensen.
- HRV: undersöker variation mellan hjärtslagen.
- Rörelsesensor: registerar fysisk aktivitet för att ge mer sammanhang till mätningarna.
- EDA-sensor: kan mäta förändringar i hudens elektriska aktivitet.

Genom att kombinera olika mätvärden kan systemet uppmärksamma förändringar som eventuellt kan vara kopplade till stress eller överbelastning. Mätvärden kan däremot inte ensamma avgöra vad eleven känner.

## Användare och sammanhang

Den primära målgruppen är ungdomar med ADHD i skolmiljö. Eftersom ADHD påverkar individer på olika sätt har eleverna olika behov och kan reagera olika på exempelvis ljud, sociala situationer, skoluppgifter och förändringar i vardagen.

De sekundära användarna är lärare/vårdnadshavare och annan ansvarig skolperson som kan använda informationen för att bättre förstå elevens behov och de stöd vid rätt tillfälle.

## Visualisering och information

Informationen från sensorerna ska visas i en digital dashboard som är anpassad för lärare. 

Dashboarden ska innehålla:

- En graf som visar elevens puls över tid.
- En översikt över förändringar i kroppens mätvärden under skoldagen.
- Tydlig färgmarkeringar när värden avviker från elevens vanliga nivå.
- Notiser som uppmärksammar läraren på förändringar som kan behöva följas upp.

Exempel på en notis kan vara: "Förändringar i elevens mätvärden har registrerat. Kontrollera om eleven behöver stöd eller en paus".

## Från data till kunskap

Genom att omvandla sensordata till tydliga grafer och information kan CalmWave hjälpa lärare att upptäcka mönster och förändringar över tid. Informationen kan användas som ett underlag för samtal med eleven och för att förstå vilka situationer som eventuellt kan innebära ett större behov av stöd.

Systemet ska ta hänsyn till att varje elev är individuell. Därför ska mätvärden jämföras med elevens egna vanliga nivåer istället för att använda samma gränsvärden för alla.

## Teknisk utveckling

Vi kommer att undersöka vilka sensorer som passar bäst för projektet och hur de kan kopplas till en digital visualisering med JavaScript.

## NOTES

### Här länkar vi till det vi kan behöva till projektet

Komponent
https://my.cytron.io/p-max30102-oximeter-and-heart-rate-sensor-module?__cf_chl_tk=WE9ywdMSIFLggGgxTEfMMT2Pv2llnGd4fq.MyAoAh_w-1795442104-1.0.1.1-uuKyQU8CWGwzyVDxoX8MJveLnq3p7LY6bhjqh_Ou7co
This is a small MAX30102 Oximeter and Heart Rate Sensor Module for you to try!

The module is based on the MAX30102 chip and communicates via the I2C interface. MAX30102 is a complete system solution that facilitates the design process of mobile devices and wearable devices. The MAX30102 is integrated pulse oximetry and a heart-rate monitor module. It includes internal LEDs, photodetectors, optical elements, and low-noise electronics with ambient light rejection.

The MAX30102 operates on a single 1.8V power supply and a separate 3.3V power supply for the internal LEDs. Communication is through a standard I2C-compatible interface. The module can be shut down through software with zero standby current, allowing the power rails to remain powered at all times

