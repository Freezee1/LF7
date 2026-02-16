Im Rahmen dieses Projektes wurde ein Python-Programm entwickelt, das die Temperatur eines DS18B20 Temperatursensors am Raspberry Pi ausliest und im Terminal ausgibt. 

Der Sensor wird über das 1-Wire-System angesprochen. Der Raspberry Pi stellt die Sensordaten im Linux-Dateisystem unter /sys/bus/w1/devices/ bereit. 
 Das Python-Programm liest diese Datei aus, überprüft die Gültigkeit der Messung und gibt die Temperatur formatiert in Grad Celsius aus. 
