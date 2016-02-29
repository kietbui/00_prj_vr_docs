Schlage 
======================

.. _schlage_config_door_lock:

Door Lock  
-----------


.. image:: ../_static/images/schlage_door_lock.jpg 
   :align: center

Configuration  
~~~~~~~~~~~~~~~

.. list-table:: 
   :widths: 15 30
   :header-rows: 1

   * - BEEPER 
     - Description   
   * - ON  
     - Enable beep when a key is pressed 
   * - OFF 
     - disable beep when a key is pressed  

When Vacation Mode is enabled, User Codes will not unlock the lock. Used to ensure lock remains secure while you are away from home. Disable vacation mode to resume normal operation

.. list-table:: 
   :widths: 15 30
   :header-rows: 1

   * - VACATION MODE 
     - Description   
   * - ON  
     - Enable vacation mode 
   * - OFF 
     - Disable vacation mode 

.. Press Schlage button, it is automatically locked 

Enabled by default. When enabled, the  deadbolt can be locked from the outside by pressing the Schlage button and rotating the thumbturn. When disabled, a User 
Code must be entered before rotating the thumbturn. Disabling this feature keeps an unauthorized person from locking the door from the outside.

.. list-table::  
   :widths: 15 30
   :header-rows: 1

   * - LOCK AND LEAVE 
     - Description   
   * - ON  
     - Enable lock and leave 
   * - OFF 
     - Disable lock and leave 

It is automaitcally lock after a mount of time is eslapsed 
.. list-table::  
   :widths: 15 30
   :header-rows: 1

   * - AUTOLOCK 
     - Description   
   * - ON  
     - Send Binary and Basic Set Report 
   * - OFF 
     - Send Binary Report 

.. 
.. list-table:: 
   :widths: 15 30
   :header-rows: 1

   * - LENGTH OF PASSCODE 
     - Description
   * - 4, 5, 6, 7, 8   
     - Set the corresponding length of passcode to door and lock


.. _schlage_config_door_window_sensor:

Door and Window Sensor 
---------------------------


.. image:: ../_static/images/schlage_door_window_sensor.jpg 
   :align: center


Wake-up device 
~~~~~~~~~~~~~~~
This device is waken by triggering open/close event of this device


Configuration  
~~~~~~~~~~~~~~~

Association group two is intended for any device that is controllable with a Basic Set of 0xFF such as lights, sirens, or chimes. When a Door Window sensor is faulted, it will always send a Basic Set of 0xFF to all nodes associated to group two. When the Door Window sensor is restored, it is configurable if the Basic Set of 0x00 is sent to all nodes associated to group two. The following table shows the configuration


.. list-table:: 
   :widths: 15 30
   :header-rows: 1

   * - Signal Trigger Device
     - Basic Set Report    
   * - ON 
     - Basic Set Report 00 is sent when it is restored  
   * - OFF 
     - Basic Set Report 00 is NOT sent when it is restored


.. _schlage_config_motion_detector_sensor:

Motion Detector 
------------------

.. image:: ../_static/images/schlage_home_motion_sensor.jpg 
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


