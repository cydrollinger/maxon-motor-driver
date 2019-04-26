<a href="https://elec-real.com"><img src="/docs/github.png" ></img></a>

>Electronic Realization L.L.C.								   
>Design: Maxon Motor Driver with Bluetooth v4.2/5.0		   
>Engineer: Cy Drollinger								   
>Date: 4/18												           
>Email: cy@elec-real.com								   
>Address: 2023 Stadium Dr Suite 2B #210 Bozeman, MT 59715				   
>Phone: 406-539-8117	

**NOTE:**
 This design has been tested and functions as specified. The design is provided gratis, so, please 
 think critically while utilizing and or redesigning. Open electronic circuitry can be dangerous due 
 to easily shorting circuits which can generate immediate and intense heat resulting in fire. Conversation is
 welcome to improve this design and repository, but, be advised ER is a professional design house and
 monetary compensation is required for additional work toward this design enabling your success.			   
	 
![Maxon Motor Driver](/docs/pictures/ICSP.png)

**PURPOSE:**
The puspose of this design was to implement a 3 phase DC motor driver for a high speed 8mm dia motor by
Maxon. The system utilizes the nRF52832 by Nordic Semicondutor which outputs bluetooth v4.2/5.0 wireless
communication. The device also boast the mpu9250 a 9 axis inertial sensor as well as a TDK's MEMs micro phone. 

>**File Arcitecture with a terse description**


* FOLDERS:
	* docs		: datasheets charging IC and battery holder
	* hardware	: eagle cadsoft(v7.7) hardware design files 	
		* library		: eagle part files 
		* manufacturing	: files required to produce the design
			* bom	: files created to order the parts	
			* gerber	: files generated to manufacture the board
			* <a href="https://oshpark.com/shared_projects/ryMoScdj"><img src="https://oshpark.com/assets/badge-5b7ec47045b78aef6eb9d83b3bac6b1920de805e9a0c227658eac6e19a045b9c.png" alt="Order from OSH Park"></img></a>
	* readme.md	: this file
	
[![](http://img.youtube.com/vi/88ky35AwuC4/0.jpg)](http://www.youtube.com/watch?v=88ky35AwuC4 "maxon motor driver")