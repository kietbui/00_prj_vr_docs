Aeotec based device 
======================

Please note that the following devices should be waken up before do configuration  

Door and Window Sensor  
--------------------------

Wake-up device 
~~~~~~~~~~~~~~~~~~


.. list-table:: Door and Window Sensor 
   :widths: 15 30
   :header-rows: 1

   * - Signal Trigger Device
     - Basic Set Value 
   * - ON 
     - Open: FF. Close: 00
   * - OFF 
     - Open: 00. Close: FF


.. list-table:: Value Trigger Controller 
    :widths: 15 30
    :header-rows: 1

    * - Value
      - Binary Report 
    * - 0x00
      - Open: FF. Close: 00
    * - 0xFF
      - Open: 00. Close: FF



Recessed Door Window Sensor  
-------------------------------

.. list-table:: Basic Set Report 
   :widths: 15 30
   :header-rows: 1

   * - Value 
     - Basic Set Report 
   * - ON 
     - Open: FF. Close: 00
   * - OFF 
     - Open: 00. Close: FF



.. list-table:: Which Report 
   :widths: 15 30
   :header-rows: 1

   * - Value 
     - Binary Report  
   * - Binary, Basic 
     - Send Binary and Basic Set Report 
   * - Binary 
     - Send Binary Report 
   * - Basic  
     - Send Basic Report 
   * - Nothing
     - Send neither Basic Set nor Binary Report 

