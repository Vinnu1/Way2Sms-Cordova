# Prerequisites

Basic knowledge of Cordova.
Way2SMS account through which messages will be send.

# Intro

This is a cordova application which can send messages directly via Way2SMS Api.

# Setup

All the files except the files in PHP folder are Cordova files.
The two files in PHP folder should be uploaded on a host/server to perform backend operations.

Cordova Plugins needed for this application are -
 1) Contact Plugin
 2) Splashscreen Plugin

All the cordova files will replace your initial files which are created on creating a new application.

In index.html and index.js, the YOUR_PHP_PAGE should be replaced by the address of sendmessage.php file
on your server.

In PHP file sendmessage.php, you have to provide your account number and password of Way2SMS.

# Credits
The Way2SMS api is made by kingster and can be found (here)[https://github.com/kingster/Way2SMS-API].
