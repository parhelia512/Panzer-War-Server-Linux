# Server

This is Panzer War Game Server for Linux.

## Installation & Runing with default settings

Video Tutorial: <https://youtu.be/asSYQOijpvU>

1. Open ternimal

Requirements:
git
screen

For Cent OS

1. yum install git -y
2. yum install screen -y

3. git clone <https://github.com/Doreamonsky/Panzer-War-Server-Linux.git>
4. cd Panzer-War-Server-Linux
5. chmod +x ./runServer.sh
6. ./runServer.sh

Tip: Press ctrl+a crtl+d to exit the server without closing it. And screen -r GameServer to reconnect it.

## FireWare

You need to allow TCP 7777 port.

1. firewall-cmd --permanent --add-port=7777/tcp
2. firewall-cmd --reload

## Advance Usage

Usage:

./Server.x86_64 -clientType Server -gameMap Desert -port 7777 -modSupport Deny -playerCount 16 -battleRank 5 -battleRankRange 2 -batchmode -nographics

You can modify the parameters to suit your desires.
