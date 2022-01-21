# automation-remote

Components:
- Remote for the ceiling lamp working on 2.4Ghz (SUNGTU V853G-2-5)
![remote-front](https://user-images.githubusercontent.com/5171984/150520516-1c691788-a622-4e30-a1f0-67fc25274865.png)
![remote-back](https://user-images.githubusercontent.com/5171984/150520042-c7bebcc7-5332-4b86-b04e-ae0c667d90e0.png)
![remote-inner](https://user-images.githubusercontent.com/5171984/150520528-069998b1-11b0-425e-967c-a0bbe6aebc54.png)
- ESP8266 mini Wemos with Tasmota
- Optocouplers

Wiring:

Tasmota configuration
- TODO: Add status on load
- Rule1 on Event#lightTrigger DO Backlog Power1 OFF; Delay 2; Power1 ON ENDON

Wiring results:
![remote-wiring-result](https://user-images.githubusercontent.com/5171984/150491491-acfac2f6-0ef5-4ab6-9b94-70ed1b61fd45.png)
