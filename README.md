# ESP_RSA
Project to develop a Remote Service Adaptor for the ESP's
Idea of this project is to develop an RSA for all the existing hardware:
... means:
  - other ESP like ESP8266, ESP32
  - Linux machines like Raspberry
  - Windows machines like normal PC
  
 This project try to include hardware and software.

To bring this project to live:
1. connection is only via serial connection available (require an additonal ESP for log and control)
2. use default communication channels => planned is only mqtt (header=source, payload=Incident/Problem/Change as required)
3. if the default channels are unreacheble => Issue Management (i.e. Backbone done) => solution contains a http post

Let's try it ...
