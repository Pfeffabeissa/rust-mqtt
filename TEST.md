```bash
cp .ci/mqtt_pass_plain.txt .ci/mqtt_pass_hashed.txt
chmod 700 .ci/mqtt_pass_hashed.txt
mosquitto_passwd -U .ci/mqtt_pass_hashed.txt
```
