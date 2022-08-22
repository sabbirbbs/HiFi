# HiFi is just a simple modification of ZiFi to solve deauth problem by changing deauth packet to work on channel 1.Wish this will work for you.
# ZiFi
Wifi hacking tool using ESP8266 ( Evil-Twin method )

<p align="center">
<a href="https://github.com/sankethj/z-cam/"><img title="Tool" src="https://img.shields.io/badge/Tool-ZiFi-blue.svg?style=for-the-badge"></a>
<a><img title="Version" src="https://img.shields.io/badge/Version-1.0-blue.svg?style=for-the-badge"></a>
<a><img title="Maintainence" src="https://img.shields.io/badge/Maintenance-Yes-blue.svg?style=for-the-badge"></a>
</p>

![logo](/Images/ZiFi.png)

## FEATURES :
* [+] Deauth
* [+] Evil-Twin
* [+] User Interface

## TESTED ON :
* Nodemcu
* Probably will work in all-other boards too...

## INSTALLATION :
* Install [Arduino IDE](https://www.arduino.cc/en/software)
* Add Esp8266 in Additional Board Manager `http://arduino.esp8266.com/stable/package_esp8266com_index.json`
* Esp8266 board  [NODEMCU](https://www.amazon.in/dp/B010O1G1ES/ref=cm_sw_r_apan_glt_i_MAFEQVVXSRR69JXNYFA3)
* Install your board, choose correct Port.
* Compile and Upload.
* For detailed explanation check on [blogger](https://zansecurity.blogspot.com/2022/02/hacking-wifi-using-esp8266-deauth-and.html)

## CONCEPT :
* Connect to the Access Point named `ZiFi` with password `Eviltwin` from your device.
* Select the target you want (list of available APs refreshes every 15secs - page reload is required).
* Select The Attack Mode. If you choose Deauth it will start deauthing the clients in that network.
* Then Start Evil-twin attack, which will create the clone of the selected network.
* The web interface will be unavailable during Evil-twin attack mode, You need to reconnect.
* Reconnect after some time, it will display you the correct password in Result section.
* For detailed explanation check on [blogger](https://zansecurity.blogspot.com/2022/02/hacking-wifi-using-esp8266-deauth-and.html)


## DEMONSTRATION VIDEO:
[![YOUTUBE](/Images/ZiFi_yt.PNG)](https://youtu.be/pwSO3hhf1vA)

## CONTACT :
[![Telegram](https://img.shields.io/badge/TELEGRAM-Team_ETF-blue?style=for-the-badge&logo=telegram)](https://t.me/Team_ETF)
[![Twitter](https://img.shields.io/badge/TWITTER-SANKETH-blue?style=for-the-badge&logo=twitter)](https://twitter.com/SankethZ4N)
<a href="https://www.youtube.com/channel/UCJnx0yDhcTLWM3ZrAtSvaIw"><img title="YouTube" src="https://img.shields.io/badge/YouTube-Team ETF-blue?style=for-the-badge&logo=Youtube"></a>

## CREDITS :
* [M1z23R](https://github.com/M1z23R)  --> MODIFIED VERSION OF HIS SCRIPT
* [Spacehuhn Technologies](https://github.com/SpacehuhnTech)   --> TEMPLATE
* [125K](https://github.com/125K)     --> TEMPLATE

## WARNING :
Use it only against your own networks and devices!
Please check the legal regulations in your country before using it.
We don't take any responsibility for what you do with this program.

## DONATIONS :
- We don't ask much, if possible feed stray animals in your free time. 
