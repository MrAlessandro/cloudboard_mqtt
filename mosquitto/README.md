# DEPLOLY LOCAL

Run following: 

```bash
docker run -it -d --name mosquitto -p 1883:1883 -p 9001:9001 \
    -v /Users/alessandro/Development/Personal/cloudboard_mqtt/mosquitto/mosquitto.conf:/mosquitto/config/mosquitto.conf \
    -v /Users/alessandro/Development/Personal/cloudboard_mqtt/mosquitto/mosquitto_data:/mosquitto/data \
    -v /Users/alessandro/Development/Personal/cloudboard_mqtt/mosquitto/mosquitto_plugins:/mosquitto/plugins \
    -v /Users/alessandro/Development/Personal/cloudboard_mqtt/mosquitto/mosquitto_log:/mosquitto/log eclipse-mosquitto 
```