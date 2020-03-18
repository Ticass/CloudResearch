# CloudResearch
Definitions For cloud Research 
Team [Maria](https://github.com/maguilar93)

# IOT (Internet of things)
The IOT Data route is simple, it first starts his journey inside the sensors, where the data is Created
then the sensors will use the **[MQTT Protocol](https://en.wikipedia.org/wiki/MQTT)** to send that data to the Backend which is Either
the **NOsql service** or The **cloudSQL service** (Firebase etc…) (which is basically mySQL)

## What's the [MQTT Protocol](https://en.wikipedia.org/wiki/MQTT) ?
**[MQTT Protocol](https://en.wikipedia.org/wiki/MQTT)** stands for **Message Query Telemetry Transport**. it's a very **lightweight** [pub/sub](https://cloud.google.com/pubsub/docs/overview) protocol, designed for slow, bad or high latency networks, the whole thing is designed to be the most reliable protocol even if your network conditions are really poor, and also to ensure stability and good delivery of the service. These things makes the protocol perfect for new and emerging **"M2M"** or **"Message to Message"** technologies that uses the **IOT**.

## Who invented MQTT?
[MQTT Protocol](https://en.wikipedia.org/wiki/MQTT) was invented by [Dr Andy Stanford-Clark](https://en.wikipedia.org/wiki/Andy_Stanford-Clark) of [IBM](https://en.wikipedia.org/wiki/IBM), and [Arlen Nipper](https://www.linkedin.com/in/arlen-nipper-42281057) of Arcom (now Eurotech), in 1999.

### Where is the [MQTT Protocol](https://en.wikipedia.org/wiki/MQTT) in use?
[MQTT Protocol](https://en.wikipedia.org/wiki/MQTT) has been widely implemented across a variety of industries since 1999.

#### Is MQTT a standard?
v5.0 and v3.1.1 are now OASIS standards (v3.1.1 has also been ratified by ISO).

##### How does [MQTT Protocol](https://en.wikipedia.org/wiki/MQTT) relate to SCADA protocol and MQIsdp?
The [SCADA protocol](https://en.wikipedia.org/wiki/SCADA) and the **MQ Integrator SCADA Device Protocol** (MQIsdp) are both old names for what is now known as the MQ Telemetry Transport ([MQTT Protocol](https://en.wikipedia.org/wiki/MQTT)). The protocol has also been known as “WebSphere MQTT” (WMQTT), though that name is also no longer used.

###### Are there standard ports for MQTT to use?
Yes. TCP/IP port 1883 is reserved with IANA for use with MQTT. TCP/IP port 8883 is also registered, for using [MQTT Protocol](https://en.wikipedia.org/wiki/MQTT) over [SSL](https://en.wikipedia.org/wiki/Transport_Layer_Security).

###### Does [MQTT Protocol](https://en.wikipedia.org/wiki/MQTT) support security?
You can pass a user name and password with an MQTT packet in V3.1 of the protocol. Encryption across the network can be handled with SSL, independently of the [MQTT Protocol](https://en.wikipedia.org/wiki/MQTT) protocol itself (it is worth noting that SSL is not the lightest of protocols, and does add significant network overhead). Additional security can be added by an application encrypting data that it sends and receives, but this is not something built-in to the protocol, in order to keep it simple and lightweight.








