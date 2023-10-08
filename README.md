This was created to be used on non RaspberryPI (I use Proxmox with raspios-bullseye for i386 systems), like virual machine in Proxmox 
<br/>
How to use:
<br/>
Like original script: Open your VM/system SSH/terminal and type these commands:
<br/>
cd /home/pi<br/>
sudo wget https://raw.githubusercontent.com/LukaGitH/Gateway/main/gateway_i386.sh<br/>
sudo bash gateway_i386.sh && sudo rm gateway_i386.sh<br/>

Gateway Home Automation & IoT Applications
----------------
[![Build Status](https://app.travis-ci.com/LowPowerLab/RaspberryPi-Gateway.svg)](https://app.travis-ci.com/LowPowerLab/RaspberryPi-Gateway)
[![GitHub release](https://img.shields.io/github/release/LowPowerLab/RaspberryPi-Gateway.svg)](https://github.com/LowPowerLab/RaspberryPi-Gateway)
[![GitHub issues](https://img.shields.io/github/issues/LowPowerLab/RaspberryPi-Gateway.svg)](https://github.com/LowPowerLab/RaspberryPi-Gateway/issues)
[![GitHub pull requests](https://img.shields.io/github/issues-pr/LowPowerLab/RaspberryPi-Gateway.svg)](https://github.com/LowPowerLab/RaspberryPi-Gateway/pulls)
[![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/)

Designed and coded by [Felix Rusu](https://lowpowerlab.com/contact), Low Power Lab LLC
<br/>
Moddified for non ARM based systems by Luka Kurinčič
<br/>

### Features:
- HTTPS secured with self signed certificate
- HTTP `auth_basic` authentication
- responsive & mobile friendly design
- realtime updated via socket.io websockets & node.js backend 
- [neDB](https://github.com/louischatriot/nedb) storage of node data and logs
- [flot](http://flotcharts.org/) front end graphs
- [nconf](https://github.com/indexzero/nconf) for easy global variable configuration maintenance
- [nodemailer](https://github.com/andris9/Nodemailer) for sending email (and SMS relayed via email)
- [Font-awesome](http://htmlpreview.github.io/?https://github.com/dotcastle/jquery-mobile-font-awesome/blob/master/index.html) icons for jQuery-Mobile

### LICENSE
This project is released under [CC-BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/).<br/>
The licensing TLDR; is: You are free to use, copy, distribute and transmit this Software for personal, non-commercial purposes, as long as you give attribution and share any modifications under the same license. Commercial or for-profit use [requires a license](https://lowpowerlab.com/contact).
For more details see the [LICENSE](https://github.com/LowPowerLab/RaspberryPi-Gateway/blob/master/LICENSE)

### Details & Setup Guide
Please see the [PiGateway Guide](https://lowpowerlab.com/guide/gateway/) for all details requires to install this software.

### Video Overview & Demo
https://www.youtube.com/watch?v=F15dEqZ4pMM

### 3rd party custom gateway setup overview
https://www.youtube.com/watch?v=DP83RJeTpUY
