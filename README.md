# dentalintel-windows-app
Dental Intel Desktop Version

# Installation
## Requirements
Nodejs version 6.4.0 or higher
NPM version 3 or higher
Nodejs download it here https://nodejs.org/en/

## Getting the source 
```bash
git clone https://github.com/WebCookInc/dentalintel-windows-app.git
cd dentalintel-windows-app/
```

## Installing Dependencies
```bash
# install electron-forge globally
npm install -g electron-forge

# install dependencies
npm install

# testing app
npm start
```

### ScaleDrone Pusher Page

https://mark.nscook.net/scaledrone/pusher.html

### ScaleDrone Client Page

https://mark.nscook.net/scaledrone/scaledrone-client.html

## Building and Packaging
```bash
electron-forge package
```

## Creating Installer

Using <a href="http://nsis.sourceforge.net/Download" target="_blank">NSIS</a> software for the windows installer.

* download the NSIS 
* package your application using `electron-forge package`
* compress the packaged application located on `/out` directory
* compile the compress application using the NSIS `Installer base on ZIP file`


signtool.exe sign /f DentalIntel.pfx /d "Dental Intel Desktop" /p denta!inte! /t "http://timestamp.comodoca.com/authenticode" snoretoast.exe

"# didesktop" 
