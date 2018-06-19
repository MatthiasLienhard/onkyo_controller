# onkyo_controller
Small box to controll onkyo multi room music (and potentially smart home devices)

* Onkyo TX-NR616 7.2 Netzwerk AV-Receiver
  * issues
    * Display is not that good, infos are often missing
    * No screen attached, just projector, does not run often
    * Device is in a sideboard, sometimes left on accidentally
      * in particular if used with spotify, mobile swiches onkyo on but not off again
    * in second room there is no infos, and only the app to controll 
      * the app is inconvinient
  * can be remote controlled with a wifi network api
    * (e.g.) https://github.com/miracle2k/onkyo-eiscp 
* Components
  * ESP32
    * WiFi/BLE    
    * low power
    * arduino ide
  * Li Ionen Akkupack
  * Display (Nextion 3.2 Zoll)
    * https://www.youtube.com/watch?v=D-zgtylBKUc
  * Status LED 
  * some buttons
  * wheel (e.g. for volumen)
  * casing
  * NFC antenna
* main functions:
  * not wired (micro USB for charching)
  * communicates with onkyo via wifi api
  
* Smart home extentions
  * control light, 
  * control heating, 
  * water plants 
  * show weather forcast
   * https://www.youtube.com/watch?v=eI-4_QyVenw
  * ...
