**Project Abstract:**

The goal of this sub-project is to create a new embedded controller system for plastic recycling and manufacturing
equipment. 

The current system can be viewed on the injection machine located here:
https://minufacture.com/collections/plastic/products/injection-machine

This machine was derived from the original Precious Plastic Injection Machine: https://www.onearmy.earth/news/injection-machine

The current plastic electrical system contains two MYPIN TA temperature controllers that use PID and PWM to drive
SSRs connected to heating elements monitored by K thermocouples. The system also has a time-controlled relay (not
shown) that is used drive and hold a pneumatic piston for a set time duration.

The new embedded controller system should replace the two MYPINS and the time-controlled relay with a single
embedded microcontroller system (e.g. Beagle Bone Black, Raspberry Pi). The system should work stand alone and
connect to WifI. This includes a user interface that replicates the ability to set temperatures/times, view current state,
and operate the device. When connected to the internet, the embedded controller should act as an IOT endpoint with
connections to the cloud via services like AWS IOT core. Messaging services, like MQTT, to the cloud will allow for data
collection, future data analytics, and remote device monitoring /control.

**Deliverables:**

  - Trade Study - Embedded Controller and electronics configuration  
  - Schematic / Architecture Drawing  
  - Software Requirements Specification  
  - Software Design Document  
  - Software Test Report  
  - Demonstration  
  - Software
  
