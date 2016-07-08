# OpenRemote Overview

The OpenRemote platform consists of several software components: **Controller**, mobile client **Console**, and **Designer**. Backend services provided (and some publicly hosted by OpenRemote) are collectively called **Beehive**.

OpenRemote supports a large variety of building automation protocol standards. In addition, it provides APIs for the customization and extension of its capabilities.

## OpenRemote Controller

The OpenRemote Controller, an always-on (24/7) Linux, Windows or OS X server application, which connects the mobile control devices (smartphones, tablets) to building automation systems and devices under control. Control devices can be building infrastructure (light switches, power outlets etc.), consumer electronic devices, or home appliances. The OpenRemote Controller can also run scripts, which are called rules. These rules are automation sequences, which are implemented based on the open Drools event processing language. The OpenRemote controller acts as a gateway running an agent in an IoT architecture.

## OpenRemote Console

The second component consists of the OpenRemote mobile clients (OpenRemote Console) for iOS or Android. Graphical user interface and functionality of these apps can be fully customized using the third component of OpenRemote, the OpenRemote Designer.

## OpenRemote Designer

OpenRemote Designer is an online, cloud-based application, providing a graphical user interface for crafting the mobile client interface and the related commands, sensors, and switches. Once user interface and control functions are designed, the Designer configuration files are synchronized with the co-located or hosted Controller installation. The mobile client application Console is updated automatically, when connecting to the Controller, immediately reflecting changes or updates made within the online Designer project.

## Beehive Services

OpenRemote backend services provide user, tenant, device, asset, and rule management. Remote proxy support (bi-directional communication with gateways through network routers is available.

The current software release OpenRemote Controller 2.5 supports the following device protocol adapters:

* 1-Wire Protocol
* AMX Controller
* DateTime Protocol
* Denon Serial AVR Protocol
* Domintell
* DSC IT-100
* EnOcean
* GlobalCache
* HSC Z-WAVE IP Gateway
* Insteon
* Integrated Control Technology (ICT)
* ISY-99
* KNX
* Lutron HomeWorks
* panStamp Lagarto
* Russound RNET Protocol
* Samsung TV Remote Protocol
* Shell execution protocol
* Shell execution protocol
* TCP/IP, UDP, Telnet, HTTP, HTTP/REST
* Velbus
* Wake-On-Lan Protocol
* X10
* XBMC
* xPL,IRTrans, VLC, FreeBox, MythTV
* Z-Wave