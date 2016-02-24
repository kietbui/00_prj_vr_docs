Aeotec 
======================

Please note that the following devices should be waken up before doing configuration  


Door and Window Sensor  
--------------------------

Wake-up device 
~~~~~~~~~~~~~~~~~~

The Aeotec Door and Window Sensor can be made to stay awake for 10 minutes by firmly tapping the security switch 3 times in quick succession. Once the Aeotec Door and Window Sensor has been woken, the LED will blink every few seconds indicating that it is now awake.



.. image:: ../_static/images/aeotec_door_window_configuration.jpg 
   :align: center

Configuration   
~~~~~~~~~~~~~~~~

.. list-table:: 
   :widths: 15 30
   :header-rows: 1

   * - Signal Trigger Device
     - Description
   * - ON 
     - When it is open, the Basic Set of 0XFF is sent. If It is closed, the Basic Set of 0x00 is sent.
   * - OFF 
     - When it is open, the Basic Set of 0x00 is sent. If it is closed, the Basic Set of 0xFF is sent.


.. list-table::  
    :widths: 15 30
    :header-rows: 1

    * - Signal Trigger Controller
      - Description 
    * - 0x00
      - When it is open, the Binary Report of 0XFF is sent. If It is closed, the Binary Report of 0x00 is sent.
    * - 0xFF
      - When it is open, the Binary Report of 0x00 is sent. If it is closed, the Binary Report of 0xFF is sent.


.. list-table::  
   :header-rows: 1

   * - Report to
   * - Device & Controller with Battery Information
   * - Device & Controller
   * - Device
   * - Controller
   * - Controller with Battery Information
   * - Battery Information



Recessed Door Sensor (Gen 5) 
-----------------------

Wake-up device 
~~~~~~~~~~~~~~~

The Aeotec Recessed Door Sensor can be made to stay awake for 10 seconds by pressing the z-wave button for 6 seconds.

.. image:: ../_static/images/aeotec_recessed_door_wakeup.jpg 
   :align: center

Configuration   
~~~~~~~~~~~~~~~~~~~~~~~


.. list-table:: 
   :widths: 15 30
   :header-rows: 1

   * - Signal Trigger Device
     - Description
   * - ON 
     - When it is open, the Basic Set of 0XFF is sent. If It is closed, the Basic Set of 0x00 is sent.
   * - OFF 
     - When it is open, the Basic Set of 0x00 is sent. If it is closed, the Basic Set of 0xFF is sent.


.. list-table::  
    :widths: 15 30
    :header-rows: 1

    * - Signal Trigger Controller
      - Description 
    * - 0x00
      - When it is open, the Binary Report of 0XFF is sent. If It is closed, the Binary Report of 0x00 is sent.
    * - 0xFF
      - When it is open, the Binary Report of 0x00 is sent. If it is closed, the Binary Report of 0xFF is sent.


.. list-table::  
   :header-rows: 1

   * - Report to
   * - Device & Controller with Battery Information
   * - Device & Controller
   * - Device
   * - Controller
   * - Controller with Battery Information
   * - Battery Information



Heavy Duty Smart  
------------------

Configuration   
~~~~~~~~~~~~~~~~

.. list-table::  
   :widths: 15 30
   :header-rows: 1

   * - Configuration 
     - Description
   * - Enable  
     - Allow the configuration  
   * - Disable   
     - Not allow the configuration 


.. list-table::  
   :widths: 15 30
   :header-rows: 1

   * - Notification 
     - Description
   * - Nothing 
     - Do not send the notification when the load of heavy duty smart is changed 
   * - Basic Report  
     - Send the Basic Report when the load of heavy duty smart is changed



Smart Dimmer
--------------

Configuration   
~~~~~~~~~~~~~~~~
.. list-table::  
   :widths: 15 30
   :header-rows: 1

   * - Configuration 
     - Description
   * - Enable  
     - Allow the configuration  
   * - Disable   
     - Not allow the configuration 



.. list-table::  
   :widths: 15 30
   :header-rows: 1

   * - Notification 
     - Description
   * - Nothing 
     - Do not send the notification when the load of heavy duty smart is changed 
   * - Basic Report  
     - Send the Basic Report when the load of heavy duty smart is changed



Siren
--------

Configuration   
~~~~~~~~~~~~~~~~

.. list-table::  
   :header-rows: 1

   * - Sound Type  
     - Description 
   * - Sound type 1
     - Change to sound type 1  
   * - Sound type 2  
     - Change to sound type 2
   * - Sound type 3 
     - Change to sound type 3
   * - Sound type 4  
     - Change to sound type 4
   * - Sound type 5 
     - Change to sound type 5

.. list-table::  
   :header-rows: 1

   * - Volume  
     - Description 
   * - Low  
     - Change volume low 
   * - Medium 
     - Change volume medium
   * - High  
     - Change volume high 

.. list-table::  
   :widths: 15 30
   :header-rows: 1

   * - Notification 
     - Description
   * - Nothing 
     - Do not send the notification when the state of siren is changed 
   * - Basic Report
     - Send the Basic Report when the state of siren is changed


Multilevel sensor 5
---------------------

Configuration   
~~~~~~~~~~~~~~

.. list-table::  
   :widths: 15 30
   :header-rows: 1

   * - Motion Detection  
     - Description
   * - Enable 
     - Enable motion detection  
   * - Disable 
     - Disable motion detection 


.. list-table::  
   :widths: 15 30
   :header-rows: 1

   * - Sensor Report Type  
     - Description
   * - Temperature  
     - Report temperature  
   * - Humidity 
     - Report humidity 
   * - Luminance  
     - Report luminance 
   * - Battery 
     - Report battery


.. list-table::  TBD
   :widths: 15 30
   :header-rows: 1

   * - Report Interval   
     - Description
   * -     
     -   


.. list-table::  TBD
   :widths: 15 30
   :header-rows: 1

   * - Delay time   
     - Description
   * -    
     -  
