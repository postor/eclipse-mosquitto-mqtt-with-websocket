# eclipse-mosquitto-mqtt-with-websocket

eclipse-mosquitto mqtt with websocket


```
...
services:
  ...
  mqtt:
    image: eclipse-mosquitto
    restart: always
    ports:
      - 8000:8000
      - 1883:1883
```