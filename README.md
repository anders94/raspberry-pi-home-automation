raspberry-pi-home-automation
============================
A node.js based home automation system based around the Raspberry Pi. For background around this project:

[![The Well Tempered Hacker](http://img.youtube.com/vi/SEAQVXHSwg4/0.jpg)](http://www.youtube.com/watch?v=SEAQVXHSwg4)

Installation
============
To get started, clone the repository and install the required dependencies.

    git clone https://github.com/anders94/raspberry-pi-home-automation.git
    cd raspberry-pi-home-automation
    npm install

Server
======
The server uses MQTT, a lightweight messaging channel over TCP, and presents a
pub-sub like interface to clients. Clients connect and can publish messages which
get copied to all other connected clients.
