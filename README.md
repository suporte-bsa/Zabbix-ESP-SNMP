# Zabbix-ESP-SNMP
Integração entre a ferramenta Zabbix e uma ESP-01 utilizada para coletar dados de temperatura e umidade. Os dados são enviados para o Zabbix via SNMP. 

# Esp-01 - Zabbix - SNMP (Monitor de temperatura e umidade)

Esse é um tutorial para configuração de SNMP para monitoração de temperatura e umidade utilizando-se uma ESP-01.


# Esquemático


## Requerimentos

Para o correto funcionamento do upload, necessita-se:

 - Arduino IDE  ([Download](https://www.arduino.cc/en/main/software));
 - As bibliotecas:
 WifiManager.h ([Download](https://github.com/tzapu/WiFiManager));
 Arduino_SNMP.h ([Download](https://github.com/fusionps/Arduino_SNMP));
 WiFiUdp.h ([Download](https://github.com/esp8266/Arduino/blob/master/libraries/ESP8266WiFi/src/WiFiUdp.h));
 DHT.h ([Download](https://github.com/adafruit/DHT-sensor-library)).
 
 - Módulo ESP-01;
 - Sensor DHT22.


## Como instalar as bibliotecas

Após fazer Download das bibliotecas em formato .ZIP, copie as pastas para o diretório "arduino-1.8.12\libraries".

	> O nome do diretório vai depender da versão da ide.

## Fazer Upload do Código para a placa

## WifiManager.h


