# Lora-n-ud-avec-Arduino-et-LM35-
pour le branchement :
on connect les pins SPI  de arduino avec les pins SPI de lora (inAir4) :
MISO (pin 12 arduino ) ===> MISO 
MOSI (pin 11 arduino ) ===> MOSI 
CLK (pin 13 arduino ) ===> ACK
CS (pin 2 arduino ) ===> CS 
vcc 3,3 ====> 3,3 
GND ====> GND
le capteur de Temperture (LM35) brancher dans le pin A0 de Arduino 
Note : la bande opérationnelle de inAir4  est de 433Mhz
