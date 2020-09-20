# cbp-config

1. Install Raspberry Pi OS with desktop and recommended software.
2. Use Balena Etcher on a SD card with min 16gb.
3. Put the SD card on Raspberry Pi and turn on.
4. Connect to Wifi.
5. Execute on terminal commands:

```sh
git clone https://github.com/jpgimenez/craftbeerpi3 
cd craftbeerpi3  
sudo ./install.sh  
```

6. Enable autostart and restart.
7. Enter localhost:5000 on the browser.
8. Install addons:
* AutoStartFermenter
* OneWireTweaks (não oficial - https://github.com/diogavila/cbpi-OneWireTweaks)

9. Restore database.

```sh
git clone https://github.com/diogavila/cbp-config.git
sudo cp cbp-config/craftbeerpi.db craftbeerpi3/
sudo /etc/init.d/craftbeerpiboot restart
```
