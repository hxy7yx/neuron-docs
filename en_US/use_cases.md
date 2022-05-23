# Introduction

Neuron is an industrial application that can run on all kinds of IoT ultra-low resource hardware, supporting access to dozens of industrial protocols and converting to MQTT protocol to access the cloud-based IIoT platform, access to multiple devices or applications with various protocols simultaneously. Neuron provides a SQL-based stream processing rule engine to execute AI/ML logic. Make it to be a lightweight and powerful edge server, becoming the leader of the same product in the current market.

- Multiple Industrial Protocols: Supports many protocols and devices such as Modbus, OPCUA, Siemens, Mitsubishi, Omron, IEC104 and BACnet;
- Management web console: users can perform visual configuration in the browser to achieve cross-industrial equipment data access;
- Northbound standard MQTT data transmission: according to the user-specified configuration, the data is sent to the specified MQTT message server;
- Southbound driver connection: Neuron send control commands to the device and get back data.
- Stream processing engine: Combined with the rule engine function provided by eKuiper, it can quickly realize streaming SQL rule-based device control;
- Local data storage: realizing the storage and viewing of the original data of the device in local database;