### 1.1 Description 
The extension of a unidirectional RKE system to a bidirectional RKE system is known as a bidirectional communication system. 
It's an automatic vehicle security system that unlocks the door on approach or when the door 
handle is lifted, then locks it when the user steps away or touches the car on leaving. 

### 1.2 State of Art  
The system is made up of two parts: a key fob and a vehicle module, both of which
contain transceivers that connect wirelessly to detect each other using a magnetically coupled radio 
frequency signal. The vehicle's module sends out encoded messages all the time, and when the key fob is within range,
it reacts. If the encrypted communications are correct, the vehicle and key fob are recognized as one unit, and the door opens. Before the systems disarm, 
the Bicom systems emit the signal and receive and require a return signal from the key. 

### 1.3 General System Description 
##### 1.3.1 System functions 
The BiCom system provides the following car access functions: remote keyless entry, passive entry (PE),
passive start (PS) and passive lock (PL). In addition, it also includes the following system configuration functionalities: 
a learning procedure for pairing vehicle and key fob, RKE rolling code synchronization, and end-of-line parameters (RSSI compensation, etc.). When the driver 
approaches the vehicle, a secure wireless communication between the key fob and the vehicle control unit authenticates the fob. Bi-directional wireless 
communication authenticates the key fob and the vehicle in both one-way and two-way systems. In one-way RF systems the LF downlink serves to wake up the key and to 
receive commands as well as data for the authentication process. The fob then sends the response to the vehicle via RF uplink. In two-way RF systems the LF downlink only 
serves to wake up the key fob and to establish the RF up-/downlink. The bi-directional RF link handles the entire communication during the authentication process. 

##### 1.3.2 Remote Keyless Entry 
In addition to the lock and unlock function, you can include supplemental remote functions in the key fobs even with the system. 
For example, if the driver wants to lock the doors via RKE, the vehicle needs to check for active keys inside the vehicle cabin. 
If a paired key fob is detected inside the cabin, it must be disabled for the next passive entry request.  

##### 1.3.3 Bi-directional Authentication 
The bi-directional procedure offers increased security compared to uni-directional authentication. 
The fob authenticates the vehicle before replying, and in a second step, the vehicle authenticates the fob. Both steps use different secret keys. 

##### 1.3.4 Communication Interfaces 
A system communicates bidirectionally via three different communication channels: 
• Bidirectional, short-range (4 to 5cm) LF communication  
• Unidirectional, medium-range (about 2 to 3m) 3D-LF communication  
• Long-range (10 to 30m) RF communication, both one and two-way RF 

### 1.4 4W’s and 1H    
Who: Those that own modern smart cars that have a keyless entry system 
What: The Bicom system is a feature of Keyless Enter-N-Go — Passive Entry and is an addition to the vehicle's Remote Keyless Entry (RKE) system. 
When: unlocking the door on approach or when the door handle is pulled and locking it when the user walks away or touches the car on exit. 
Why: vehicle is usually attained by sending a radio frequency signal from a remote transmitter to the receiver in the car. 
How:  It work using radio signals that are emitted from the car and a key fob that searches for those signals 


