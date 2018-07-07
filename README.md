

This repository comprises the second part of our fog planning project, which is the fog facility simulation. The source code here is a testbed for a simple fog network. This work employed the fog framework: [fogframe](https://github.com/keyban/fogframe/blob/master/logo_fogframe.png) and please feel free to test it and adapt it to future work. Don't forget to include the license of FogFrame -- Apache 2.0 © [Kevin Bachmann](kevin.bachmann@gmx.at).


The fogframe embodies a set of microservices developed in Java together forming a researched fog computing framework. The project consists of the cloud-fog middleware, fog control node, fog cell, hostmonitor, and the fog data.

* <b>Cloud-fog middleware (CFM):</b> Cloud middleware that handles the service deployment in the cloud and the data propagation to cloud services.
* <b>Fog control node (FCN):</b> Control node that orchestrates subjacent fog colonies consisting of other fog control nodes and fog cells. 
* <b>Fog cell (FC):</b> Node connected to fog control nodes and IoT devices to execute services and propagate data to a parent fog control node.
* <b>Fog data:</b> Models and Util classes shared amongst the other components.
* <b>Hostmonitor:</b> Monitoring applicatoin that monitors the host and sends the data to a corresponding Redis database for further processing.

## Software Specs
Tested with the following software versions:
* Docker 1.12.2
* Java 8
* Apache Maven 3.2.3
* OpenStack Cloud (Keystone v2.0, Nova)
* Hypriot OS (preinstalled on the Raspberry Pis)



## License

Fog Facility Planning -- Apache 2.0 [Decheng Zhang](qrafzv88@gmail.com)
FogFrame -- Apache 2.0 © [Kevin Bachmann](kevin.bachmann@gmx.at)


## Sources
Cloud graphic by <a href="http://www.flaticon.com/authors/yannick">Yannick</a> from <a href="http://www.flaticon.com/">Flaticon</a> is licensed under <a href="http://creativecommons.org/licenses/by/3.0/" title="Creative Commons BY 3.0">CC BY 3.0</a>. Made with <a href="http://logomakr.com" title="Logo Maker">Logo Maker</a>
