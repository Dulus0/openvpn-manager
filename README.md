# Description

OpenVPN Manager is a tool which controls OpenVPN. It is written in C# and uses the management interface of OpenVPN to control connections.
Use the smart card feature in a simple way, enter passwords, monitor the OpenVPN log etc...
The goal is to be a simple but powerful OpenVPN GUI.

# Want to know more?

The [wiki pages](https://github.com/jochenwierum/openvpn-manager/wiki) contain more information. Feel free to contribute!

# Download

You can download OpenVPN Manager using the [download page](http://openvpn.jowisoftware.de/downloads/).

# License

OpenVPN Manager is licenced under GPL v2, see the included licence.txt

# History
 * New in 0.0.3.8 (28.04.2013) (thanks to Gaki and ezechiel1917)
  * Bugfix: long config names leads to errors when they were displayed as quick info in the taskbar notification icon
  * Honor log-append directive in config files
 * New in 0.0.3.7 (27.04.2013) (thanks to gwww, ezechiel1917, EvilOlaf and dillydog)
  * IMPORTANT: before installing this version please uninstall the OpenVPN Manager service from version 0.0.3.6 by running `openvpnmanager.exe -uninstall` as admin
  * Moved OpenVPN Manager into a separate process
  * Use log file path from config (if one is set)
  * Show connection status in quick info
  * Added support to load custom tray icons
  * Show status window while connecting
  * Several installer improvements
 * New in 0.0.3.6 (04.11.2012) (thanks to PiBa-NL)
  * change: Added OpenVPNManager Service as alternative to OpenVPN Service with restarting feature (see [Wiki](https://github.com/jochenwierum/openvpn-manager/wiki/OpenVPNManagerService))
  * change: time of log messages is shown in the log status window
  * change: company name JoWiSoftware used in AppData for user.settings file.
  * change: new Installer (NSIS-based) installes OpenVPN Manager, OpenVPN and downloads the .NET Framework if it is missing
  * change: some UI-changes
  * change: Username and Password fields select text on focus
  * change: Option to save username in username+password dialog.
  * change: drawing issue fix in status log window when resizing.
  * fix: sometimes password was not processed/received by OpenVPN process..
  * fix: Settings are automatically detected on first start
 * New in 0.0.3.5 (12.10.2012) (thanks to PiBa-NL)
  * change: Doubleclick on systray-icon now starts/stops vpn if only a single profile exists
  * fix: fixed crash on cancelling username/password dialog
  * fix: workaround for OpenVPN.exe terminated on canceling username/password dialog
  * fix: UI Typos
 * New in 0.0.3.4 (28.08.2012)
  * change: Window does not flicker on startup (Thanks to Ingo)
  * change: More useful menu ordering (Thanks to Martin)
  * change: Setup included (Thanks to Ingo)
