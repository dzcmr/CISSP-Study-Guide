# Communication and Network Security.md

[Back to Home Page](https://github.com/so87/CISSP-Cheat-Sheet-) <br />
[To next domain! - D5 - Identity and Access Management](https://github.com/so87/CISSP-Cheat-Sheet-/blob/master/D5%20-%20Identity%20and%20Access%20Management.md) <br />

### Implement secure design principles in network architectures
* Open System Interconnection (OSI) and Transmission Control Protocol/Internet Protocol (TCP/IP) models
</br>Layers:
  </br>7. Application  -  Google chrome
  </br>6. Presentation -  MPG / JPEG / Data compression (often) / encryption (often)
  </br>5. Sessions     -  PPTP / ZIP / SCP / SIP / RPC
  </br>4. Transport    -  Segments and Sequencing / TCP / UDP
  </br>3. Network      -  ^ Takes frames and organizes into packets IP Addressing
  </br>2. Data Link    -  Ehternet / Frame Relay / Token Ring / L2TP / PPP / CDP / Wifi / Generates Frames MAC Address
  </br>1. Physical     -  Electrical/Optical Current
</br>Think of it like you are trying to send a package of cookies to someone else half way across the world.

TCP/IP Model
</br>Layers:
  </br>4. Application   (OSI: Session, Presentation, Application)
  </br>3. Host-to-Host Transport (OSI: Transport)
  </br>2. Internet (OSI: Network) 
  </br>1. Network access (OSI: Physical and Data Link)


* Wifi Connectivity - CSMA/CA - IEE 802.11 (a,g,n OFDM)
* Bluetooth - CDMA - IEEE 802.15 - 2.4Ghz - FHSS (modulation technique)


* Internet Protocol (IP) networking - DHCP on LAN.  Lan connects to WAN. ISPs route traffic
* Implications of multilayer protocols
* Converged protocols - providing industrial controls, storage, voice, etc via Ethernet(tcp/udp)
* Software-defined networks - seperates a router's control plane from data forwarding plane
* Wireless networks - WEP, WPA, WPA2. 802.11 is the wireless standard
Many varieties of EAP
  * LEAP : Cisco-proprietry, very bad
  * EAP : IEE 802.1X standard
  * EAP-TLS : requires server/client certificates
  * EAP-TTLS : allows passwords for client-side authentication
  * PEAP : similar to EAP-TTLS, developed by cisco and microsoft
* Firewalls - network segmentation
  *  Packet Filter: no decisions. set list of allow rules
  *  Stateful: slower but more secure. compare packets to previous ones. 
  *  Proxy: acts as middle man on network. does not give anything back if doesn't meet proxy rules
  *  application-layer proxy: make decissions on like HTTP, and layers 3 and 4
* VoIP - voice over IP
  * RTP for streaming
  * SRTP for secure communication

### Secure network components
* Operation of hardware
* Transmission media - properly encrypt media
* Network Access Control (NAC) devices - 802.1X is port based network access control
* Endpoint security - deep packet inspection. email filtering. 
* Content-distribution networks - series of distributed caching servers to imporve performance and lower latency. They find closest servers to you and go


### Implement secure communication channels according to design
Figure out what type of security mechanisms are best for scenarios you get on the test
* Voice
* Multimedia collaboration
* Remote access
* Data communications
* Virtualized networks

[Back to Home Page](https://github.com/so87/CISSP-Cheat-Sheet-) <br />
[To next domain! - D5 - Identity and Access Management](https://github.com/so87/CISSP-Cheat-Sheet-/blob/master/D5%20-%20Identity%20and%20Access%20Management.md) <br />
