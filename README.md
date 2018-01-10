# Lora-n-ud-avec-Arduino-et-LM35-
##### pour le branchement :
on connect les pins SPI  de arduino avec les pins SPI de lora (inAir4) :
MISO (pin 12 arduino ) ===> MISO 
MOSI (pin 11 arduino ) ===> MOSI 
CLK (pin 13 arduino ) ===> ACK
CS (pin 2 arduino ) ===> CS 
vcc 3,3 ====> 3,3 
GND ====> GND

###### pour les test d'envoie de valeur (exemple temperature)
le capteur de Temperture utilisé (LM35) est branché dans le pin A0 de Arduino; il donne des valeurs plus ou moins exacte en prenant compte la sensibilité de capteur; ceci est mentionné dans le code. 
Note : la bande opérationnelle de inAir4  est de 433Mh
D'autres tests se feront prochainement avec d'autres types de capteures afin d'avoir une multitude de valeurs. et aussi s'orienter vers les tests d'envoie multiples channels.
