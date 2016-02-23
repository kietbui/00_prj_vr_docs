Ecolink based devices
======================

Tilt Sensor  
---------------

Wake-up device 
~~~~~~~~~~~~~~~
This device is waken by rotation 


Configuration  
~~~~~~~~~~~~~~~

Association group two is intended for any device that is controllable with a Basic Set of 0xFF such as lights, sirens, or chimes. When a Tilt sensor is faulted, it will always send a Basic Set of 0xFF to all nodes associated to group two. When the Tilt sensor is restored, it is configurable if the Basic Set of 0x00 is sent to all nodes associated to group two.  The following table shows the configuration

.. list-table:: 
   :widths: 15 30
   :header-rows: 1

   * - Signal Trigger Device
     - Description
   * - ON  
     - Basic Set of 0X00 is sent when it is restored 
   * - OFF 
     - Basic Set of 0X00 is NOT sent when it is restored  


Door and Window Sensor
-----------------------

Wake-up device 
~~~~~~~~~~~~~~~
This device is waken by triggering open/close event of this device


Configuration  
~~~~~~~~~~~~~~~

Association group two is intended for any device that is controllable with a Basic Set of 0xFF such as lights, sirens, or chimes. When a Tilt sensor is faulted, it will always send a Basic Set of 0xFF to all nodes associated to group two. When the Tilt sensor is restored, it is configurable if the Basic Set of 0x00 is sent to all nodes associated to group two. The following table shows the configuration


.. list-table:: 
   :widths: 15 30
   :header-rows: 1

   * - Signal Trigger Device
     - Value
   * - ON  
     - Basic Set of 0X00 is sent when it is restored 
   * - OFF 
     - Basic Set of 0X00 is NOT sent when it is restored  