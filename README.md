# ProtocoloMqtt

* O protocolo MQTT é utilizado para que o ESP32 assine um tópico onde, se a mensagem recebida for "1L" ele ligue o LED1; se for "1D" ele desligue o LED1; se for "2L" ele ligue o LED2; e se for "2D" ele desligue o LED2. Qualquer outra mensagem recebida deve ser só impressa na serial;
* Este mesmo ESP32 publica a cada DOIS segundos uma mensagem "Hello World #XXX", onde XXX é um número que é incrementado automaticamente pelo ESP32; 
* O broker utilizado foi o -> test.mosquitto.org.
