# PnP

[GitHub - ridomin/Rido.IoTHubClient: Minimalistic device client to interact with Azure IoT Hub](https://github.com/ridomin/Rido.IoTHubClient)

## DTDL Broker

- mosquitto with custom Topics 
- - Device and ControlApp
- mosquitto with hub reserved topics
- Twin Service for mosquitto 


## BYO MQTT

- Refactor Interface to hide MqttNet types
- Review M2M, look at async/callback style

## Interactions

- Implement correlation with Rid (and validate errors)
- Review return types
- Refactor Topics in smart constants
  
## codegen

- Refactor target sample
- Explore Source Generators
- PoC with Mustache

## web clients

- Sas Auth https://github.com/ridomin/iothub-auth