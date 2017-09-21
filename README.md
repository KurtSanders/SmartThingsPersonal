# SanderSoft SmartThings Repository

![Kurt the Geek](https://raw.githubusercontent.com/KurtSanders/MySmartThingsPersonal/master/Geek.jpg)

## My SmartThings Applications

### Garage Door Virtual Contact Sensor SmartApp and Device Handler (DTH)
- Eliminates the need for using physical zwave sensors attached to MyQ controlled garage doors
- The DTH works with IFTTT or customized Python Code (*See info below*)
	- Polls an e-mail account for targeted emails from [Sears Craftsman Assurelink Website](https://assurelink.craftsman.com/) concerning your MyQ controlled garage door activity states (ie. open/close).  
	- Parses those e-mails for open/close state and updates SmartThing virtual contact sensors with garage door status condition.  
	- Works in concert with [MQ Lite SmartApp](https://github.com/brbeaird/SmartThings_MyQ)
		- *Note: Customized Python dameon code not provided for the Raspberry PI server.  Requires knowledge of Python programming language, installed prerequisite software and setting up a dameon service.  Contact me for information of my code or create your own*

### Open Door Sensor SmartApp
- Reports on doors with contact sesnors that are left open for a specified period of time.

### Button Controller {Legacy} SmartApp
- Works with multiple Minimote devices using child apps

### Alarm Panel Monitor
- Works with Vista/Honeywell Alarms

### Alarmdecoder SmartApp
- Provides integration with Alarm Decoder hardware

### BWA Device Type Handler (DTH)
- Provides cloud connected status of a Balboa Model 20p WiFi connected Hot Tub 

### RestServer Device Type Handler (DTH)
- Provides Ping Response from a local network REST API Webserver

### My MimoLite Device Handler (DTH)
- Provides for the dual capabailities (switch/sensor) of the MimoLite device
