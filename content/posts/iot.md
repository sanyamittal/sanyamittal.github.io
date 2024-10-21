---
title: Internet Of Things
date: 2024-10-19
tags:
  - IoT
  - IIoT
  - Internet of Things
  - Arduino
---

# Introduction #

The term IoT is an abbreviation for Internet of Things. It is a collective network of physical devices which are
connected through the internet or any other communication network. They use certain technology that facilitates
communication among these connected devices as well as between these connected devices and the cloud. The
Internet of things encompasses electronics, communication, and computer science engineering.

# IoT Ecosystem #

IoT ecosystem consists of several heterogeneous components and technologies as below:
1. Things: Things are physical devices, assets, products, systems, people or processes that properties and
business logic. When a thing is fitted with various sensors and actuators so that they can recognize their
surroundings, we call that device a node in IoT terminology. Nodes are intelligent to measure and
communicate the physical parameters related to things.
2. Power and power management module: The power module offers the reliable power needed for the
system.
3. Sensor: A sensor is a device that measures physical parameters of a thing like humidity, blood pressure,
speed etc., collects light, vibration and chemical signals, and transforms them into electrical signals and
then transfers them to the Microcontroller. A variety of sensors have been used across industries for years,
specifically in vehicles, buildings and factories.

The table below lists the various factors you should consider while buying a sensor.

4. Actuators: Actuators are devices which convert mechanical or electrical signals into motion. They are
responsible for performing actions like switching on or off a light, generating sound or locking a door.

5. Microcontroller: The Microcontroller receives the data from the sensor and processes the data
accordingly.
6. Wireless Transceiver: The Wireless Transceiver then transfers the data, so that the physical realization of
communication can be achieved.
7. IoT Gateways: IoT Gateway sits at the intersection of Nodes and Cloud. It aggregates and processes the
information from multiple Nodes and facilitates the data flow to the cloud. IoT Gateway is capable of
- Connecting to the nodes via specific protocols (Communication between Node and Gateway)
- Storing and parsing the information from the nodes
- Sending information to the cloud servers for processing (Communication between Gateway and
Cloud)
- Controlling the nodes in the field in real time

8. IoT Communication Technologies: WPAN protocols are used to exchange information between Nodes
and Gateways. A Wireless Personal Area Network (WPAN) is a network for interconnecting devices
centered on an individual person&#39;s workspace, in which connections are wireless. Unlike wireless
networking standards like Wi-Fi, IoT applications have “less range” requirements for connecting
peripherals wirelessly and transferring files or data between various devices under vicinity hence WPANs
are the perfect fit. They have signal ranges of around 1m to 100m, a variety of data rates, and most
importantly low power consumption. The below table shows the various communication protocols
(between nodes &amp; gateways and gateway &amp; cloud) that can be adopted for IoT solutions.

9. IoT Platform: They are a complex heterogeneous aggregation of components which overlays device
connectivity, data aggregation, transformation, analytics and visualizations.

# Types of IoT #

The IoT Industry Sector is classified into three different categories as below:

## Consumer IoT ##

The Consumer IoT refers to the personal devices, such as smartphones, wearables, fashion items, and the growing
number of smart home appliances, that are now connected to the internet, collecting and sharing data. These are
products that make our lives easier by performing tasks or services for us. The common connectivity protocol used
in this kind of solution is BLE, WiFi, and ZigBee.

## Commercial IoT ##

Commercial IoT aims to provide our daily environment outside of the home. There is a set of applications that can
be deployed in places we frequently visit such as commercial office buildings, supermarkets, stores, hotels,
healthcare facilities, or entertainment venues. These types of applications provide a better experience to guests
through more efficient monitoring in smart buildings and smart offices. The common connectivity used in this kind
of solution are Radio Frequency (RF), NFC, Wi-Fi, etc.

## Industrial IoT ##

The Industrial Internet of Things (IIoT) takes networked sensors and intelligent devices and puts those technologies
to use directly on the manufacturing floor, collecting data to drive artificial intelligence and predictive analytics. The
IIoT can transform traditional, linear manufacturing supply chains into dynamic, interconnected systems that can
more readily incorporate ecosystem partners. The common connectivity used in this kind of solution is Advanced
Message Queuing Telemetry Protocol.

# Challenges #

There are some of the IoT issues and concerns:
## Privacy &amp; Security ##

- One of the greatest threats to the IoT comes from the strain put on the global system of information exchange that the IoT relies upon.
- Poorly secured IoT devices and services can serve as potential entry points for cyber-attack and expose user data to theft by leaving data streams inadequately protected.

## Interoperability &amp; Standards ##

- A fragmented environment of proprietary IoT technical implementations will inhibit value for users and industry.
- The use of generic, open, and widely available standards as technical building blocks for IoT devices and services will support greater user benefits innovation and economic opportunity.

## Legal, Regulatory &amp; Rights ##

- The use of IoT devices raises many new regulatory and legal questions as well as amplifies existing legal issues around the Internet.
- The questions are wide in scope, and the rapid rate of change in IoT technology frequently outpaces the ability of the associated policy, legal, and regulatory structures to adapt.

# Use Case Cold Storage #

## Problem Statement ##

ABC Beverages is a food &amp; beverage chain. They produce cool drinks and packaged foods. They also transport all
their items to outlets/retailers present in various cities across country. These beverages and food items require to be
kept in temperature less than 2 degrees. Also, the packaged food items should be stored at humidity less than 10%.
In few instances, when the temperature and humidity was not maintained appropriately, the items were found to be
spoilt.

## Solution ##

The company must ensure the following to solve the above problem:
- Maintain the temperature inside the trucks at less than 2 degrees
- Maintain humidity inside truck at 10%

## Approach ##

- Identify the sensors to be fitted inside the truck
- Connect the sensors to the trucks
- Collect and transfer the sensor data from the truck to the IoT platform
- Alert and act in case of any deviation

## IoT Ecosystem ##

| Components Used              | Variety                                                                                                                                                    |   |
|------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------|---|
| Things                       | Trucks                                                                                                                                                     |   |
| Sensors                      | Humidity Sensor and Temperature Sensor                                                                                                                     |   |
| IoT Gateway                  | Arduino Uno. Arduino board is a constrained device. It does not store any data. It just collects data from sensors and sends it to Cloud through Internet. |   |
| IoT Communication Technology | GSM                                                                                                                                                        |   |
| IoT Cloud/Platform           | Arduino Cloud                                                                                                                                              |   |

## Steps ##

1. The temperature sensor and humidity sensor are connected to Arduino&#39;s GPIO Pins (General Purpose Input
and Output Pins).
2. The combination of Arduino and sensor boards are placed in each truck.
3. The Arduino board acts as gateway and is programmed to capture electrical signals from the sensors. It
aggregates temperature and humidity data every 60 seconds and converts them to their respective unit of
measurement. Since the datasets generated by the sensors are in disparate formats, Arduino normalizes this
aggregated data into a standard format like JSON that is understood by the Cloud platform.
4. Since trucks are going to be mobile/moving on road, Arduino boards are connected to Internet via GSM
connectors for transmitting temperature and humidity data to Cloud Platform.
5. The temperature and humidity data, sent from each truck through the Arduino gateway, is stored in a
database on the Cloud.
6. An IoT platform hosted on cloud accesses this data and following needs to be done:
  - Configure the User (Manager) credentials using name/mail-id/phone number
  - Create nodes with unique Node numbers where each node represents a combination of truck and Arduino boards.
  - Device No. in Arduino should match with the one created in the IoT Platform
7. In the IoT platform, Rules and Alarms can be created for each truck.
8. A rule is set in the IoT Platform, to check if temperature is greater than 2 degrees and the humidity is greater than 10% in each of the trucks.
9. An alarm is created to send SMS with details of truck and deviation to manager under whom truck is registered, if the above rule is met.
10. Now for every set of data that the IoT platform receives, the rule is executed. If the rule is successful, the
alarm is triggered automatically. In this case an SMS is sent to the manager.
11. The manager who receives SMS takes appropriate action, like calling truck driver to clarify the settings and corrective actions.
