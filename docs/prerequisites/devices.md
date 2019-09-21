# Devices
A list of verified compatible devices is maintained here.

Added to that is an overview of devices supported by OpenMQTTGateway:
* For radio frequency devices OpenMQTTGateway can support a wide range of 433mhz/315mhz devices, all the ones with SC5262 / SC5272, HX2262 / HX2272, PT2262 / PT2272, EV1527, RT1527, FP1527, HS1527 chipset  are supported by the RF gateway. Added to that RF2 support Kaku and Pilight an [huge list](https://wiki.pilight.org/devices). Note that for the moment RF, RF2 and Pilight can not be activated on the same boards together.

![boards](../img/OpenMQTTGateway_devices_rf1.png ':size=250%')
![boards](../img/OpenMQTTGateway_devices_rf2.png ':size=250%')
![boards](../img/OpenMQTTGateway_devices_rf3.png ':size=250%')

* For BLE devices OpenMQTTGateway is able to scan all the BLE devices that advertise their data so as to do presence detection. Added to that it reads values coming from :
** Mi Flora (temperature/moisture/luminance/fertility)
** Mi Jia (temperature/humidity)
** Clear Grass (temperature/humidity)
** LYWDS02 Clock (temperature/humidity)
** Mi Scale (weight)

<p align="center">
    <img alt="compatible devices" src="../img/OpenMQTTGateway_devices_ble.png" width=250>
</p>

* For infrared devices the list of supported brand is [here](https://github.com/1technophile/OpenMQTTGateway/blob/d2dd6138558909b71cc44f69665340247bd5f356/main/config_IR.h#L52), as there is also the possibility of using raw and global caché sending the possibilities of this gateway is huge!

* LORA is more dedicated at this moment for tinkering and DIY and there is no Off the shelves devices compatible to my knowledge with this gateway.
