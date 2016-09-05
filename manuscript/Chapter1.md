# Chapter 1
## Overview
OpenRemote is a state of the art open source software platform for building automation and device control. It has been used for smart building and Internet of Things (IoT) projects around the world, and is supported by a large and active user community. The OpenRemote platform consists of three software components: 
#### Open Remote Controller
The OpenRemote Controller, an always-on (24/7) Linux, Windows or OS X server application, which connects the mobile control devices (smartphones, tablets) to building automation systems and devices under control. Control devices can be building infrastructure (light switches, power outlets etc.), consumer electronic devices, or home appliances. The OpenRemote Controller can also run scripts, which are called rules. These rules are automation sequences, which are implemented based on the open Drools event processing language. 
#### OpenRemote Mobile Client
The second component consists of the OpenRemote mobile clients (OpenRemote Panels) for iOS or Android. Graphical user interface and functionality of these apps can be fully customized using the third component of OpenRemote, the OpenRemote Professional Designer. 
#### Professional Designer
OpenRemote Professional Designer is an online, cloud based application, providing a graphical user interface for crafting the mobile client interface and the related commands, sensors, and switches. Once user interface and control functions are designed, the Professional Designer configuration files are synchronized with the local controller installation. The smartphone client application is updated automatically, when connecting to the controller, immediately reflecting changes or updates made within the online Professional Designer project. 
## Supported Control Protocols
OpenRemote supports a large variety of building automation protocol standards. In addition, it provides API’s for the customization and extension of its capabilities. The current software release OpenRemote Controller 2.6 supports the following control protocols:

| Protocol                    | Description       |
|--------------------------------------|----------------------------------------------------------------------------------------------|
| 1-Wire Protocol                       | Low data rate communication bus for Maxim Integrated Products. [www.maximintegrated.com]()                                               |
| AMX Controller                       | AMX Inc. proprietary device control protocol.                                                |
| DateTime Protocol                    | Display of date and time, including sunrise/sunset calculation.                              |
| Denon Serial AVR Protocol            | Protocol to control Denon / Marantz audio / video/ devices.                                  |
| Domintell                            | Protocol for Domintell building control infrastructure.                                      |
| DSC IT-100                           | Protocol for DSC (Digital Security Controls) systems.                                        |
| EnOcean                              | Energy harvesting wireless technology for device control ISO/IEC 14543-3-10. www.enocean.com |
| GlobalCache                          | Infrared control devices by specialist GlobalCache. www.globalcache.com                      |
| HSC Z-WAVE IP Gateway                | Honeywell Z-Wave Gateway.                                                                    |
| Insteon                              | Home automation system based on power line and radio frequency (RF). www.smartlabsinc.com    |
| Integrated Control Technology (ICT)  | Protocol for the Protege Suite, an enterprise level building automation system               |
| ISY-99                               | Control protocol for Universal Devices home automation solution.                             |
| KNX                                  | International standard for industry grade wireline home automation. www.knx.org              |
| Lutron HomeWorks                     | Protocol for Lutron building control infrastructure.                                         |
| panStamp Lagarto                     | Open source protocol for PanStamp wireless modules. www.panstamp.com                         |
| Russound RNET Protocol               | Protocol for Distributed Audio/Video solutions from Russound.                                |
| Samsung TV Remote Protocol           | Protocol used to control Samsung TV systems.                                                 |
| Shell execution protocol             | Execution of shell scripts.                                                                  |
| Shell execution protocol             | Execution of shell scripts.                                                                  |
| TCP/IP, UDP, Telnet, HTTP, HTTP/REST | Internet protocols                                                                           |
| Velbus                               | Protocol for velbus home automation products www.velbus.eu                                   |
| Wake-On-Lan Protocol                 | Protocol activating networked systems in power save mode.                                    |
| X10                                  | Legacy standard for power line based home automation.                                        |
| XBMC                                 | Open source media player platform. xbmc.org                                                  |
| xPL,IRTrans, VLC, FreeBox, MythTV    | Commercial and OpenSource home automation solutions.                                         |
| Z-Wave                               | Wireless communication protocol optimized for home automation. www.z-wavealliance.org 
