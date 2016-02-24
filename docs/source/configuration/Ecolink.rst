Ecolink
======================

.. _ecolink_config_door_window_sensor:

Door and Window Sensor
-----------------------

.. image:: ../_static/images/ecolink_door_window_sensor.jpg 
   :align: center


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


.. _ecolink_config_tilt_sensor:

Tilt Sensor  
---------------

.. image:: ../_static/images/ecolink_tilt_sensor.jpg 
   :align: center

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


.. _ecolink_config_motion_detector_sensor:

Motion Detector 
------------------

.. image:: ../_static/images/ecolink_home_motion_sensor.jpg 
   :align: center


Wake-up device 
~~~~~~~~~~~~~~~
This device is waken by triggering motion 


Configuration  
~~~~~~~~~~~~~~~

Association group two is intended for any device that is controllable with a Basic Set of 0xFF such as lights, sirens, or chimes. When a Motion sensor is faulted, it will always send a Basic Set of 0xFF to all nodes associated to group two. When the Motion sensor is restored, it is configurable if the Basic Set of 0x00 is sent to all nodes associated to group two. The following table shows the configuration


.. list-table:: 
   :widths: 15 30
   :header-rows: 1

   * - Signal Trigger Device
     - Value
   * - ON  
     - Basic Set of 0X00 is sent when it is restored 
   * - OFF 
     - Basic Set of 0X00 is NOT sent when it is restored  

