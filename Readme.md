## MQTT Broker Example

Start Eclipse MQTT Broker:

```
docker compose up
```

Start MQTT Publisher:

```
cd iot-mqtt/
source venv/bin/active
python publisher.py
```

Start MQTT Subscriber:

```
cd iot-mqtt/
source venv/bin/active
python subscriber.py
```