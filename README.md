# Server

This is Panzer War Game Server for Linux.

## Installation & Runing with default settings

1. Open ternimal

Requirements:
git
screen

Cent OS:
yum install git -y
yum install screen -y

1. git clone <https://github.com/Doreamonsky/Panzer-War-Server-Linux.git>
2. cd Panzer-War-Server-Linux
3. chmod +x ./runServer.sh
4. ./runServer.sh

Tip: Press ctrl+a crtl+d to exit the server without closing it. And screen -r GameServer to reconnect it.

## FireWare

You need to allow TCP 7777 port.

## Advance Usage

Usage:

./Server.x86_64 -clientType Server -gameMap Desert -port 7777 -modSupport Deny -playerCount 16 -battleRank 5 -battleRankRange 2 -batchmode -nographics

You can modify the parameters to suit your desires.
