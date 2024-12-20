Sandbox Application
This repository contains the setup and configuration for the Sandbox Application, including a functional network diagram, IP address tables, and server configuration details. The project demonstrates a virtualized network environment using Ubuntu Server, Ubuntu Desktop, and a Bitnami application server.

Project Overview
This project simulates a network infrastructure featuring:

Gateway Router: Connects and routes traffic between subnets.
Desktop PC: Accesses the application server for testing.
Application Server: Hosts a web server running on a Bitnami WordPress VM.
Features
Network Diagram: A detailed network topology including:

Gateway router
Two subnets
Multiple virtual machines
Application server
Configuration Steps:

Setting up Ubuntu Server, Ubuntu Desktop, and Bitnami VM.
Static IP configuration.
Enabling IP forwarding and routing between subnets.
Functional Test Results:

Successful pings between all devices in the network.
Web server tested and accessible from the desktop.
Hosted Website: The configuration details are hosted on GitHub Pages.
Link: https://mohamedabisheik2506.github.io/SandBoxApplication.github.io/


Repository Contents
index.html: Main HTML file for the hosted website.
images/: Folder containing screenshots of the network diagram and test results.
README.md: Documentation for the project.

Getting Started

Requirements

Install VirtualBox.
Download the following:
Ubuntu Server ISO
Ubuntu Desktop ISO
Bitnami WordPress OVA file

Steps

Clone the repository:

bash
Copy code
git clone https://github.com/MohamedAbisheik2506/SandBox-Applications.git
Follow the configuration steps detailed in the hosted website or index.html.

Functional Test Results

Communication Tests

Ping Results:

Ubuntu Server ↔ Ubuntu Desktop
Ubuntu Server ↔ Application Server
Ubuntu Desktop ↔ Application Server

Web Server Access:

Tested via browser using http://192.168.122.2.
Video Demonstration
Watch the full project demonstration on YouTube:
https://youtu.be/GzSqXAzXNz4


Author
Mohamed Abisheik Mohamed Ali
