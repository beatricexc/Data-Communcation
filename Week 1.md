# Computer Networking 
*A top-down Approach*



Socket interface = set of rules the sending program must follow so that the Internet can deliver the data to the destination program 

 

**Protocol** = the format and the order of messages exchanged between two or more communicating entities , as well as the action taken on the transmission and/or receipt of a message or other event. 

 

 
**End system** = hosts = devices connected to the internet ( referred to as end systems because they sit at the Internet's edge) . We call them hosts because they host (ie run) application programs such as a Web browser program, a Web Server program, an email client program, or an e-mail server program. 

 

**Clients** = desktop + Mobile PCs, smartphones etc. 

**Servers = more powerful machines that store and distribute web pages, stream video, relay e-mail etc 

 

**Network edge** :  

Desktop computers 

Servers (Web and e-mail) 

Mobile devices 

 

 

**Access Network**  

The network that physically connects an end system to the first router ( aka edge router) on a path from the end system to any other distant end system.  

 

Home Access: DSL (digital subscriber line), Cable, FTTH (fiber to the home), Dial-Up, and Satellite 

 

#### Types of broadband residential access: 

**DSL**: a DSL modem uses the existing telephone line (twisted pair copper wire) to exchange data with a DSLAM( digital subscriber line access multiplexer) located in the telco's local central office (CO) 

The residential telephone line carries both data and traditional telephone signals simultaneously, which are encoded at different frequencies :  

 

A high-speed downstream channel: 50 kHz to 1 MHz band 

A medium-speed upstream channel: 4 kHz to 50 kHz band 

A ordinary two-way telephone channel: 0 to  4kHz band 

 

 

**Cable** : requires special modems, called cable modems and both fiber and coaxial cables are employed, hybrid fiber coax (HFC) 

**CMTS** : cable modem termination system turns the analog signal sent from the cable modems in many downstream homes back into digital format. 

Faster cable network : FTTH = fiber to the home – provides an optical fiber path from the CO (central office) directly to the home. 

**ONT** = optical network terminator which is connected by dedicated optical fiber to a neighborhood splitter connecting about 100 houses onto a single, shared optical fiber, which connects to an OLT  in the telco's CO. 

**OLT** = optical line terminator that provides conversion between optical and electrical signals connects to the internet via a telco router. 

 

Access to the Enterprise (and the Home): Ethernet and WiFi 

 

LAN: used to connect an end system to the edge router  

Ethernet is the preferred access tech , uses twisted-pair copper wire  

Speed access: 100 Mbps or 1 Gbps to the Ethernet switch , whilst servers : up to 1 G or even 10 Gbps 

 

Physical Media 

 

HFC – combination of fiber and coaxial cable 

DSL and Ethernet – copper wire 

Mobile Access Network – radio spectrum 

 

Bits travelling from one end system through a series of links and routers to another end system. 

The source end system first transmits the bit, and shortly thereafter the first router in the series receives the bit; the first router then transmits the bit, and shortly thereafter the second router receives the bit; and so on. ==> The lovely bit passes through a series of transmitter-receiver pairs.  

For each transmitter-receiver pair, the bit is sent by propagating electromagnetic waves or optical pulses across a physical medium ( eg. Coaxial, hybrid, twisted=pair, multimode) 

 

Physical media:  

Guided : 

Unguided :  

 
