### **Thunder Chicken** - *Kinda like Rygel the Sixteenth, The Dominar of the skies...*

**Description:** An open source integrated ESP32 based flight controller with integrated 433 MHz LORA long range radio and dual band (1.3 / 3.5 GHz) video transmitter.

Additional details and progress of this project can be found at the Laup-X RC blog here: https://laup-x-rc.blogspot.com/

---

**High Level Features:**
* RC
	* 6 x 0.1" RC I/O pins
	* Each pin supports the one of the following functions
		* (TODO) PWM
		* (TODO) PPMSum
		* (TODO) S.Bus
		* (TODO) UART (Max 2 available)
			* (TODO) Protocol support for eagletree open telemetry
			* (TODO) Protocol support for Crossfire telemetry (CRSF)
	* (TODO) Arbitrary Over the Air (OTA) PWM -> Output PWM slot mapping
		* (TODO) Support RSSI and LQI as additional data sources

* LED
	* (TODO) WS2812 Support
		* Max String Lenght: xxx
		* (TODO) Uses the Infared Remote Controller (IRC) peripheral to drive the WS2812 protocol with low CPU utilization
	* (TODO) Single switched VBatt output for headlight/passive LED strip
		* Support for 3 pin 0.1" pololu style regulator for alternate voltage output

* Lost Model Prevention
	* (TODO) Secondary 1S 100 mAh Backup power lipo 
	* (TODO) 88 dB Buzzer
	* (TODO) LORA SF12 Position Beacon: A very robus low datarate digital becon sending the last know position
	* (TODO) FM audio beacon: Works like the openLRS multi-tone beacon

* Video
	* (TODO) Maxim MAX7456 OSD
	* (TODO) Video input selection switch
		* (TODO) Select between 2 external sources
			OR
		* (TODO) 1 External source and one board mounted fatshark style VRX module
	* (TODO) Analog output for control of an analog cameras internal OSD simulating external joystick button presses
		* (TODO) Doubles as a uart output to support sending commands to a runcam split
	* (TODO) 1.3 GHz VTX
		* +30 dBm power output
		* 1.1 GHz - 1.35 GHz tune range
		* L1 GPS notch filter (1575.42 MHz)
	* (TODO) 3.5 GHz VTX
		* +16 dBm power output
		* 3.4 Ghz - 3.7 GHz tune range


---




