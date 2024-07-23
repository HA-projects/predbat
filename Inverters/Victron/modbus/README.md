Victron Energy Multiplus connected via modbus 🚀️
============================


There are two files one for the modbus communication and the other to create different sensor out of this data. 
Those template sensors are needed for Predbat or for the HA Energy dashboard.

The modbus configuration uses the secrets file to store the modbus addresses.

**Use the file secrets.yaml to store secrets or reusable variables.**

Learn more at https://www.home-assistant.io/docs/configuration/secrets/
```
# Use this file to store secrets like usernames and passwords.
# Learn more at https://www.home-assistant.io/docs/configuration/secrets/
logger: debug
some_password: welcome
# Victron Energy Modbus Slave adresses
com.victronenergy.grid: 30
com.victronenergy.system: 100
com.victronenergy.battery: 225 #245
com.victronenergy.vebus: 246  #242
com.victronenergy.solarcharger: 247 # en 100 ?
```

---

DISCLAIMER
----------

***This setup  can be used in your projects by you own risk.***
