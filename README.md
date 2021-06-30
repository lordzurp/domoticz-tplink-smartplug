# domoticz-tplink-smartplug
Domoticz plugin for tp-link HS100/HS103/HS110 smartplug (set HS103 as HS100 and that's it !)

forked from https://github.com/dahallgren/domoticz-tplink-smartplug

Clone repository into your Domoticz plugins folder

    cd domoticz/plugins
    git clone https://github.com/lordzurp/domoticz-tplink-smartplug.git

Restart domoticz

    sudo service domoticz.sh restart


#### lordzurp 07-2019
* change sensor type for W and Wh correctly displayed
* add v2 type (different measure output : mV vs V, mA vs A, mW vs W, Wh vs kWh)
* add refresh of smartplug status
