# Innov8-Vaccintransport
vad behövs: 
* Karta 
* Pinpoints på Kartan
* tabell på leveranserna (försändelse-ID, datum och tider, adresser m.m.),  
* highlighted pin-points 
* input för information (lägg till knapp, update knapp) 
* Refresh knapp för tabell/karta 

Kravspecifikation: 
Måste: Mäta temperatur, Distanskonfigurering, Logga tid, Långt batteriliv, Casing, GPS trackning   
Bör: Display, Reservbatteri   
 
Lösningen ska med hög noggrannhet mäta temperaturen inom förpackningarna av coronavaccin. Om temperaturen är för hög ska det skickas en signal som larmar om den dåliga temperatursnivån och samtidigt logga tid eller med andra ord mäta tiden som temperaturen har varit icke godtycklig. Temperatursensorsmodullen ska också kunna bli följd med hjälp av GPS trackning så att den kan visas upp på t.ex. en hemsida som visar vart alla paketen befinner sig.    
 
Kais har för fram idéen att checka ut I2C kommunikation dock fattar vi inte den väldigt bra. Jag hittade en länk på en artikel med ett filmklipp där Arduino används i samband med I2C protokoll.   
https://howtomechatronics.com/tutorials/arduino/how-i2c-communication-works-and-how-to-use-it-with-arduino/ 