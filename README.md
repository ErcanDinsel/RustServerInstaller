# Rust Server Installer
This script installs a Rust server on your Windows machine using a single file. It handles all necessary steps for a smooth installation process, including setup, configuration, and any required plugins.
# Overview
SteamCMD Installation – Easily install SteamCMD for Rust server setup.

Supports both official release and staging branch versions for flexible server setup.

Custom Map Support - Option to add RustEdit DLL during installation for custom map integration.

Oxide Support – (Not supported for the staging version.)

Carbon Plug-in - Support 

Configure admin access after installation for better server management.

Automatically generate management files like StartServer.bat, UpdateServer.bat, and WipeServer.bat based on user input.


# Usage

Start "rustserverinstaller.bat"

You can install it by following the instructions in the cmd window.

Works on Windows 10, Windows 11,Windows Servers/2016+/

There is no problem with Windows defender, but some virus programs may interfere with the installation. If you encounter any problems, you should close the virus program and try again.


# How to Join 

After the server installation, start the server automatically or run the server with the startserver.bat file where you installed the server.

Open the game, press f1 and type “connect localhost” (no quotes)

If your server is hosted on another machine in your local network: client.connect MachineIP:ServerPort

An example of what you would type when using the default Server Port of 28015: client.connect 192.168.1.1:28015
