# FAQ

##What is OpenRemote Controller?

A Controller in the automation industry is usually the main CPU of the installation. In the case of OpenRemote it relays the commands from the panels to the target protocols. It acts mainly as a translator between the protocols. In the case of OpenRemote, the controller is Open Source and is meant for open integration. Integrating your own protocol into OpenRemote is made by way of a few classes in the controller. It is free to download and run.

##Does OpenRemote Controller work on Windows, Mac or Linux?
Yes it does. We support all three operating systems.

##Do I Really Need A Controller?
Yes. For automation use-cases, a controller becomes necessary. For example in the case of scripting, or status updates, or reacting to events from sensors without user input, you need an "always-on" platform.

##Do I need to install one OpenRemote Controller per room?
No. Usually you don't. The OpenRemote Controller integrates via IP network so you just need one controller instance accessible somewhere in your local IP network.

For a residential installation, normally one controller is sufficient.

How about my serial or infrared connections, how can I use them if the OpenRemote controller is in other room/in my basement?

We generally recommend using your local IP network as the backbone of your installation to reach devices and control points from room-to-room. To transfer control commands from IP network to other media (serial, infrared, USB), we recommend IP-to-serial|infrared translators. You should install these micro-controller units close to where they are needed (for example, IP-to-infrared near your TV/media center) and only install and maintain a single controller per installation that contains a more powerful CPU and programming logic (the "brains" of the installation, if you will).

This type of installation topology (master controller CPU + many micro-controller based protocol translation units) will scale best.

##Does OpenRemote Controller scale?

Yes. We scale from small starter installations (single-room media center) to residential installations (per house) to large commercial/industrial installations (per building/apartment complex).

The OpenRemote Controller uses a tried and tested Java frameworks that have been deployed across businesses to serve mission-critical business applications, with high-availability and clustering requirements serving millions of transactions per day.

This same framework is used by OpenRemote in automation. We can scale the OpenRemote Controller software from a roughly $35 Raspberry Pi hardware (media center or typical single-house residential setup) to large servers running multiple instances of controller for back-up/fail-safe purposes and serving entire building complex.

The server technology in OpenRemote Controller in both cases is the same, and it is designed to scale from small to large.

##Does OpenRemote Controller support security?

Yes. The HTTP connection between OpenRemote panels and controller can be encrypted using HTTPS. Authentication can be configured to restrict device control to specific users or devices.

##Can OpenRemote Controller be customized for our purposes?

Yes. The controller is built with modularity in mind which allows custom plugins to be added, or existing components modified or replaced.

Please see our Developer Documentation for more details. For development support and custom development services, please contact us.