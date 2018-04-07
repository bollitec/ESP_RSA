# ESP_RSA
Project to develop a Remote Service Adaptor for the ESP's.

Idea is to develop an RSA for most of existing ESP hardware:

... means:
  - RSA => Remote Service Adaptor to control the main host
  - Hardware => ESP like ESP8266, ESP32, (later in an other project Server, PC, ...)
  - Support for => Linux machines incl. Raspberry (later Windows as well)
  - API to control server => every platform, html based, standard json requirements
  
This project include hardware and software.

To bring this project to live:
1. connection is only via serial connection available (require an additonal ESP for log and control)
2. use default communication channels => planned is only mqtt (header=source, payload=Incident/Problem/Change as required)
3. if the default channels are unreacheble => Issue Management (i.e. Backbone done) => solution contains a http post

Let's try it ...
