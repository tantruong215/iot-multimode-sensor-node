# TODO – IoT Multi-Protocol Sensor Node

- [ ] Set up I2C read for SHT31 and BH1750 sensors
- [ ] Implement deep sleep mode on ESP32 (wake every 60s)
- [ ] Transmit readings over Wi-Fi MQTT when strong signal
- [ ] Switch to LoRaWAN if RSSI < –110 dBm or battery < 3.3V
- [ ] Connect to TTN backend and display on InfluxDB + Grafana
- [ ] Trigger alerts for high temp (>30°C) or humidity (>85%)
