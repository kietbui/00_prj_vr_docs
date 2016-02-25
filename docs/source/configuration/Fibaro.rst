Fibaro 
======================

Door and Window Sensor    
----------------------

Wake-up device 
~~~~~~~~~~~~~~~
This device is waken by opening/closing  


Configuration   
~~~~~~~~~~~~~~~~

The Door and Window Sensor can send a dimmer value to the associated devices when it is open. And the dimmer value is either from 1 to 99 or 255.  

.. list-table::  
   :widths: 15 30
   :header-rows: 1

   * - Dimming level 
     - Description    
   * - ON  
     - Send value of 255 when the door is opened  
   * - 80
     - Send value of 80 when the door is opened 
   * - 50
     - Send value of 50 when the door is opened
   * - 25
     - Send value of 25 when the door is opened
   * - 10
     - Send value of 10 when the door is opened


.. _fibaro_config_flood_sensor:

Flood sensor     
----------------------


Wake-up device 
~~~~~~~~~~~~~~~
This device is waken by opening/closing


Configuration   
~~~~~~~~~~~~~~~~ 

The following configuration determines a type of command frame sent by the Sensor in case flooding has been detected or cancelled.

.. list-table::  
   :widths: 15 30
   :header-rows: 1

   * - Alarm Type
     - Description    
   * - Alarm Water   
     - Send an ALARM WATER command when the flooding has been detected   
   * - BASIC SET 
     - Send a Basic Set command when the flooding has been detected  



The following configuration determines if an alarm is sent to the devices when either tamper or flooding happens.  

.. list-table::  
   :widths: 15 30
   :header-rows: 1

   * - Signal Trigger Device 
     - Description    
   * - Nothing     
     - Do not send nether tamper nor flooding event     
   * - Flooding    
     - Send flooding event    
   * - Tampter 
     - Send tamper event 
   * - Flooding, tampter 
     - Send flooding and tamper event 


When the flooding event is triggered, it will send a Flood Alarm.
When the flooding event is ceased, it will send another Flood Alarm which cancels the flooding event. 
The following configuration is to configure a time period that the Flood Alarm is sent since the flooding event is ceased. 

.. list-table::  
   :widths: 15 30
   :header-rows: 1

   * - Alarm Cancelation Delay 
     - Description    
   * - 0 to 3600
     - A period that the Flood Alarm is sent since the flooding event is ceased. 


.. _fibaro_config_motion_detector_sensor:

Motion sensor     
----------------------

Wake-up device 
~~~~~~~~~~~~~~~
This device is waken by making a motion in front of the device


Configuration   
~~~~~~~~~~~~~~~~ 

When the motion event is triggered, it will send a Motion Alarm.
When the motion event is ceased, it will send another Motion Alarm which cancels the motion event. 
The following configuration is to configure a time period that the Motion Alarm is sent since the motion event is ceased. 

.. list-table::  
   :widths: 15 30
   :header-rows: 1

   * - Motion Alarm Cancelation Delay 
     - Description    
   * - 1 to 65535
     - A period that the Motion Alarm is sent since the motion event is ceased. 


.. An example of configuration    
.. ~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 

