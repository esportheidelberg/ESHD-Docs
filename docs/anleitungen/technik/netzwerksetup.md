# Das Netzwerksetup
Ein gutes Netzwerksetup ist wichtig für den reibungslosen Ablauf der E-Sport Tage.

## Learnings bisher
* Immer einen Plan b) für den Fall haben, das doch etwas schief läuft mit dem Internet
* Mehr LAN-Kabel als eigentlich nötig einpacken

## Teamspeak-Docker-Setup
´´´docker
version: '3'
services:
  teamspeak:
    image: mbentley/teamspeak
    environment:
      - TS3SERVER_LICENSE=accept
    volumes:
      - ./data:/data:rw
    ports:
      - '9987:9987/udp'
      - '30033:30033'
      - '10011:10011'
      - '41144:41144'
´´´

## CSGO-Docker-Setup
Bisher nicht auf den E-Sport Tagen verwendet.
´´´docker
version: '3'
services:
  csgo:
    network_mode: "host"
    container_name: csgo-server
    image: cm2network/csgo
    environment:
      - SRCDS_TICKRATE=128
      - SRCDS_TOKEN=INSERTTOKENHERE
    volumes:
      - ./csgo-data:/home/steam/csgo-dedicated/
´´´