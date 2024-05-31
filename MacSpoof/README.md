## Requirements
__Rooted Device  
[LSPosed](https://github.com/LSPosed/LSPosed)  
[MACsposed](https://github.com/DavidBerdik/MACsposed)  
[Termux](https://github.com/termux/termux-app/releases)__  

## Steps

* Flash LSPosed
* Install the module
* Enable the module and restart
* Turn it on in Quick Settings
* Enter the command in Termux:
  
  ```
  su -c ip link set wlan0 address
  ```

__Note: This will disable MAC address randomization__

##

The change will remain until you restart the phone or until you turn the module off from Quick Settings

The netwrok interface might be different in your device  
Check the correct one using
  ```
su -c ip link show
```
