# klipper_snap
Implementation of klipper into the snap ecosystem for use on Ubuntu Core devices.


## TODO

- Set up snap enviro
    - yaml
- Port Klipper into snap
- control snap refresh behavior to prevent reboot during print
    - stop-command setting in snap daemon allows a service to reach a stoppable state first. Need to see if any time limits exist here.
    - gates or snapctl control
- connect to printer
- connet to other interfaces
    - octoprint
    - mainsail
    - fluidd